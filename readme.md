# ECE444 Fall 2021 Lab3

Omar ElZaria,
this repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1
<img width="713" alt="Screen Shot 2021-09-29 at 2 09 23 PM" src="https://user-images.githubusercontent.com/46201075/135328935-be8061e1-899b-4e12-93d0-a7a994726a87.png">

## Activity 2
![Screen Shot 2021-09-29 at 2 39 46 PM](https://user-images.githubusercontent.com/46201075/135329173-8b047b90-0b04-4839-8e63-1e42eaa348fe.png)


## Activity 3
![Screen Shot 2021-09-29 at 2 34 22 PM](https://user-images.githubusercontent.com/46201075/135329222-f732000e-8b1b-4c9d-a8ef-0555ed56787e.png)

## Activity 4
<img width="1438" alt="Screen Shot 2021-09-29 at 2 35 37 PM" src="https://user-images.githubusercontent.com/46201075/135329271-1c8f77fd-8187-41fd-bb20-633a2a0f53c3.png">

![Screen Shot 2021-09-29 at 3 10 53 PM](https://user-images.githubusercontent.com/46201075/135333377-2272e215-5f75-4507-94d6-f08866a94db3.png)


## Activity 5

One Functional Requirement I would like to improve are the filters. I would add a filter that specifies the term (Summer, Winter, Fall) in order for the student to narrow down the course searches to the ones that are offered in the term that they are currently planning for. I would also add a filter for minors and certificates for students who are pursuing either a minor or certificates so that they can filter for all the courses related to their minor/certficate and take those courses to satisfy the requirements. One non-functional requirement I would like to improve is convenience.  I would want the application to have a blank canvas that the user would fill out with courses they would like to take in one semester. On the left hand side of the canvas is all the filters and a list of all the filtered courses below it. When the user clicks on a course a pop up will come up with all information related to that course all in one place and if the user finds the course they want they can drag the course and place it on the blank canvas. An auto save feature will also be added to make it more convenient for the user so they don't have to continously save their progress.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
