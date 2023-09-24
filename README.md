# CPSC-585-Project-02-Group 7

![GitHub](https://img.shields.io/github/license/yourusername/CPSC-585-Project-02-Group7)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hm1huK8ere_Cb1wkObYjFDrDqFa2EJNO)

**Team Members:**
- Jarrod Leong
- Jeet Hirakani
- Arjit Saxena
- Dhyey Desai
- Ayush Bhardwaj
- Janvier Uwase

## Steps to Run the First Model/Best Model

To run the first model, follow these steps:

1. Create a folder in your Google Drive named "**CPSC585_Project3**".

2. Inside the "**CPSC585_Project3**" folder, create two more folders titled "**data**" and "**weights**".

3. Upload RateMyProfessor's sample data into the "**data**" folder.

## DataSet and Data PreProcessing

### Data Cleanup

The following code performs data cleanup and extracts only the relevant columns in the dataset. It removes rows with missing comments and ratings (only a few rows were removed) and runs a spell check on the words to correct spelling errors found in the comments. The code also extracts the following relevant columns:

1. student_star
2. student_difficult
3. comments

Please note that this data cleanup process may take some time due to the spellchecker being not fast. It was run locally, and the cleaned data was subsequently reuploaded to the drive, which is why there may be no visible output in the notebook.
