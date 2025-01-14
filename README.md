# Build, Deploy, and Monitor ML Models with Amazon SageMaker

## What version of the SageMaker Python SDK does this course use?

The notebooks in this repository rely extensively on the official [SageMaker Python SDK](https://sagemaker.readthedocs.io/en/stable/) to interact with SageMaker. These notebook were originally written and released using version 1.x of the SDK. 

[Version 2.x](https://sagemaker.readthedocs.io/en/stable/v2.html) of the SageMaker Python SDK was [released on August 4th, 2020](https://pypi.org/project/sagemaker/#history). At this point the notebooks were ported to v2 of the SDK.

Version 1.x of the SDK is **no longer supported** by this course. If you're running the v1.x notebooks, you should upgrade to v2.x.

### Upgrading from Version 1.x to Version 2.x

To upgrade to version 2.x:

1. Install the latest version of the SageMaker SDK by running `pip install --upgrade sagemaker`. If you are executing this pip install command in a notebook, make sure to restart your kernel.
2. Pull the latest version of this repository.

## Notebooks

* [Ch. 2 Setting Up SageMaker Studio](https://github.com/plotti/sagemaker-course/blob/master/notebooks/ch02_setup.ipynb) - In this chapter we set up the SageMaker Studio development environment and interact with Studio's visual interface. This notebook installs additional depenencies.
* [Ch. 3 Interactive Model Training](https://github.com/plotti/sagemaker-course/blob/master/notebooks/ch03_interactive_model_training.ipynb) - In this chapter we learn how to interactively train models in SageMaker using built-in algorithms and custom training code. In particular, we train customer churn prediction models using XGBoost and scikit-learn.
* [Ch. 4 Experiment Management](https://github.com/plotti/sagemaker-course/blob/master/notebooks/ch04_experiment_management.ipynb) - In this chapter we learn how to use SageMaker Experiments to organize the results of deep learning experiments. We train models using the Tensorflow and PyTorch frameworks, perform hyperparameter optimization, and find the best performing model.
* [Ch. 5 Model Deployment](https://github.com/plotti/sagemaker-course/blob/master/notebooks/ch05_model_deployment.ipynb) - In this chapter learn how to deploy trained models in SageMaker by deploying the models we trained in previous chapters. We demonstrate how to perform batch inference using SageMaker Batch Transform and how to perform online inference with hosted API endpoints. Finally, we configure autoscaling for hosted endpoints.
* [Ch 6. Model Monitoring](https://github.com/plotti/sagemaker-course/blob/master/notebooks/ch05_model_deployment.ipynb) - In this chapter we learn how to use Model Monitor to monitor deployed endpoints. This lets us detect data drift by capturing and storing incoming feature data and comparing the distributions of live data to training data.


## Additional Information

Many of the code samples in this repository have been adapted from the examples in the [Amazon SageMaker Examples](https://github.com/awslabs/amazon-sagemaker-examples/) repository. That repository is a fantastic source to learn more about SageMaker. 
