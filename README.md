# Flask-API endpoints
[![Build Status](https://travis-ci.org/imma254/API-endpoints.svg?branch=master)](https://travis-ci.org/imma254/API-endpoints)


## Overview
Creation of the website's flask API endpoints.

## Description of Task to be completed? 
Setup API and test endpoints that do the following using data structures:
- Get all questions.
- Get a question.
- Post a question.
- Post an answer to a question.

#### *API endpoints overview*
Test | API-endpoint | HTTP-Verbs
------------ | ------- | -----
User can post a question | /api/v1/questions | POST							
User can view all questions | /api/v1/questions | GET
User can view a single question | /api/v1/questions/question_id | GET
User can edit a question	| /api/v1/questions/question_id | PUT

## How should this manually be tested? 
- Navigate to the API-endpoints repository.
- Clone or download the repository
`$ git clone https://github.com/imma254/API-endpoints`
- Install and run virtualenv on your PC
`$ pip install virtualenv`
`$ virtualenv env`
- Activate virtualenv
`$ . env/Scripts/activate`
- Install Flask
`$ pip install Flask`
- Run the app
`$ python app.py`
- Test the app
`$ python test_app.py`

## Any background context you want to provide?
- Data structures
- Flask

## Relevant Pivotal Tracker Stories
 - #159925230
