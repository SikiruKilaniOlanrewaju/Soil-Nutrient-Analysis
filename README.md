# Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT
An Web Application developed using Streamlit to predict the suitable crop for a particular land. This is predicted by using Sentinal and Landsat images.

# Architecture used for crop prediction using ML
![ML1](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/fd4973c1-e381-4689-8491-581367363033)

# Architecture used for Analysis of Soil Nutrients using IOT
![iot](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/5fba3095-5615-417f-908a-a3d6ba212e9a)

# IOT Component
    * Connection for the circuit(Change needs to be done by removing NRF24L01)
![IoT Connection](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/913673aa-7ef4-4593-b8f4-5a72849d9bdf)




    * This is the Output of IOT Component
![IoT-Output](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/904ccbe8-f02a-4ab8-b280-6fad8559ba98)



# Architecture used for Satellite Imaging
![satelliteimage](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/0377b46c-3531-45a1-a106-9c067241ef3b)


# Overall Architecture
![overall](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/82519637-dfdf-4a12-b19a-50a23fa5e8a3)

# Dataset
The data used to train the model was collected from the Crop Prediction dataset. The dataset consists of 2200 samples of 22 different crops whose predictions are made using 7 features: nitrogen, phosphorus, potassium, and pH content of the soil, temperature, humidity and rainfall. The dataset is perfectly balanced, with each crop having 100 samples. 

![crop](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/1b2d77f0-232a-4241-938d-0b4d6c3f3907)


# Attributes information:

N - Ratio of Nitrogen content in soil

P - Ratio of Phosphorous content in soil

K - Ratio of Potassium content in soil

Temperature - temperature in degree Celsius

Humidity - relative humidity in %

ph - ph value of the soil

Rainfall - rainfall in mm

# Procedure

* Create an ML model for Crop prediction using the code provided in Crop Prediction module.
  
* We are using the LGBM algorithm since it shows higher accuracy than other algorithms.
  
* Open a new project in Google Earth Engine.

* Download Landsat and Sentinal images by using the code which is given in Google Earth Engine module.

*  Then Create an UI to display using the code in streamlit(new.py) module.

* Insert the necessary ML models as per the code and change the file path accordingly. (as per ML models module)

* Then after the new.py runs successfully follow the Steps provided in the OUTPUT of this readme.   

# Accuracy of Crop Prediction Algorithms
![accuracy](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/14137873-d79b-4ea4-94c5-b259bbb428cc)

# Confusion Matrix
![confusion](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/49b0d09f-ab84-4914-9f83-a6105aa483d6)

# Web UI
![webui-1](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/d3f723b2-defd-404f-bf06-fb16bb202849)
![webui-2](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/7bf83012-b5ea-4513-96d4-2685defad794)

# OUTPUT
> We need to upload Sentinal and landsat images seperately.

![output1](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/7e77d2fe-3e7b-4680-b7ee-c4f3a740f053)


![output2](https://github.com/SasiKumar2003/Crop-Prediction-Using-ML-and-Analysis-of-Soil-Nutrients-using-Satellite-imaging-and-IoT/assets/88201153/0f12e84e-1c3c-4fde-aa96-9da12a0c90f9)




* Step 1: We provide Sentinal image to get the analysis of soil nutrients such as " nitrogen, phosphorus, potassium, temperature, humidity ". 

* Step 2: We Provide Landsat image to get the analysis of soil nutrients such as " Ph "

* Step 3: Provide Rainfall Input.

* Step 4: Click Predict Button to get the Crop Prediction result.
  

# For further doubts reffer Documentation Module

 
