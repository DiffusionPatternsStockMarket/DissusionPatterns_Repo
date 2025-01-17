<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDPFXrQCarT31BhLslgs8zabgSlsCdA77RT9VcijLX&s" width="500" height="90"> <img src="https://festinfor.webs.upv.es/src/logos/etsinf.png" width="300" height="100" align="right"> 


# Team Diffusion Repository. GCD Project III 22/23

## About

This repository covers the Anomalous Diffusion Patterns modelling project. This project is built under the scope of the AnDi Challenge 2021. It has been developed by Team 03 from Project III course from UPV Data Science Degree.

The [AnDi Challenge](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/LaBiblia.pdf) consisted of 3 tasks, each of them covering a matter of interest for the study of anomalous diffusion. This project focuses on the third of the proposed challenges, which aimes to develop state-of-the-art methodologies for changepoint detection

The documentation used can be found to and task-specific documentation and references can be found in task specific folders (refer to [Task1](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/Task1), [Task2](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/Task2) and [Task3](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/Task3)).

## Data

Data generation was a key part of the project, the instructions for generating synthetic data for the tasks can be found in the [Data](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/data) folder. There it can be found Python notebooks that can help you to create synthetic data for the AnDi Challenge Sub-Tasks. The same way, trajectory exploration notebooks can be found as well.
You can also find the data we used to train our task 3 [models](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/Task%203/models) into the [model_data](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/data/model_data) folder, including the synthetic trajectories that we have generated and the predictions of the sliding windows.

## Models 

Specifications for the models can be found in the [Lista](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/Lista) folder, containing .h5 files with pre-trained models for AnDi specific tasks. The same way, code to deliver predictions following this project's approach for AnDi Challenge's Task 3 is available as well. 
You can also found our own models for the task 3 in the [models](https://github.com/DiffusionPatternsStockMarket/DiffusionPatterns_Repo/tree/main/Task%203/models) folder.

## Model Pipeline Tester

Inside this folder you will find everything you need to use our exploratory scripts. You will find two scripts, NN_script.ipynb, with which you can use our neural network model and represent the predictions made by it and Shap_script.ipynb that allows us to predict the changepoint of a trajectory using our XGBoost model and calculates the shap values of the prediction in order to see which variables are more decisive in the prediction made. To do your own tests you will simply have to generate a file that contains the trajectory to study and has the name task3.csv, this file can contain more than one trajectory, but in this case we will have to select which trajectory we are interested in studying.

## References

Alessia Gentili and Giorgio Volpe 2021 J. Phys. A: Math. Theor. 54 314003

Carlo Manzo 2021 J. Phys. A: Math. Theor. 54 334002

Dezhong Li et. al 2021 J. Phys A: Math. Theor 54 404003

Aykut Argun et al 2021 J. Phys A: Math Theor 54 294003








