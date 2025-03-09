# House Prediction (Under Development)

- apply all the MLOPs principles and practices 
- core ML
- MLOPs priniciples  

# Tools

- ZenML to create pipelne and it is a MLOPs framework 

# Flow
Install ZenML - https://docs.zenml.io/getting-started/installation 

zenml integration install mlflow -y 

The project can only be executed with a ZenML stack that has an MLflow experiment tracker and model deployer as a component. Configuring a new stack with the two components are as follows:

zenml integration install mlflow -y
zenml experiment-tracker register mlflow_tracker --flavor=mlflow
zenml model-deployer register mlflow --flavor=mlflow
zenml stack register local-mlflow-stack -a default -o default -d mlflow -e mlflow_tracker --set

# Design patterns

- Factory design pattern (e.g. Coffe -> Expresso, Latte, Cuppiciono):



# References & Citation
this content is created using large language models, different sources in internet and also the following a course on YouTube:
https://www.youtube.com/watch?v=o6vbe5G7xNo&t=133s

