# Psychological Artificial Intelligence Research (PAIR) Project

<!--This is the first gif. It is sourced from giphy under the search term "psychology".-->
<div id="header" align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYTMwam5wdnhndG54Y2M4NXFqZWRwdWRoNWZmeHFlNHdtMHlpd2JzOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/vmpD7oogmtjGg/giphy.gif" width="700" height="300"/>
</div>

**THIS PROJECT IS TEMPORARILY PAUSED (AS OF JANUARY 2024). WORK IS CURRENTLY EXPECTED TO RESUME IN APRIL 2024.**

## Project Overview

The **PAIR Project** is an ongoing effort to build AI frameworks for identifying psychological epidemics in populations during specific epochs in order to better design public policies and medical diagnostics.

PAIR is an interdisciplinary project, utilizing research and techniques from psychology,
data science, sociology, and ethical philosophy. 

The primary programming language used is Python (currently version 3.11.3). Additional 
languages, including R, SQL, HTML, and CSS, may be used to supplement the Python code 
where advisable. 

All current work (as of December 2023) is being developed by the Project Lead. No 
collaborators are currently being sought (the project is expected to be reopened to 
potential collaborators in January 2024). 

Data collection is expected to begin in January/February 2024 (I am currently working
on a way to administer the questionnaire, obtain the time data, and ensure data
privacy/security; likely to be distributed using Qualtrics). The questionnaire is expected to contain the MACH-IV questions+survey, 
the SD3 questions, the UCLA Loneliness Scale, and a time tracker component (time to answer individual questions + time to 
complete sections). Questions will be presented in English and will be shown in random 
order, with the optional personal information survey always being the final part (education
level, age, gender, native language, religion, sexual orientation, ethnicity, nationality,
marital status, number of children, number of siblings, and university major (if applicable)).

**Last Update: December 23rd, 2023**
<div id="header" align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbXl5cTRia2Q0dnEzYWdrMzFlZDkwN29pdGtrZGJ0dTl3dnVkenF2dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/O3pR48VrAqirjZhOyE/giphy.gif" width="700" height="300">
</div>

## Current Objectives

I am currently exploring approximately 73K responses to the MACH-IV psychological assessment (with an additional optional survey) collected between 2017-2019 ([Data Source](https://www.kaggle.com/datasets/mathurinache/machivallianism-test)). I aim to identify robust and informative clusters in the data and provide supportive (and easily intelligible) visuals to better understand the behaviors/beliefs of those displaying above/below "normal" levels of Machiavellianism.

For now, I am using Jupyter Notebooks to develop and present my work. The first version (which will include significant code and preliminary comments) of this analysis is currently expected to be released in early January 2024. 

I am also finalizing the questionnaire + survey for live data collection. All questions have been collected/written; I am just working on which platform is best for hosting.

## History of the Project

Begun in Spring 2023 by a team of 4 developers led by Tyler Chang, the first released content 
focused on building classification models that predict levels of dark triad traits relative to others 
based on the SD3 (*short dark triad*) questionnaire. The SD3 questionnaire includes questions 
meant to measure a person's level of psychopathy, narcissism, and Machiavellianism, and can be 
administered without the presence of a psychologist (it is **NOT** a diagnostic tool, 
regardless of whether a psychologist is present). The models developed were each trained 
on a subset of the questions associated with two of the three dark triad traits to predict 
a person's average score for questions associated with the third trait. With accuracies 
ranging between approximately 67-78%, the models provided limited insight into the 
connections between each of the dark triad traits. 

Following the initial release, the initial project team was disbanded (due to changing
professional obligations) and further work was temporarily paused. Development resumed
in late Summer 2023 and the project was restructured to focus on loneliness and Machiavellianism. 

## Disclaimers

<div id="header" align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOWZ6bmhudzJmNHc2aWd2b3ByczFlMDZ0bjZzb3RzbTcyMThsemNmYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/26FmPTVxvuGupMAYo/giphy.gif" height="300" width="700">
</div>

- This project's team does not currently include any medical professionals. 
No claims made in this report should be taken as a substitute for a medical
diagnosis.
- The data used in parts 1-3 has not been collected by the PAIR development team. 
As such, the findings of these sections should be taken as frameworks for use with
live data (to be clear, the data used is real data but the PAIR team has not been
able to verify that the advertised collection methods were followed or data integrity standards
were met).
- The project is ongoing and objectives may change as it progresses. If any significant
changes are made, they will be reflected in the project's GitHub repo README and in 
the documentation of this report.





