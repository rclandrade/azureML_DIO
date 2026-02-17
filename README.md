# azureML_DIO

## This repo was created to show up a case of usage of AzureML to process data in a ML Pipeline using the builtin tools.


**For this activity I have decided to use a real data set that I got for my TCC in the MBA of USP Esalq in DSA, what I will briefly explain below**

The data used for this activity what acquired using the DAQ hardware that I have designed I then packaged to be analyzed and processed with ML. Basically my goal on the TCC is to show that it is possible to identify properties of the load based on the behavior of voltage and current supplied by the power supply.


 - DAQ Prototype:

![DAQ](./DAQ_Prototype.jpeg)
 
 - Dataset link:

[dataset.csv](./dataset_teste_1771164123.csv)

To execute this DiO lab I have created to kinds of flow, one using the AutoML function and the second using the design function, what I show below:

**OBS: For both methods I have selected the state as output so that I could try to check whether there was correlation between Voltage/Current and the infered load state.**

 1. Auto ML:





2. ML Designer:




As we can see, both of the methods have returned a strong model with really good accuracy and ROC.
