<h2>Identifying mental health disorders with Artificial Intelligence using Natural Language Processing & Deep Learning Techniques

Zacharias Siatris <br></h2>

<br><br>
This project includes the use of one NLP model (pre-trained via API) and the development of NLP pre-processing methods along with a DL model to identify potential mental health disorders through text. Please follow the instructions below to experience a successful execution of the end-to-end AI solution.

1. Prior to running the code, make sure you have installed/available the following three things:

   a. Python (3.9+) installed.
   
   b. Anaconda Navigator / Jupyter Notebook installed.
   
   c. Internet connection available.
   
2. Make sure you have the "Datasets" folder in the same folder (path) where the Jupyter Notebook exists. 
3. Pay attention to the initial parameters set at the beginning of the Jupyter Notebook which you may find below: 

   a. load_big_datasets: This boolean variable when set to 'True' will use the csv files that include more than 800K samples.
      <br>**Warning:** Depending the machine you are running the code, the execution time may last between 1-3 hours.
      
   b. use_nlp_validation_model: This boolean variable when set to 'True' will utilize the NLP validation model (Hugging Face) in order to apply sentiment analysis to         the dataset.
      <br>**Warning:** It requires a lot of time due to the use of API calls. In case you selected to load the big datasets (previous boolean variable), make sure you       set this variable to 'False'. Set it to "True" if and only if "load_big_datasets = False".

   c. print_word_cloud_per_disorder: This boolean variable when set to 'True' will print at the last section "Results & Visualizations" a group of words included in         each mental health disorder using Word Cloud.

   d. print_dataset_each_step: This boolean variable when set to 'True' will print the dataframe object at each step during the NLP pre-processing.

   e. number_of_rows_to_print: This number regards to the "print_dataset_each_step" variable and sets the number of rows of the dataframe object to be printed on each       step.

4. Now you are ready to run the Jupyter Notebook. In the first code cell of the notebook all installation and import commands are placed so there is no further need to install manually any other library or package. The first time that you will run the notebook it will take a few minutes to install the packages and libraries.
