# Operationalizing ML in Azure

## Table of contents
* [Overview](#Overview)
* [Architectural Diagram](#Architectural-Diagram)
* [Key Steps](#Key-Steps)
* [Screen Recording](#Screen-Recording)
* [Future work](#Future-work)
* [References](#References)


## Overview
In this project, we build, deploy, and consume an ML model in Azure ML studio. Two approaches were implemented for developing and deploying the ML model, the first approach involved building a model using AutoML, and then deploy the best model. Once the model was deployed, it was consumed with the help of Swagger UI using the REST API endpoint and the primary key genrated for the deployed model. The second approach followed the same steps but it was performed using the Python SDK in [Jupyter Notebook](aml-pipelines-with-automated-machine-learning-step.ipynb). The steps taken in both approaches and the results are explained below.
<br>
The dataset provided contains data related to a direct marketing campaign for a bank. This is a binary classification problem with the goal to predict if a client will subsrcibe a term deposit or not. However, the goal of this project is to get familiar with deployment and consuming the ML model rather than focsuing on building the most accurate model for the classification tasl. There are 20 features (columns) in total which includes customers age, job, maritual...etc. and the target column "y" which is a "Yes" or "No". The original dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

## Architectural Diagram
*TODO*: Provide an architectual diagram of the project and give an introduction of each step. An architectural diagram is an image that helps visualize the flow of operations from start to finish. In this case, it has to be related to the completed project, with its various stages that are critical to the overall flow. For example, one stage for managing models could be "using Automated ML to determine the best model". 


## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps. 


## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:



## Future work


## References

