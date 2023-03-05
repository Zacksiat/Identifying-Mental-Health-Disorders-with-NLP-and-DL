<h2>Identifying mental health disorders with Artificial Intelligence using Natural Language Processing & Deep Learning Techniques


MSc in Artificial Intelligence <br>
The University of Bath <br>2022 - 2023</h2>

<br><br>
This project includes the use of one NLP model and the development of two AI models (NLP &amp; DL) to identify potential mental health disorders through text.
Please follow the instructions below to experience a successful execution of the end-to-end AI solution.

1. Prior to running the code, make sure you have installed/available the following three things:

   a. Python (3.9+) installed.
   
   b. Anaconda Navigator / Jupyter Notebook installed.
   
   c. Internet connection available.
   
3. Make sure you have the "Datasets" folder in the same folder where the Jupyter Notebook exists
4. Pay attention to the initial parameters set at the beginning of the Jupyter Notebook.

   a. load_big_datasets: This boolean variable when set to 'True' will use the csv files that include more than 800K samples.
      <br>**Warning:** Depending the machine you are executing this notebook it may take from 1-3 hours.


   b. use_nlp_validation_model: This boolean variable when set to 'True' will utilize the NLP validation model (Hugging Face) in order to apply 
                               sentiment analysis to the dataset.
      <br>**Warning:** It requires a lot of time due to the use of API calls. In case you selected to load the big datasets, make sure you set this variable to 'False' .


   c. print_word_cloud_per_disorder: This boolean variable when set to 'True' will print at the last section "Results & Visualizations" a group of words 
                                    included in each mental health disorder using Word Cloud.

   d. print_dataset_each_step: This boolean variable when set to 'True' will print the dataframe object at each step during the NLP development.

   e. number_of_rows_to_print: This number regards to the "print_dataset_each_step" variable and sets the number of rows of the dataframe object to 
                              be printed on each step.
