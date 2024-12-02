# WMNLP, Final Project: Article Summarizer
Melissa Stone Rogers, December 1, 2024

## Introduction
Professional project using Jupyter Lab, requests, JSON, and basic NLP with spaCy. This project was created via a template of a repository provided by Northwest Missouri State University's School of Computer Science and Information Systems, [article-summarizer](https://github.com/wmnlp-materials/article-summarizer). 
Commands were used on a Mac machine running zsh.  

### Final Project
Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

### Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt


## How to Install and Run the Project
Create project repository in Github and clone to your machine.
```zsh
git clone project.url
```
Create requirements.txt in the root project folder. 
```zsh
touch requirements.txt
```
Add the following to your requirements.txt
- beautifulsoup4
- html5lib
- requests
- spacy
- spacytextblob
- matplotlib

Verify Python version of Python 3
```zsh
python3 --version
```

Activate virtual environment. 
```zsh
python3 -m venv venv
source venv/bin/activate
```

Install required packages and dependencies.
```zsh
pip install -r requirements.txt
```

Freeze Dependencies 
```zsh
python3 -m pip freeze > requirements.txt
```

## Add .gitignore File
Add .gitignore file to the root project folder if not already completed within repository creation in GitHub.
```zsh
touch .gitignore
```
Add the following to your .gitignore file: 
- .venv/
- .vscode/
- .ipynb_checkpoints/

## Initial Project Save
```zsh
git add .
git commit -m "initial"                         
git push origin main
```
### Start and Complete Project 
Follow instructions within the requests-json-nlp notebook file. Push updates to your GitHub periodically.  

## Complete Your Project
Save your project and push back to your repository. 
```zsh
git add .
git commit -m "final"                         
git push origin master
```
