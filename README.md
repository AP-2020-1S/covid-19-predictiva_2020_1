# Pronostico de la evolución de casos activos de SARS-CoV-2 en Colombia


## Cuaderno

El cuaderno de colab realizado para el análisis de datos del proyecto se encuentra en este [link](https://colab.research.google.com/drive/12hCvQw-_B6mOqrugQnW1OA2x_tIYxdg_?usp=sharing) (Acceder desde cuenta unal). Este mismo también se encuentra subido en el repositorio como ProyectoCovid.ipynb, para correrlo localmente, en caso de correrlo localmente se necesitan los siguientes paquetes instalados: 

*   sodapy
*   pandas
*   matplotlib.pyplot
*   sklearn

En este se encuentra todo el procedimiento para  la limpieza, análisis, y predicción propuesta para los datos de Covid-19 otorgados por el gobierno colombiano. 


## Producto de Datos 

Para el producto de datos se hizo uso de la librería de python Streamlit, que permite crear fácil y rápidamente aplicaciones de datos. En esta aplicación se exponen los análisis realizados, comenzando con un dashboard realizado en Google Data Studio para ver el análisis exploratorio de los datos y después se presentan todo el proceso y resultado del modelo predictivo

Para la instalación del producto de datos en el equipo se sugiere la versión 3,7 de python o superiores y comenzar la instalación con la creación de un entorno virtual en el PC local como se ve en la [documentación](https://docs.python.org/es/3/tutorial/venv.html) 

Teniendo listo el entorno virtual los siguientes pasos:

`git clone https://github.com/AP-2020-1S/covid-19-predictiva_2020_1.git` 

dentro de la carpeta donde instalaste el entorno virtual


Se deben hacer las instalaciones correspondientes a los paquetes requeridos por la aplicación

`pip3 install streamlit`

`pip3 install sodapy`

`pip3 install pandas`

`pip3 install matplotlib`

`pip3 install sklearn`


Finalmente queda listo para ver la aplicación de forma local corriendo el siguiente comando

`streamlit run data.py`

La aplicación se abre por defecto en el navegador predeterminado el en puerto:


http://localhost:8501/


Para una visualización rápida del producto de datos presentamos un [video](https://github.com/AP-2020-1S/covid-19-predictiva_2020_1/blob/master/streamlit-data-2020-09-07-09-09-89.webm.mp4) que muestra el contenido de la aplicación y que se puede descargar de este mismo repositorio. [video](https://github.com/AP-2020-1S/covid-19-predictiva_2020_1/blob/master/streamlit-data-2020-09-07-09-09-89.webm.mp4)

