# **<h1 align="center">Proyecto_3. Competición en Kaggle</h1>**
===============================================================
El objetivo del proyecto era participar en una competición de Kaggle que tiene como finalidad conseguir la mejor predicción de precio de un diamante.

💻 **Technology stack**
-----------------------
- [Python](https://docs.python.org/3.7/l)
- [sqlite3](https://www.sqlite.org/index.html)
- [Pandas](https://pandas.pydata.org/)
- Numpy
- [Sklearn](https://scikit-learn.org/stable/)
- Jupyter notebook
- [DBeaver](https://dbeaver.io/)

**Consulta de datos**
-----------------------
Hemos partido de dos dataset:
- Uno para el entrenamiento
- Otro para el testing

⏩ **Resultados**
-----------------------
Se han entrenado tres modelos, expopngo los dos con mejores resultados:
- Resultado 554
  - Se ha conseguido otorgándole un valor proporcional a las features cut y color.  
- Resultado 608
  - Intenté que no existieran valores decimales, si no que todos los valores fueran números enteros para, desde mi punto de vista, normalizar un poco más los datos. No obstante, el resultado empeoró.

En ambos casos el modelo utilizado ha sido RandomForest.

**Siguientes pasoso o puntos de mejora**
-----------------------------------------
La clave de este proyecto estaba en probar diferentes opciones y modelos, hacer una buena limpieza de datos y selección de features. Por ello, como puntos de mejora para proyectos similares, anotaría, dedicar más tiempo para la búsqueda de información y conocimiento del tema, así como para la prueba de modelos.
