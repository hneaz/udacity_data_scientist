# Game of Thrones - Battle Prediction

Game of Thrones is a popular fantasy TV show based on a series of books written by George RR Martin. This repository showcases the analysis and predictions of the battles in the book series. 

### Table of Contents

1. [Project Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation<a name="motivation"></a>

This is a Udacity Data Scientist nanodegree project for **Introduction to Data Science** section. I chose the [Game of Thrones - Explore death and battles from this fantasy world](https://www.kaggle.com/mylesoneill/game-of-thrones) dataset as I am a huge fan of the show.

I came up with these questions to answer:

1) Which house wins the most battle in any situation?  
2) What is the expected size of the defending army given the size of the attacking army?  
3) What factors contribute to a battle victory?  

## Installation <a name="installation"></a>

### Virtual environment
Add the following to your .bash_profile to source virtualenv correctly:

```
export WORKON_HOME=$HOME/.virtualenvs
export VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python3
export VIRTUALENVWRAPPER_VIRTUALENV=/usr/local/bin/virtualenv
source /usr/local/bin/virtualenvwrapper.sh
```
Create a virtual environment:
```
mkvirtualenv kingofthenorth --no-site-packages
workon kingofthenorth
add2virtualenv .
```

### Python packages:
```
pip3 install -r requirements.txt
```

### Jupyter notebook (if needed):
```
python3 -m ipykernel install --user --name kingofthenorth --display-name "kingofthenorth"
```

## File Descriptions <a name="files"></a>
There is one notebook called `got_battle.ipynb` that runs the exploratory data analysis as well as the modeling sections. There is another script called `visuals.py` that is used to plot important features of a model. Lastly, there is an HTML file called `got_battles_data_profile.html` with the notebook outputs.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here]().


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to: 
* Chris Albon's "The War of the Five Kings" Dataset, which can be found here: https://github.com/chrisalbon/war_of_the_five_kings_dataset . It's a great collection of all of the battles in the series. 

* As well as Myles O'Neil Kaggle data here: https://www.kaggle.com/mylesoneill/game-of-thrones)  

Feel free to use my notebook and explore my analysis!

## Authors

**Hasib Neaz** - *Initial work* - [hneaz](https://github.com/hneaz)
