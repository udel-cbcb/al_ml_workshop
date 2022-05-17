# Practical AI/ML for Computational Biology and Chemistry Workshop

  - [Introduction](#introduction)
  - [Requirements](#requirements)
  - [Sponsors](#sponsors)
  - [License](#license)
  - [Schedule](#schedule)
  - [Logistics](#logistics)

## Introduction
Research is being revolutionized by methods from the field of Artificial Intelligence and Machine Learning (AI/ML). AI is the simulation of human intelligence processes (such as problem-solving, learning, and planning) by machines, while ML, a type of artificial intelligence, gives computers the ability to learn without explicitly being programmed. They have been applied in many areas including drug discovery, protein folding, and identification of variants from genetic data.

This workshop will provide you with

- a conceptual understanding of various AI/ML approaches,
- examples of practical applications of AI/ML in computational biology and chemistry,
- hands-on exercises with emphasis on the importance of data preparation and readiness for AI/ML.

Through introductory lectures, you will be exposed to the basic concepts behind AI/ML approaches to better understand the practical applications of these data science tools, including what types of data can be used for a specific approach, and what types of outcomes can be expected. The illustrative practical applications will help you understand how these tools can be used in your research project. You will also learn about the importance of preparing the data according to the FAIR principles, namely, [Findability, Accessibility, Interoperability, and Reusability](https://pubmed.ncbi.nlm.nih.gov/26978244/). This will be addressed by providing you with first-hand experience on the issues arising when data that is not well-prepared, and covering various data formats, processing and wrangling techniques to get the data into a form where it can be utilized by Machine Learning algorithms. You will learn different visualization techniques to better understand the data at hand.

## Requirements

Bring your computer. Live demos and hands-on exercises will involve coding using [Google Colaboratory](https://colab.research.google.com/?utm_source=scs-index) notebooks. Basic Python programming is recommended but not required. The skills covered in the Data Carpentry Bootcamp that will be held in June 1-3 2022 meet this requirement.

## Sponsors

Hosted by the UD Chemistry-Biology Interface Program and Center for Bioinformatics and Computational Biology. This workshop is offered free of charge with support from the NIH National Institute for General Medical Sciences (T32GM133395-03S1).

## License

(c) 2022 by Center for Bioinformatics and Computational Biology, University of Delaware

The Practical AI/ML for Computational Biology and Chemistry Workshop materials are licensed under a
Creative Commons Attribution 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by/4.0/>.

## Schedule

Day 1 (June 13, 1:00pm – 5:00pm)
- [Introduction to Workshop](https://docs.google.com/presentation/d/1is6-cpgnrYn5vHzUTF9iovDPMOmmnf6hsPeJi1AeLfI/edit?usp=sharing)
- Lecture
  - [Introduction to AI/ML](https://docs.google.com/presentation/d/1QqiLijMrdQ5bwjayNeFz2dCx1v8Te4PVy5brscaL-aY/edit?usp=sharing)
  - [AI/ML Applications in Biology and Chemistry](https://docs.google.com/presentation/d/1z9OktpolGPzeWjN_mz4h61iV22i9Zvf0qTQp5MW7YA4/edit?usp=sharing)
- Live Demo
  - [Introduction to Google Colab](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Live_Demos/Day_1_Live_Demo_1_Introduction_to_Google_Colab.ipynb)
  - [Introduction to NumPy](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Live_Demos/Day_1_Live_Demo_2_Introduction_to_NumPy.ipynb)
  - [Introduction to Pandas](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Live_Demos/Day_1_Live_Demo_3_Introduction_to_Pandas.ipynb)
  - [Predict Gene Family using DNA Sequence](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Live_Demos/Day_1_Live_Demo_4_Predict_Gene_Family_Using_DNA_Sequence.ipynb)
- Exercise
  - [NumPy Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_NumPy.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_NumPy_Solution.ipynb))
  - [Pandas Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_Pandas.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_1/Exercises/Day_1_Exercise_Pandas_Solution.ipynb))

Day 2 (June 14, 1:00pm – 5:00pm)
- Lecture
  - [Data Collection and Data Preparation](https://docs.google.com/presentation/d/1iuT2jQpTqY6E8CI2GRbwFALLCTPukQLlCkB7d4xj8jA/edit?usp=sharing)
  - [Data Readiness for AI/ML Checklist](https://docs.google.com/presentation/d/1AGXmqoWbo1JHNTcgVqWXVYEbTlPg1Rid7J8mbrm58Kk/edit?usp=sharing)
- Live Demo
  - [Basic Data Cleaning](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_1_Basic_Data_Cleaning.ipynb)
  - [Marking and Removal of Missing Data](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_2_Mark_and_Remove_Missing_Data.ipynb)
  - [Outlier Identification and Removal](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_3_Outlier_Identification_and_Removal.ipynb)
  - [Missing Data Imputation](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_4_Missing_Data_Imputation.ipynb)
- Exercise
  - [Data Wrangling Exericse](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Exercises/Day_2_Exercise_Data_Wrangling.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_2/Exercises/Day_2_Exercise_Data_Wrangling_Solution.ipynb))

Day 3 (June 15, 1:00pm – 5:00pm)
- Lecture
  - [Feature Engineering, Scaling and Selection](https://docs.google.com/presentation/d/1boVdrT2YqcIj0MzOQiObSp8MBqGcgrtaYoJvve0C5IU/edit?usp=sharing)
- Live Demo
  - Feature Engineering
    - [Encode Categorical Data](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_1_Feature_Engineering_Encode_Categorical_Data.ipynb)
    - [Change Numerical Data Distribution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_2_Feature_Engineering_Change_Numerical_Data_Distributions.ipynb)
    - [Derive New Input Variables](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_3_Feature_Engineering_Derive_New_Input_Variables.ipynb)
  - Feature Scaling
    - [Numerical Data](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_LIve_Demo_4_Feature_Scaling_Numerical_Data.ipynb)
    - [Data With Outliers](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_5_Feature_Scaling_Data_with_Outliers.ipynb)
  - Feature Selection
    - [Numerical Input Features](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_6_Feature_Selection_Categorical_Input_Features.ipynb)
    - [Categorical Input Features](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_LIve_Demo_7_Feature_Selection_Numerical_Input_Features.ipynb)
    - [Recursive Feature Elimination](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_8_Feature_Selection_Recursive_Feature_Elimination.ipynb)
- Exercise
  - [Feature Engineering Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Engineering.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Engineering_Solution.ipynb))
  - [Feature Scaling Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Scaling.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Scaling_Solution.ipynb))
  - [Feature Selection Exercise](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exericse_Feature_Selection.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exericse_Feature_Selection_Solution.ipynb))

Day 4 (June 16, 1:00pm – 5:00pm)
- Lecture 
  - [ML Models and Model Evaluation](https://docs.google.com/presentation/d/1nk-CBd-6o5J-S8QTVrvXOtalnjUoSRgqgHSNaFEAq4M/edit?usp=sharing)
  - [Model Tuning, Interpretation and Deployment](https://docs.google.com/presentation/d/1PRIDgPmcQuxxHIs3V0zslJXymmEwQSqdJgwgJ0t3yWY/edit?usp=sharing)
- Live Demo
  - [Predict Drug Activity for Androgen Receptor](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_1_Predict_Drug_Activity_for_Androgen_Receptor.ipynb)
  - [Model Building and Evaluation](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_2_Model_Building_and_Evaluation.ipynb)
  - [Model Tuning, Interpretation, Deployment](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_3_Model_Tunning_Interpretation_Deployment.ipynb)
- Exercise
  - [Exploratory Analysis of Wine Types and Quality Data](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_1_Exploratory_Analysis_of_Wine_Types_and_Quality_Data.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_1_Exploratory_Analysis_of_Wine_Types_and_Quality_Data_Solution.ipynb))
  - [Predict Wine types using physicochemical features](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_2_Predicting_Wine_Types.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_2_Predicting_Wine_Types_Solution.ipynb))
  - [Predict Wine quality using physicochemical features](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_3_Predicting_Wine_Quality.ipynb) ([Solution](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_3_Predicting_Wine_Quality_Solution.ipynb))

Day 5 (June 17, 1:00pm – 5:00pm)
- Lecture 
  - [Introduction to Deep Learning](https://docs.google.com/presentation/d/1_GNZw6aiE8m9YMsF18NokoIJH6K2tWLWN70S4C98kxM/edit?usp=sharing)
- Live Demo
  - [Pfam protein sequence classification using Tensorflow and Keras](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_5/Live_Demos/Day_5_Live_Demo_1_Pfam_Protein_Sequence_Classification_with_Tensorflow_Keras.ipynb)
  - [Predicting molecule solubility using DeepChem](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_5/Live_Demos/Day_5_Live_Demo_2_Predicting_the_Solubility_of_Small_Molecules.ipynb)
- Exercise
  - [Predict Wine types using Deep Learning](https://colab.research.google.com/github/udel-cbcb/al_ml_workshop/blob/main/Day_5/Exercises/Day_5_Exercise_1_Predicting_Wine_Types_Deep_Learing.ipynb) ([Solution](Day_5/Exercises/Day_5_Exercise_1_Predicting_Wine_Types_Deep_Learing_Solution.ipynb))
  - [Protein 3D structure prediction using AlphaFold2](https://colab.research.google.com/github/deepmind/alphafold/blob/main/notebooks/AlphaFold.ipynb)
- [Course Summary](https://docs.google.com/presentation/d/1lqlWVt4-bZHavCK4rfEKl0In6iENZl6tn569CtI0nlA/edit?usp=sharing)

## Logistics

A reminder that the workshop is in person in the auditorium (BPI 140) of the Ammon Pinizzotto Biopharmaceutical Innovation Center which is located on UD STAR Campus at 590 Avenue 1743.  If you are not a resident of BPI, you do NOT need to sign in at the front desk.

Parking/Transportation:
UD permit parking is available. Gray Permit: Lot 207 (some spaces) and on street parking on Discovery Blvd and Avenue 1743; Red Permit: Lot 209.  Those without UD parking permits may use on street parking and pay at kiosks or using the PassPort app.  Parking map available at: https://sites.udel.edu/parking/.  UD Bus: North/South College Route use the Star Tower stop.

COVID Considerations:
All participants must complete the UD COVID Check (https://covidcheck.udel.edu) each day before arriving on UD’s campus.  While the University of Delaware no longer requires masks to be worn for non-classroom events, all participants are encouraged to bring a mask for use whenever social distancing cannot be maintained.  

Please Be Kind:
The organizers of the workshop and the University of Delaware are dedicated to fostering a safe and inclusive learning environment that does not discriminate against any person on the basis of race, color, national origin, sex, gender identity or expression, sexual orientation, disability, religion, age, or any other characteristic.  All participants are asked to also please abide by these values in your interactions with others throughout this workshop.