# Data Science Project

A ==Data Science== project to deploy a model that will read some data generated by a smoke detector and will try to predict wether is a fire or not in the local.

# Tasks
- [x]  Read the dataset
- [x]  UTC to datetime
- [x]  There is no null data
- [x]  Data description
- [x]  Plots
- [x]  Train & Test Split
- [x]  Logistic Regression Model
- [x]  Accuracy

## Smoke Detection Dataset

![Smoke_Detection](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRznbDftAYZ59Gnj8vpeI-2Aiw5G6f5VmRJWA&usqp=CAU)

### Features
* UTC           
* Temperature[C]
* Humidity[%]   
* TVOC[ppb]     
* eCO2[ppm]     
* Raw H2        
* Raw Ethanol   
* Pressure[hPa] 
* PM1.0         
* PM2.5         
* NC0.5         
* NC1.0         
* NC2.5         
* CNT           
* Fire Alarm    

# Demonstration

Logistic Regression
![App Screenshot](https://matheusfacure.github.io/img/tutorial/perceptron1.gif)


### Sigmoid Function
$\Sigma(\Theta^TX)$ = $\frac{1} {1 + e^-\Theta^Tx }$
$\hat{y}$ = $\Sigma(\Theta^T X)$

### Cost Function
$Cost(\hat{y}$, y) =  $\frac{1}{2}(\Sigma(\theta^TX)-y)^2$

### Mean Squared Error
J($\theta$) = $\frac{1}{m} \Sigma_{i=1}^{m} Cost(\hat{y}, y)$

### Logistic Regression Cost Function
$J(\Theta)$ = -$\frac{1}{m} \Sigma_{i=1}^my^ilog(\hat{y}^i) + (1-y^i)log(1-\hat{y}^i)$

## Images

Correlation Map
![Correlation](https://github.com/ViniciusHolanda001/smoke_detection/blob/main/data/images/correlation_output.png)


Confusion Matrix
![CFM](https://github.com/ViniciusHolanda001/smoke_detection/blob/main/data/images/cfm.png)


Temperature -> ECO2
![T&ECO2](https://github.com/ViniciusHolanda001/smoke_detection/blob/main/data/images/temperature_eco2.png)


## References

 - [Smoke Detection Dataset](https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset)
 - [Stefan Blattmann Article](https://www.hackster.io/stefanblattmann/real-time-smoke-detection-with-ai-based-sensor-fusion-1086e6)
 - [Storopoli & Souza (2020). Ciência de Dados com Python: pandas, matplotlib, Scikit-Learn, TensorFlow e PyTorch](https://github.com/storopoli/ciencia-de-dados)
