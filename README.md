# personalised-cancer-diagnosis
 lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.

But this is only partially happening due to the huge amount of manual work still required. Memorial Sloan Kettering Cancer Center (MSKCC) launched this competition, accepted by the NIPS 2017 Competition Track,  because we need your help to take personalized medicine to its full potential.



Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 

Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.

We need your help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.


Kaggle is excited to partner with research groups to push forward the frontier of machine learning. Research competitions make use of Kaggle's platform and experience, but are largely organized by the research group's data science team. Any questions or concerns regarding the competition data, quality, or topic will be addressed by them.

### Business Problem
The workflow is as follows:
A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze.
The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest.
Finally, this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them into any one of the 9 different classes. Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated by a machine learning model.
Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated by a machine learning model.
### Problem Statement
Classify the given genetic variations/mutations based on evidence from text-based clinical literature. In this problem, we need to find the mutation-type given the gene, variation and some text data from published research.

## Source of Data
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data Data: Memorial Sloan Kettering Cancer Center (MSKCC)

## Real-world/Business objectives and constraints.
No low-latency requirement. Interpretability is important. Errors can be very costly. Probability of a data-point belonging to each class is needed.

## Getting Started
Start by downloading the project and run " Personalized-Cancer-Diagnosis.ipynb" file in ipython-notebook.

## Running the tests
This project can be tested in real-world with similar data. The shape of the test data should be same as of training data. In order to test the project in real world, perform following steps in order:
Run the project just before "Base Line Models"
Once the project ran completely, add your testing data to the project at "Reading Data" section.
Perform data pre-processing and data cleaning.
Out of total 8 models choose any one model as per your choice and run that model.
Using best hyper-parameter of that model, run that model on your test data.
Note down the results.
For more results you can try with another model and follow the same procedure.
## Built With
• ipython-notebook - Python Text Editor

• sklearn - Machine learning library

• seaborn, matplotlib.pyplot, - Visualization libraries

• numpy, scipy- number python library

• pandas - data handling library

• mlxtend - used for stacking the models

## Authors
• yashwanthreddysomala

## Acknowledgments
• Applied AI Course
