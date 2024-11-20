# Riesgo Crediticio

Este proyecto utiliza el conjunto de datos [GiveMeSomeCredit](https://www.kaggle.com/c/GiveMeSomeCredit/) de Kaggle, creado por Credit Fusion y Will Cukierski, para analizar el riesgo crediticio.

El riesgo se entiende como la probabilidad de que ocurra un evento que pueda tener consecuencias negativas. En nuestro caso, el riesgo crediticio se refiere a la probabilidad de que una persona incumpla con el pago de sus créditos. Un crédito es un instrumento financiero en el que una persona se compromete a recibir una cantidad de dinero y devolverla junto con los intereses acordados. La palabra "crédito" proviene del latín y significa "creer"; esto representa la confianza que las instituciones financieras depositan en sus clientes. Sin embargo, surge una pregunta importante: **¿bajo qué condiciones una persona podría dejar de pagar sus deudas?**

### Importancia del análisis de riesgo crediticio

Las instituciones financieras dependen de este análisis para minimizar pérdidas y gestionar el capital. A diferencia de instrumentos como los CETES (Certificados de la Tesorería de la Federación) en México, que son respaldados por el gobierno y se consideran libres de riesgo, los préstamos personales y créditos bancarios conllevan un riesgo de incumplimiento. Si un cliente no paga, la institución pierde capital y los intereses esperados.

En este proyecto, exploramos los datos para identificar patrones y factores que puedan predecir cambios en el perfil de los clientes y así estimar la probabilidad de impago.



# Entrega

Este proyecto tiene como entrega una carpeta de drive. Pero esta respaldado en el [perfil de github](https://github.com/dt-sc-Josue-Diaz/Proyecto-DS-II).

En esta entrega obtuvimos un modelo de XGBoost para predercir la morosidad de un cliente que tiene cierto perfil bancario.  



Obtuvimos este resultado;

# Resultados del Modelo

## ROC-AUC

- **Entrenamiento**: 0.89  
- **Prueba**: 0.87  

---

## Métricas de Clasificación - Entrenamiento

| Clase | Precision | Recall | F1-Score | Support |
| ----- | --------- | ------ | -------- | ------- |
| 0     | 0.80      | 0.83   | 0.81     | 7018    |
| 1     | 0.82      | 0.79   | 0.80     | 7018    |

**Accuracy**: 0.81  
**Macro Avg**: Precision=0.81, Recall=0.81, F1-Score=0.81  
**Weighted Avg**: Precision=0.81, Recall=0.81, F1-Score=0.81  

---

## Métricas de Clasificación - Prueba

| Clase | Precision | Recall | F1-Score | Support |
| ----- | --------- | ------ | -------- | ------- |
| 0     | 0.78      | 0.82   | 0.80     | 3008    |
| 1     | 0.81      | 0.77   | 0.79     | 3008    |

**Accuracy**: 0.80  
**Macro Avg**: Precision=0.80, Recall=0.80, F1-Score=0.80  
**Weighted Avg**: Precision=0.80, Recall=0.80, F1-Score=0.80  



## Referencias

@misc{GiveMeSomeCredit,  
    author = {Credit Fusion and Will Cukierski},  
    title = {Give Me Some Credit},  
    year = {2011},  
    howpublished = {\url{https://kaggle.com/competitions/GiveMeSomeCredit}},  
    note = {Kaggle}  
}  
