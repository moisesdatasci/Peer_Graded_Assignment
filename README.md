# 🏡 Boston Housing — Final Project

Análisis del conjunto de datos de viviendas de Boston

Este proyecto corresponde a una actividad práctica donde se analizan variables del **Boston Housing Dataset** mediante técnicas de estadística descriptiva, pruebas estadísticas y modelos de Machine Learning.

---

## 📌 Contenidos del Notebook

### 1. Importación de Librerías
Se utilizan librerías esenciales para análisis, visualización y modelado:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `sklearn`

### 2. Carga del Dataset
Se carga el archivo CSV con los datos de viviendas de Boston y se realiza una inspección inicial (primeras filas, estructura y tipos de datos).

### 3. Análisis Exploratorio de Datos (EDA)
El análisis incluye:
- Estadísticos descriptivos
- Histogramas
- Diagramas de dispersión
- Mapas de calor (correlaciones)
- Exploración variable por variable

### 4. Pruebas Estadísticas Aplicadas
En el notebook se realizan pruebas como:
- **ANOVA** para comparar valores medios de `MEDV` según la variable `AGE`
- **Correlación de Pearson** entre `NOX` y proporción de acres comerciales
- **Pruebas t** para comparar valores medios según variables categóricas
- Interpretación de cada prueba con **α = 0.05**

### 5. Modelos de Regresión
Incluye:
- Regresión lineal simple
- Regresión lineal múltiple
- Evaluación del modelo mediante **R²** y **RMSE**
- Interpretación del impacto de variables como `DIS` sobre `MEDV`

### 6. Conclusiones Generales
El notebook resume los hallazgos obtenidos en las pruebas estadísticas y en los modelos predictivos, respondiendo a cada consigna del proyecto.

---

## 📁 Estructura del Proyecto

```
📦 Peer_Graded_Assignment
 ┣ 📜 Peer_Graded_Assignment_jupyterlite_.ipynb
 ┣ 📄 boston_housing.csv
 ┗ 📘 README.md
```

---

## ▶️ Cómo Ejecutar el Proyecto

### 1. Clonar el repositorio

```bash
git clone https://github.com/moisesdatasci/Peer_Graded_Assignment.git
cd Peer_Graded_Assignment
```

### 2. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 3. Abrir el notebook

```bash
jupyter notebook
```

Luego abrir: `Peer_Graded_Assignment_jupyterlite_.ipynb`

---

## 📊 Sobre el Dataset

El dataset contiene características de viviendas en Boston, entre ellas:

| Variable | Descripción |
|----------|-------------|
| **MEDV** | Valor medio de viviendas ocupadas por propietarios |
| **AGE** | Proporción de viviendas construidas antes de 1940 |
| **NOX** | Concentración de óxidos nítricos |
| **RM** | Número promedio de habitaciones |
| **DIS** | Distancias ponderadas a los centros de empleo |
| **CRIM** | Tasa de criminalidad |
| **INDUS** | Proporción de acres no residenciales |
| **CHAS** | Límite con el río Charles (0/1) |

---

## 🛠️ Tecnologías Utilizadas

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## 🧑‍💻 Autor

Proyecto académico basado en análisis estadístico y técnicas de machine learning aplicadas al **Boston Housing Dataset**.

---

## 📄 Licencia

Este proyecto es de uso académico y educativo.
