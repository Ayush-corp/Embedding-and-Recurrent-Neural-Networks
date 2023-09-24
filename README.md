CPSC-585-Project-02-Group 7
GitHub

Open in Colab

Team Members:

Jarrod Leong: 885142281
Jeet Hirakani: 885189175
Arjit Saxena: 885188839
Dhyey Desai: 885451609
Ayush Bhardwaj: 885866178
Janvier Uwase: 885942086
Steps to Run the First Model/Best Model
To run the first model, follow these steps:

Create a folder in your Google Drive named "CPSC585_Project3".

Inside the "CPSC585_Project3" folder, create two more folders titled "data" and "weights".

Upload RateMyProfessor's sample data into the "data" folder.

DataSet and Data PreProcessing
Data Cleanup
The following code performs data cleanup and extracts only the relevant columns in the dataset. It removes rows with missing comments and ratings (only a few rows were removed) and runs a spell check on the words to correct spelling errors found in the comments. The code also extracts the following relevant columns:

student_star
student_difficult
comments
Please note that this data cleanup process may take some time due to the spellchecker being not fast. It was run locally, and the cleaned data was subsequently reuploaded to the drive, which is why there may be no visible output in the notebook.
