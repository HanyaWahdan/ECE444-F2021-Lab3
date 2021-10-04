# CARTE Education Pathways

Hanya Wahdan

This repo is a clone of https://github.com/nelaturuk/education_pathways

Feedback for Activity 5: After experimenting with Carte for a bit, one functional requirement I would like to change is improving how the search is done. The search  is very basically done through drop-down menus which can be very exhaustive if you're looking for a particular course. Also, in addition, in order to specify the term, you have to completely write "fall" or "winter" vs. "F" or "S" which might be more common for people so adds to the hassle. As for non-functional requirements, I think the user interface and the user experience requries a lot of improvement as I think it's not very usuable or convenient for the student to use. 

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
