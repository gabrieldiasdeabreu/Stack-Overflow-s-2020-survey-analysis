# Stack-Overflow-s-2020-survey-analysis

Choose a main programming language is a great step in one's career, this analysis is an activity to udacity's first project [Data Science NanoDegree Udacity](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

#### -- Project Status: [Avaliation]

## Project Description

This notebook aims to answer questions about choices of main programming language and their impact on the developers. The Data is provided by [StackOverflow Annual Developer Survey](https://insights.stackoverflow.com/survey).

See the [Medium post](https://gabrieldiasdeabreu.medium.com/dont-choose-your-main-programming-language-before-reading-this-5b416c93b9ac).

The main questions used to investigate are the following:

- Programming Language impacts on the Job Satisfaction?;
- Which languages pay the biggest salaries and have more developers?
- How much are developers working with some language engaged in online communities?;

### Summary

We saw Julia is the highest very satisfied rated language, but has neither as much median salary as Perl and Scala nor bigger community as Java and C, on the other hand Python and Bash have a balance among all these aspects.

### Methods Used

- Inferential Statistics
- Data Visualization

### Library

- Python
- Seaborn, Matplotlib
- Pandas, Numpy

## Getting started

Clone this repository

```shell
git clone https://github.com/gabrieldiasdeabreu/Stack-Overflow-s-2020-survey-analysis
```

- Check pyenv installation:

```shell
$ pyenv --version
```

Set to current python to be the same as 3.7.8

````shell
$ pyenv init # follow the instructions of this command
$ pyenv install 3.7.8
$ pyenv shell 3.7.8

Create a virtualenv

```shell
python3 -m venv venv
````

Activate the virtualenv

```shell
$ source venv/bin/activate
```

Install the requirements in your virtualenv:

```shell
pip install update pip
pip install -r requirements.txt
```

### Project tree

    .
    ├── README_2020.txt - stack overflow readme
    ├── README.md - project readme
    ├── requirements.txt - requirements for pip
    ├── so_survey_2020.pdf - an example of the survey analysed
    ├── StackOverflowAnalisys.ipynb - jupyter notebook with CRISP-DM proccess
    ├── survey_results_public.csv - survey dataset
    └── survey_results_schema.csv - dataset descriptions

## Acknowledgment

Stack Overflow for providing [Stack Overflow 2020 Developer Survey](https://insights.stackoverflow.com/survey)
[Udacity Data Science Nano Degree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

## Contact

My [LinkedIn Profile](linkedin.com/in/gabriel-dias-de-abreu-b2063a199)
