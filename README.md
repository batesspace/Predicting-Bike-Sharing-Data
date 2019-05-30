# Predicting-Bike-Sharing-Data

The predicting bike sharing data project by Udacity inc. takes in bike sharing data and an basic neural network python class, design by me, and outputs bike sharing data analytics. This project repo is for educational purpose and should be used as a tool, not for copying. If viewing or using this repo, please follow the Udacity Honor Code and Community Code of Conduct: https://www.udacity.com/legal/community-guidelines

This neural network is used to predict bike usage and city events corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in http://capitalbikeshare.com/system-data. 

All data analytics can be previewed at Your_first_neural_network.html which is an output of the jupyter notebook Your_first_neural_network.ipynb. 




---

# Run (dependencies are required to run)

To run turn on the `predicting-bike-sharing-data` environment as defined in dependenceies 


```
git clone https://github.com/jujbates/Predicting-Bike-Sharing-Data.git
cd Predicting-Bike-Sharing-Data
jupyter notebook

```

You can open the file `Your_first_neural_network.ipynb` in the browser with the jupyter notebook, and run all cells. This will give you the same output find in the `Your_first_neural_network.html` file. But if you could to walk there the `Your_first_neural_network.ipynb` file and run it cell by cell these are the step that you would be taking. 
0. import libraries
1. Load and prepare the data
2. Checking out the data
    - Dummy variables
    - Scaling target variables
    - Splitting the data into training, testing, and validation sets
3. Time to build the network (The Neural Network I design is found in my_answer.py in a class called NeuralNetwork)
4. Unit tests
5. Training the network
    - Choose the number of iterations
    - Choose the learning rate
    - Choose the number of hidden nodes
6. Check out your predictions
7. Thinking about your results(this question will not be evaluated in the rubric).
    - How well does the model predict the data? 
    - Where does it fail? 
    - Why does it fail where it does?
