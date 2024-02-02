*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Your Project Title Here

*TODO:* 
This project was completed to satisfy requirements for the Azure Machine Learning Nanodegree offered by Udacity.  I demonstrate registering a dataset, configuring an AutoML job, deploying a ML model, leveraging REST endpoints of said model from Azure Machine Learning Studio.  Using Python SDK in the attached notebook, I then create and publish a ML pipeline.

## Architectural Diagram
*TODO*: Provide an architectual diagram of the project and give an introduction of each step. An architectural diagram is an image that helps visualize the flow of operations from start to finish. In this case, it has to be related to the completed project, with its various stages that are critical to the overall flow. For example, one stage for managing models could be "using Automated ML to determine the best model". 

## Key Steps
### Part One: Creating, deploying and leveraging ML model

First I registered the required dataset.
![screenshot1](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/Dataset.png)

Next, I created an AutoML job to find the best model to predict values from the Bankmarketing dataset.  The completed job results are documented below.
![screenshot2](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/CompletedAutoMLJob.png)

Here are some interesting details about the best model.
![screenshot3](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/ModelAlgorithms.png)

![screenshot4](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/ModelExplination.png)

Next, I deployed the model, enabling authentication, using Azure Container Instance.
![screenshot5](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/DeployingModel.png)

Then, I enabled application insights.
![screenshot6](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/EndpointDetails.png)

The below screenshot shows the resulting output from running the provided logs.py file. 
*todo* add screenshot
![screenshot8](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/ServerRoutes.png)
![screenshot9](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/ServerOutput2.png)

The model was then consumed using swagger by running swagger.sh and swagger.py.  
Below are images of the swagger interface to my deployed model.
![screenshot10](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/SwaggerView.png)

I also tested the endpoint via commandline with the provided test data.
![screenshot11](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/EndpointResults.png)

### Part Two: Documenting ML Pipeline
This section is evidence of the resulting ML pipeline generated from the Juypter notebook.

Below is the created pipeline.
[!screenshot12](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/CompletedPipeline.png)

[!screenshot13](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/PipelineDetails.png)

[!screenshot14](https://github.com/torijule/nd00333_AZMLND_C2/blob/master/sample_screenshots/PipelineEndpoint.png)

Successful pipeline runs
*todo* add here

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
