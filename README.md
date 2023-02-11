# Marvel-or-DC Repository
### About
This repository is for a mini-project for the course SC1015 (Introduction to Data Science & Artificial Intelligence). The debate between Marvel or DC and which is better, prompted some thoughts within us. Being big superheroe fans ourselves, we set out to explore more about the data taken from the [Superheroes NLP Dataset](https://www.kaggle.com/datasets/jonathanbesomi/superheroes-nlp-dataset?datasetId=633089&sortBy=voteCount).

![image](https://user-images.githubusercontent.com/104261859/164895966-ef953792-4fb5-40e3-b26a-e51b1b754d6b.png)

### Problem Definition
To predict the universe of a hero, whether they are from Marvel or DC.

### Models Used
- Decision Tree
- Natural Language Processing (NLP)

### Libraries Used
- Numpy
- Pandas
- Seaborn
- Matplotlib.pyplot
- Wordcloud
- Statistics
- Scipy
- Statsmodel
- Sklearn

### Algorithms Used
- DecisionTreeClassifier
- CountVectorizer
- LinearSVC
- CalibratedClassifierCV


### Key takeaways
- You can take advantage of the different writing styles in each hero's description to predict whether they are from Marvel or DC 
- NLP has a much higher classification accuracy than a decision tree with depth 4
- NLP also has a significantly lower false positive rate of 10% than compared to decision tree's 44%
- It is possible to predict the universe of a hero only with numerical statistics of that hero but with weak probability of prediction

### Valueable Learning Experiences
- Improving the credibility of our analysis by employing point estimation on the classification accuracy
- Finding the most optimal depth of a decision tree to prevent underfitting or overfitting
- Learning how to apply and utilize NLP which was not taught in labs was an incredible journey
- Obtaining outstanding results from a simplified NLP model only inspired us further to try out more advanced NLP model designs in the future!

### Jupyter Notebook - SC1015_Mini_Project.ipynb
- The code in this notebook covers the entire codebase for our project, from Data Preparation and Cleaning, Exploratory Analysis, the Machine Learning Models implemented and some improvements, as well as the meaningful findings throughout our project.
- It also contains statistical evaluations and analyses of the predictions computed by the models we used.

### Folders
##### SC6_Team10
- Our presentation slides provides a summary of our journey of this project. It touches upon the reasons how we came up with our problem definition as well as how we tackle the problem and finalizing our findings from it.
##### Dataset Folder
- This contains the dataset, ‘superheroes_nlp_dataset.csv’ file, which contains an abundance of statistical information with regard to every single Superhero ever created in the comics.

### Contributions
- Clement Tan - Exploratory Data Analysis, Video, Slides & Presentation
- Darren Ng - Data preparation, Data cleaning, Decision tree, Slides
- Denzyl Peh - Natural Language Processing, Point Estimation, Optimal Depth

### References
- https://www.kaggle.com/datasets/jonathanbesomi/superheroes-nlp-dataset?datasetId=633089&sortBy=voteCount
- https://www.flaticon.com
- https://www.kaggle.com/code/raislervoigt/marvel-or-dc-creators#Some-tests
