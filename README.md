### Table of Contents
1. [Running the Project](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Libraries Used](#libraries)
5. [Results](#results)
6. [Acknowledgements](#licensing)

## Running the Project<a name="installation"></a>
1. Clone or download this repository.
2. Ensure Python version 3.* is installed.
3. Ensure the necessary libraries are installed by running `pip install -r requirements.txt`.
4. Download the 2025 [Stack Overflow Annual Developer Survey results](https://survey.stackoverflow.co/). You will need both the survey results and the schema. Put them im a folder named "Data." The Data folder should be in the same directory as the Jupyter Notebook.
5. Run the code in stack_overflow_data_project.ipynb.


## Project Motivation<a name="motivation"></a>

I wanted to investigate the following 3 questions:
1. Is AI a threat to Data Science or Data Analysis jobs?
2. What factors are correlated with workers' view of the perceived or real threat?
3. What skills will be most necessary for data scientists and data analysts in the future?


## File Descriptions <a name="files"></a>
- `stack_overflow_data_project.ipynb`: Contains all code for the analysis.
- `requirements.txt`: Lists all Python dependencies.
  
## Libraries Used <a name="libraries"></a>

This project uses the libraries listed below, which are also listed in requirements.txt for convenience of installation.
- numpy
- pandas
- seaborn
- matplotlib
- wordcloud
- scikit-learn

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@sky_adams/will-your-job-be-replaced-by-ai-d5e076c75c72).

## Acknowledgements<a name="licensing"></a>

The analysis was performed using the results of the 2025 [Stack Overflow Annual Developer Survey](https://survey.stackoverflow.co/).
