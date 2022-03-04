# DASHBOARD para el estudio de las ofertas de empleo en Aragón

<!--- 
![alt text](https://github.com/[username]/[reponame]/blob/[branch]/icon_offer.png?raw=true)
--->

<p align="center">
  <img width="100" height="100"src="https://static.thenounproject.com/png/305581-200.png" />
</p>

Este repositorio contiene el código fuente de una aplicación basada en técnicas de Procesamiento del Lenguaje Natural (PLN) que facilita analizar las ofertas de empleo disponibles en Aragón a partir de diferentes criterios (sector, provincia, ciudad, oficina, fechas, etc.).

## Conjunto de datos
El conjunto de datos que se obtuvo fue el resultado de analizar, extraer y preprocesar un conjunto de documentos PDF disponibles en el portal de [INAEM](https://inaem.aragon.es/ofertas-de-empleo), en el rango de fechas del 2021 hasta los días actuales.

En la siguiente tabla, se muestran estadísticas resultantes de la fase de extracción de información relevante desde documentos PDF.

| **Documentos PDF** | **Ofertas de empleo** | **Sectores** | **Columnas** |
|---|---|---|---|
| 11 | 584 | 19 | 13 |

## Instalación de librerías requeridas

```python
$ pip install -r requirements.txt
```

## DASHBOARD desde Streamlit

```python
conda activate [env_name]
cd ./src/main/streamlit/app.py
streamlit run app.py
```

## Desarrolladores

- Mariana Morao Santos - [mariana-morao@hotmail.com](mariana-morao@hotmail.com)
- Esther Puisac Nogarol - [epuisac@hotmail.com](epuisac@hotmail.com)

## Referencias
[1] Mariana Morao y Esther P. Nogarol. EL MERCADO DE TRABAJO: MENOS INFOJOBS Y MÁS TINDER, pp. 10, 2022. https://medium.com/@ferringayo/el-mercado-de-trabajo-d73d79ed3c06
