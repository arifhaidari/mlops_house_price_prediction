# House Prediction (Under Development)

- apply all the MLOPs principles and practices
- core ML
- MLOPs priniciples

# Tools

- ZenML to create pipelne and it is a MLOPs framework

- Julius: AI Data Analysis - Chat with your files and get expert-level insights in seconds and it is like Excel, Python and ChatGPT in one tool
  https://julius.ai/

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
  https://github.com/arifhaidari/mlops_house_price_prediction/blob/main/reports/factory_design_pattern.py

- Strategy pattern

# References & Citation

- this content is created using large language models, different sources in internet especially medium and freecodecamp
- https://www.kaggle.com/code/tomasmantero/predicting-house-prices-keras-ann
