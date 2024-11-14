# Building `Search Engine` using `Inverted Index`

USE CASE : Job Postings

Dataset : https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset

Project Architecture:
![Car Insurance Comparison  Presentation in Navy Yellow Blue Bold Modern Style-32](https://github.com/user-attachments/assets/a299043d-b0da-4592-9f88-2cabcedb6f13)


### Steps:

1. Dataset Download and Preparation:
  - Download the dataset from Kaggle.
  - Load and clean the data by removing unnecessary columns.
2. Build Inverted Index:
  - Create an inverted index using the job titles for fast search.
  - Tokenize each job title and store the document (row) IDs associated with each term.
3. User Query Input:
  - Prompt the user to enter a search query.
4. Search Process:
  - Tokenize the input query and look up each term in the inverted index.
  - Retrieve matching job listings based on the document IDs.
5. Display Results:
  - Show job details like title, role, company, qualifications, and salary.
  - Repeat the process or exit based on user input.
  -End Program
   Exit if the user types 'exit'.
