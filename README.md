# ACT-coursework-2-project
Repository containing files relevant to my coursework 2 project; project completed in python with a standard coding method and a neural-network method.

This project is using the dataset NuclearFusion_data, created by Adebusayo Adewunmi on Kaggle. 
The goal of the project is to create two methods for grouping fusion results into four categories: Complete Success, Partial Success, Partial Failure, and Complete Failure. 
Main idea: Make a scoring system from the parameters given by the dataset, with each contributing different amounts to the overall score. 

Download for dataset:
import kagglehub

# Download latest version
path = kagglehub.dataset_download("adebusayoadewunmi/nuclearfusion-data")

print("Path to dataset files:", path)
