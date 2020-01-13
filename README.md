# mlflow-end-to-end
MLflow end-to-end demo (tracking, projects, model) with Azure Databricks

# Agenda

**In this notebook** we will demonstrate the following topics:<br>

<img src="https://i.imgur.com/7yofoyJ.png" style="width:1800px"/> <br>

#### Step 1: Load our exploration dataset into a DataFrame
In this case, we'll be using the "[Inside Airbnb](http://insideairbnb.com/get-the-data.html)" dataset, and loading it from a csv from an Azure Storage Container.

#### Step 2: Perform basic exploratory analysis
Like plotting on a heatmap to get a better sense of the data.

#### Step 3: `Tracking` Demo: Random Forest Experiment
We perform multiple experiments using scikit-learn's Random Forest Regressor and log the models on MLflow to demonstrate the tracking capabilities.

#### Step 4: `Projects` Demo: Package up a Random Forest model as a Project
We will define these components that makes up an MLflow Project.:
- **MLProject** file
- **Conda** file
- **Run** script <br>

We will also load and run a Project straight from git to demonstrate git integration capabilities.

#### Step 5: `Model Management` Demo: Explore model flavors and framework abstraction capabilities
We explore the power of model flavors and framework abstraction capabilities available with MLflow models.

#### Step 6: `Production Serving` Demo: Containerize the trained model and deploy to Azure Container Instances
We will build a _Docker Container Image_ for a trained model and deploy to _Azure Container Instance_ (can easily swap to Kubernetes as well).

#### Step 7: `Live scoring` Demo: Make a prediction against the live API endpoint
We use an _HTTP call_ and _Postman_ to make a prediction against a test payload.
