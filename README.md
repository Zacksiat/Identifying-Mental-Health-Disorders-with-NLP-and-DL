# Idenfitying-Mental-Health-Disorders-with-NLP-and-DL
This project includes the use of one NLP model and the development of two AI models (NLP &amp; DL) to identify potential mental health disorders through text (e.g. social media posts, etc..)

1. Make sure you have the "Datasets" folder in the same folder where the Jupyter Notebook exists
2. Pay attention to the initial parameters set at the beginning of the Jupyter Notebook.

   a. load_big_datasets: This boolean variable when set to 'True' will use the csv files that include more than 800K samples.
      **Warning:** Depending the machine you are executing this notebook it may take from 1-3 hours.


  b. use_nlp_validation_model: This boolean variable when set to 'True' will utilize the NLP validation model (Hugging Face) in order to apply 
                               sentiment analysis to the dataset.
      **Warning:** It requires a lot of time due to the use of API calls. In case you selected to load the big datasets, make sure you set this variable to 'False' .


  c. print_word_cloud_per_disorder: This boolean variable when set to 'True' will print at the last section "Results & Visualizations" a group of words 
                                    included in each mental health disorder using Word Cloud.

  d. print_dataset_each_step: This boolean variable when set to 'True' will print the dataframe object at each step during the NLP development.

  e. number_of_rows_to_print: This number regards to the "print_dataset_each_step" variable and sets the number of rows of the dataframe object to 
                              be printed on each step.
