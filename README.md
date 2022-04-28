NLP and ML for sentiment analysis of opinions:

We will use the Python scikit learn library in order to create and evaluate various classifiers that will allow us to determine the sentiment expressed in texts: positive or negative.

The dataset we are going to work with can be downloaded from the following URL: https://www.kaggle.com/nehasontakke/amazon-unlocked-mobilecsv
The dataset used is the following Amazon_Unlocked_Mobile.csv, released by PromptCloud and containing information on opinions, ratings and prices of nearly 400,000 unlocked mobile phones sold on Amazon.com

To prepare the text type data, we will see the operation of both the CountVectorizer class and the TfidfVectorizer class of scikit learn, with which we will obtain the frequency of the text tokens.

We are going to implement, train and evaluate three different classifiers. They will be a Naive Bayes model, a Logistic Regression model and a Support Vector Machine (SVM) model. We will calculate different metrics for each of the classifiers that we have just trained, in order to compare them and later decide which one allows us to obtain the best results. We will calculate for each of them its confusion matrix, accuracy, precision, recall, F1-score, ROC curve and area under it (AUC). In addition, we will apply cross validation and see the results it offers us.

-----------------------------------------------------------------------------------------------------------------------------------------------

ML con PLN para Análisis de Sentimientos de opiniones:

Usaremos la librería scikit learn de Python con el fin de crear y evaluar varios clasificadores que nos permitan determinar el sentimiento expresado en textos: positivo o negativo.

El dataset con el que vamos a trabajar se puede descargar desde la siguiente URL: https://www.kaggle.com/nehasontakke/amazon-unlocked-mobilecsv
El dataset usado es el siguiente Amazon_Unlocked_Mobile.csv, liberado por PromptCloud y que contiene información sobre opiniones, calificaciones y precios de cerca de 400.000 teléfonos móviles libres vendidos en Amazon.com

Para preparar los datos de tipo texto, veremos el funcionamiento tanto de la clase CountVectorizer, como de la clase TfidfVectorizer de scikit learn, con las que podremos obtener la frecuencia de los tokens del texto.

Vamos a implementar, entrenar y evaluar tres clasificadores distintos. Serán un modelo Naive Bayes, un modelo de Regresión logística y un modelo de Máquinas de Vectores de Soporte (SVM). Calcularemos diferentes métricas para cada uno de los clasificadores que acabamos de entrenar, para poder compararlos y posteriormente decidir cuál es el que mejores resultados nos permite obtener. Calcularemos para cada uno de ellos su matriz de confusión, tasa de acierto, precisión, recall, F1-score, curva ROC y área bajo la misma (AUC). Además, aplicaremos validación cruzada y veremos los resultados que nos ofrece.

