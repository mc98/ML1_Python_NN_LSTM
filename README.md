# ML1_Python_NN_LSTM
This is a team project in the course Machine Learning-I
# TITLE: 
Machine Learning Quality Prediction for a Flotation Mining Process

## PROJECT MOTIVATION: 
Currently, companies are required to provide products that comply with rigorous industry standards, while at the same time meeting and exceeding their customers’ needs and expectations. Therefore, organizations often have strategies to improve the quality of their work processes and their products, since failure to address quality standards could result in customer dissatisfaction, a bad reputation, and problems with regulatory agencies (in the case of more regulated industries, such as the mining industry). Additionally, proper quality control could prevent the costs associate to inefficiencies, downtimes in production, and low revenues, among others. As mentioned by Schmitt et al., the complexity of inspection and operation has increased; thus, requiring the application of the latest technology the era of Industry 4.0 has to offer. Nevertheless, Usuga et al. reported that 55% of ML-aided production planning and control activities (PPC) involved scheduling, and only 3% involved quality control. 
 
As indicated in the description of the data set, during a mining operation the impurities (in the form of silica) in the ore concentrate are measured every hour. Early detection of such impurities could be beneficial for engineers as they would have more information on the process and the quality of their concentrate. Additionally, reducing the number of impurities in concentrate could benefit the environment by reducing the amount of ore that goes to tailings, waste stream. A ML model approach seems appropriate for the accurate prediction of the percent of silica in the iron ore concentrate.

## OBJECTIVES: 
Develop a ML algorithm that can predict the percent of silica in the iron ore concentrate every hour, and if it is possible every minute. Additionally, one would assess and compare the accuracy in the measurements provided for the different rates (i.e., every hour vs. every minute). 

Due to the lack of trends in algorithms for manufacturing plants, especially mining plants, another objective is to clearly identify the strengths and weaknesses of the method (or combination of algorithms) that could potentially provide the most accurate prediction; the modelling results could have the potential to incentivise the application of ML techniques for manufacturing processes. 

Even though the dataset has received over 82.0k views, the number of unique contributors is limited to 58 – and most of them have focused on running either a regression analysis or a random forest generator on the data set. For this reason, it would be particularly interesting to evaluate the predictive power and performance of additional methods like neural networks, particularly an artificial recurrent neural network like Long Short-Term Memory.
## What input data is available for the algorithm?   
The original dataset was collected from machine sensors of the flotation columns of a mining operation every 20 seconds (in some cases) during a 6 month range from march of 2017 until September of 2017.
## What would be the specific output? 
The most accurate prediction model to predict the percent of silica in the iron ore concentrate – comparing the model’s predictive accuracy when output is measured every hour vs.  every minute. Provide valuable insight on the correlation and relationship between factors of the dataset. An evaluation of the accuracy and performance of the generated model on other types of domains (i.e., retail, consumer goods, automotive, etc.).

  Quality Predictions in a Mining Process (2017-12-06) EduardoMagalhãesOliveira https://www.kaggle.com/edumagalhaes/quality-prediction-in-a-mining-process
