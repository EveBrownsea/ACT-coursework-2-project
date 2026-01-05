# ACT coursework 2 project
Repository containing files relevant to my coursework 2 project; project completed in python with a traditional machine-learning method and a neural-network method.

This project is using the dataset NuclearFusion_data, created by Adebusayo Adewunmi on Kaggle. 
The goal of the project is to evaluate the effectiveness of classifier models in predicting ignition for a Nuclear Fusion experiment, i.e. whether a fusion experiment will become self sustaining. In performing this evaluation, I will be answering three overarching questions:

- Q1: Pick a traditional - non neural network approach to your problem. Why did you pick this approach and how well does a traditional approach do?
- Q2: Repeat the answer with a Neural Network approach - compare the two approaches.
- Q3: How does choice of activation function affect the performance of a neural network?

## Dataset: NuclearFusion_data
This dataset is a set of 10000 simulated fusion experiments, utilising three different Magnetic Field Configurations and three different Target Compositions. It was uploaded by Adebusayo Adewunmi and was last updated three years ago (as of 02/01/2026).

The dataset was obtained on Kaggle and can be found [here](https://www.kaggle.com/datasets/adebusayoadewunmi/nuclearfusion-data/data/code/code).

Below is a table listing the description of each column.

| Column name | Description |
|-------------|------------------------------------------------------------------------------------------|
| Unnamed: 0  | Indexing column|
| Magnetic Field Fluctuations (T) | Measurement of maximum fluctuation in the magnetic confinement field |
| Leakage (% of leakage) | Percentage of plasma loss during an experiment |
| Instabilities (% of instabilities) | Percentage of plasma instabilities detected during an experiment |
| Magnetic Field Strength (T) | Strength of the magnetic confinement field in Tesla |
| Magnetic Field Configuration | Type of reactor used |
| Injection Energy (MJ) | Total energy of the injection beam for an experiment |
| Beam Symmetry (%) | Percentage of symmetry in the injection beam |
| Target Density (m^-3) | Density of the target substance |
| Target Composition | Substance used as the 'fuel' for the fusion reaction |
| Fuel Density (m^-3) | Density of the fuel (not including what it's contained in) |
| Temperature (K) | Average temperature of the fusion reaction |
| Confinement time (seconds) | How long the fusion reaction was ongoing |
| Fuel Purity (%) | Percentage of the target composed of the listed target composition |
| Energy Input (MJ) | Total energy fed into the fusion reaction |
| Power Output (MW) | Total power output of the fusion reaction |
| Neutron Yield (Neutrons/second) | Number of neutrons produced by the reaction each second |
| Ignition | Whether or not the reaction became self sustaining (0 for no, 1 for yes) |



## Approaches 
As previously mentioned, this project involved creating a traditional machine-learning approach and a neural net approach to answering the question posed earlier. Listed below are breakdowns of each approach:

- Traditional ML: I used a Decision Tree Classifier for this task as I felt that it was best for getting to the root of the question; whilst a random forest would surely produce better results, the DTC demonstrates the benefits and drawbacks of traditional classification methods in predicting fusion ignition.
- Neural Net: I chose to use a Multi Layer Perceptron Classifier for my neural net work, as it's generally the easiest-to-use classifier that I could find and works with all the scikit-learn evaluation functions, which was very helpful in assessing the accuracy of the model.

## Structure
In the Py folder, there are three subfolders - one for each question. These subfolders each contain an ipynb notebook, which contain all the code and documentation answering the question denoted by the subfolder. The notebooks already contain code to import and read in the data; the data is also linked above under the dataset subheading.


## Dependencies
The following are libraries required to run all the notebooks in this repository. To install them, use "!pip install [library name]"

- Scikit-learn | version 1.6.1
- Matplot lib | matplot: version 0.1.9, lib: version 4.0.0
- Pandas | version 1.5.1
- Seaborn | version 0.13.2
- Numpy | version 1.23.4
- Scipy | version 1.9.3


## Acknowledgements
I would like to give thanks to the following websites and persons/groups who have provided help with understanding and refining my work or for being a consistent source of support throughout.

- [geeks for geeks](https://www.geeksforgeeks.org/) for providing essential help in actually learning the content.
- [The scikit learn documentation team](https://scikit-learn.org/stable/index.html) for being consistent guidance on using the Scikit machine learning functions.
- Github user Spearmintage for providing guidance on how to refine my model in Q1.
- My wonderful girlfriends for making sure I don't give up.
