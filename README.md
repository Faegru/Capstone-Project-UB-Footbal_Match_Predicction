# Capstone-Project-UB-Footbal_Match_Predicction
Proyecto final del posgrado de DataScience de la UB 2021/2022

Autor: Iván Fernández Aguirre

El proyecto consta de 6 bloques:

1_Exploracion_Inicial: Aquí se explora el dataset original tratando de entender las distintas features. Este notebook carga directamente los datos originales.

2_Corrección_del_dataset: Aquí se corrigen los valores faltantes en el dataset, asi como se eliminan algunas muestras sin casi información. Se genera como resultado un nuevo dataset "FMP_clean". Este notebook carga directamente los datos originales.

3_Tratamiento_de_Variables: Aquí se hace el procesamiento de las features para tratar de mejorar su capacidad predictiva. Se genera como resultado un nuevo dataset: "FMP_final". Este notebook carga el dataset "FMP_clean", asique debe correse después del "2_Corrección_del_dataset".

4_Análisis_del_Dataset_Final: Este datset realiza un segundo analisis de datos, pero centrado en comprender un  poco las variables nuevas generadas. Este notebook carga el dataset "FMP_Final", asique debe correse después del "3_Tratamiento_de_Variables".

5_Modelado_de_los_datos: Aquí se desarrollan y ponen en uso los modelos predictivos. También se trabaja en en balanceo de las clases y en el shapping de los datos para su carga en los modelos. Este notebook carga el dataset "FMP_Final", asique debe correse después del "3_Tratamiento_de_Variables".

Functions_for_FMP: Este notebook contiene una gran mayoria de las funciones utilizadas en todos los notebooks. Es utilizado como una librería o modulo.

Los datos fueron tomados de un desafío Kaggle: https://www.kaggle.com/c/football-match-probability-prediction y pertenecen a Octosport and Sportmonks.
