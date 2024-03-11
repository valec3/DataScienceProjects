# Google Analytics Customer Revenue Prediction EDA & Prediction

![imagen cover](https://images.squarespace-cdn.com/content/v1/5342fb92e4b0907609b1bf65/ab0f13f5-c1ed-4f65-8aa8-3c9106a576cd/Sales-forecast.png)

## Librerias utilizadas
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)


## Objetivo
El objetivo principal de este proyecto es proporcionar una herramienta para predecir los ingresos de los clientes basados en datos de Google Analytics. Esto puede ser útil para empresas que deseen optimizar sus estrategias de marketing y ventas, identificando a los clientes con mayor potencial de gasto.

## 1. Preprocesamiento de los datos
Analizando el dataset, nos encontramos que algunas columnas se encuentrane en formato JSON:

![algo](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/main/1.JPG?token=GHSAT0AAAAAACPMMJXDJAV75BYWZWOL2Z6MZPOS3VQ)

Convertimos estos datos en nuevas columnas para realizar el análisis:
![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/main/2.JPG?token=GHSAT0AAAAAACPMMJXCQYOU4QSAQSFOZDTEZPOS4HQ)

## 2. Exploración y Feature Engineering

Realizando el EDA sacamos algunas gráficas relevantes:

![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/2626f5db6931c9bd689100f4f014cec4250443d0/3.JPG?token=AYFVGCUPU4KJULZ7VFMUV2TF52JYQ)

![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/2626f5db6931c9bd689100f4f014cec4250443d0/1.EDA.JPG?token=AYFVGCWPTZ5EWTXE7GTW353F52JYQ)

![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/2626f5db6931c9bd689100f4f014cec4250443d0/2.EDA.JPG?token=AYFVGCT4IP72UTQPDQNBAEDF52JYQ)

![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/2626f5db6931c9bd689100f4f014cec4250443d0/3.EDA.JPG?token=AYFVGCSBIGLFXSAXDPGYMEDF52JYQ)

**El feature engineering,**, ha sido implementado en este proyecto como parte fundamental de la preparación de los datos para el modelado predictivo. Durante esta etapa, se han creado nuevas características y atributos a partir de los datos existentes con el objetivo de hacer que los modelos de aprendizaje automático sean más efectivos en la predicción del gasto de los usuarios en el sitio web de comercio electrónico. Este proceso ha sido crucial para mejorar el rendimiento de los modelos y aumentar su capacidad para capturar patrones significativos en los datos, lo que conduce a predicciones más precisas y útiles para la empresa cliente.

![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/2626f5db6931c9bd689100f4f014cec4250443d0/4fe.JPG?token=AYFVGCSPNVBSONSLEIWY23DF52JYQ)

## 3. Modelado predictivo

Se utilizaron técnicas de aprendizaje automático para entrenar modelos predictivos.

## 4. Evaluación y selección del modelo

Se analizaron diferentes modelos:

![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/2626f5db6931c9bd689100f4f014cec4250443d0/EVALUACION%20DE%20MODELO.JPG?token=AYFVGCWRSFCPJNE5TRNHF7DF52K7K)

![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/2626f5db6931c9bd689100f4f014cec4250443d0/METRICA%20DE%20LOS%20MODELOS.JPG?token=GHSAT0AAAAAACPMMJXCPGGHARRX5B4WMCUOZPOSXLQ)

Predicciones con el modelo: 
![](https://raw.githubusercontent.com/Elvis-Donayre/ImagenesRepositorios/main/predicciones.JPG?token=GHSAT0AAAAAACPMMJXCQOWP5JXNLGZ6KYV6ZPOS2JQ)

## Autores
- [Elvis Donayre](https://github.com/Elvis-Donayre)
- [Victor Maye](https://github.com/valec3)
- [Noe Machaca](https://github.com/newneo4)

