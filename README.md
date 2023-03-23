# AWS - Operationalizing a ML Workflow
As part of this project different AWS options for training and deploying a classification model were used.
More details are summarised in the writeup.pdf file. The following steps were carried out:
- Step 1: Training and Deployment on SageMaker
- Step 2: EC2 Training
- Step 3: Lambda Function Setup
- Step 4: Lambda Security and Testing
- Step 5: Concurrency and Auto-scaling

### Dataset
The dataset for the dog breed classification containing 133 classes was used for this project.

### Code
Starter files were supplied to start the project, which were then completed as part of the project. The main files are:
    - train_and_deploy_solution.ipynb (notebook to run pre-processing, tuning, training and model deployment as part of a pipeline)
    - hpo.py (python script that carries out hyperparameter tuning (and training of model)
    - inference2.py (script used as entry point for model endpoint deployment for inference)
    - lambdafunction.py (code to run lambda function to make inferences using deployed endpoint)
    - ec2train1.py (code to train the model on EC2 instance)
    - writeup.pdf (contains a detailed description of solutions to the five steps above with screenshots)
    - screenshots: folder that contains the project relevant screenshots
