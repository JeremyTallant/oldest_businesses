# What and Where are the World's Oldest Businesses
## Description
An important part of business is planning for the future and ensuring that the business survives changing market conditions. Some businesses do this remarkably well and last for hundreds of years. In this project, we'll explore data from BusinessFinancing.co.uk on the world's oldest businesses: when were they founded, and which industries do they belong to?

Like many business problems, the data we'll explore is contained in several different datasets. In order to understand the world's oldest businesses, we will first need to use joining techniques to merge our data. From there, we can use manipulation tools such as grouping and filtering to answer questions about these historic businesses.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib 
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **The oldest business in the world:** Let's load the data and explore it!
2. **How many businesses were founded before 1000?:** Let's join `sorted_businesses` with `countries` so we can look at data by continent.
3. **Which businesses were founded before 1000?:** Let's create a DataFrame called `continent`
4. **Exploring the categories:** For this task, we'll return to `businesses` and `countries` and use our `.merge()` skills to look for missing data.
5. **Counting the categories:** We want to vertically stack `businesses` and the information from `new_businesses.csv` together to create a more complete dataset.
6. **Oldest business by continent:** Which industries do you think are best suited to last over the course of centuries?
7. **Joining everything for further analysis:** Let's find the oldest restaurants in the world.
8. **Counting categories by continent:** Let's make a reference table showing the oldest business in each category of commerce by continent.
9. **Filtering counts by continent and category:**