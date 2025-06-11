# Modelo de Regresión Logistica con Keras

Este proyecto implementa un modelo de regresión logistica para predecir la especie de cada flor `Setosa`, `Versicolor` o `Virginica` utilizando las caracteristicas de los petalos y sepalos del dataset `Iris`.

## Dataset
[Iris - Kaggle](https://www.kaggle.com/datasets/uciml/iris)
El conjunto de datos Iris se utilizó en el artículo clásico de R.A. Fisher de 1936, "El uso de mediciones múltiples en problemas taxonómicos", y también se puede encontrar en el Repositorio de Aprendizaje Automático de la UCI.
Incluye tres especies de iris con 50 muestras cada una, así como algunas propiedades de cada flor. Una especie de flor es linealmente separable de las otras dos, pero las otras dos no lo son entre sí.

## Tecnologías utilizadas
- Python 3.10
- Jupyter Notebook 
- Pandas  
- Keras
- Tensorflow

## Cómo clonar y ejecutar el proyecto

1. Clonar el repositorio

```bash
git clone https://github.com/Fleitaselene-dev/ml_regresion_logistica_keras.git
cd ml_regresion_logistica_keras
code .
```
2.  Crear un entorno virtual
* Windows:
```bash
py -m venv env
```
* Linux/macOs:
```bash
python3 -m venv env
```
4. Activar el entorno virtual (env)
* Windows:
```bash
env\Scripts\Activate
```
* Linux:
```bash
source env/bin/activate
```
5. Instalar las dependencias
```bash
pip install -r requirements.txt
```
6. Ejecutar las celdas de jupyter notebook
