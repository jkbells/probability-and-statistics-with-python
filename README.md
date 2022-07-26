# probability-and-statistics-with-python
Probability deals with predicting the likelihood of future events, while statistics involves the analysis of the frequency of past events. Probability is primarily a theoretical branch of mathematics, which studies the consequences of mathematical definitions.



# First create a virtual environment using conda 
conda create --prefix ./stats-env  
conda activate ./stats-env  


# Fix the ugly full path 
conda config --set env_prompt '({name}) '
conda deactivate 
conda activate ./stats-env  



# Activate it and install jupyter lab and pandas 

conda install jupyterlab pandas matplotlib 

conda install pandas 

conda install bokeh
conda install matplotlib 

# Start the lab 
jupyter lab 
