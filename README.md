# Project Name

**Author**: Dana Voros and Harrison Cogswell
**Version**: 1.0.0

## Overview
https://git.heroku.com/hc-dv-bookap.git
Full-stack book searching application, using Google Books API, where a user can search for books by title or author, 
and will be shown a search list including titles, authors, cover images, and a short synopsis

## Getting Started
`npm init` with node.js installed, and then `npm i` to install node package dependencies express, ejs, dotenv, and superagent

## Architecture
Uses express to do server heavy-lifting, ejs to embed javascript and partials into 'public/' ejs views, 
uses superagent to read Google's free Book API

## Change Log
#### 02-26-2019 9:37am - Application now has a fully-functional framework, with a stand-in filepath to index page
Number and name of feature: Feature 1, Fast Load-up and frame-work

Estimate of time needed to complete: 30 min

Start time: 9am

Finish time: 9:37

Actual time needed to complete: 37 min

#### 02-26-2019 9:54am - Heroku Deployment fully functional, with no errors
Number and name of feature: Feature 2, Heroku initial deployment

Estimate of time needed to complete: 15 min

Start time: 9:37am

Finish time: 9:54am

Actual time needed to complete: 27 min

#### 02-26-2019 10:21am - Book instances create and render on new view '/searches'
Number and name of feature: Feature 3, Render array of Book instances on 'show.ejs'

Estimate of time needed to complete: 1.5 hr

Start time: 9:54am

Finish time: 10:25am

Actual time needed to complete: 27 min

#### 02-26-2019 10:40am - Book instances create and render on new view '/searches'
Number and name of feature: Feature 4, Create an Error View, in case our app is breaking, or the user sends a bad search request

Estimate of time needed to complete: 1 hr

Start time: 10:43am

Finish time: 11:35am

Actual time needed to complete: 52 min

#### 02-27-2019 12:49pm - Save books to database and Load bookshelf on Pageload
Number and name of feature: Features 5 (and 8), Render User's saved books on site load from sql database, and add ability to save Books from search view into database.

Estimate of time needed to complete: 2 hr

Start time: 9:15am

Finish time: 12:46pm

Actual time needed to complete: 3 hr 31 min

#### 02-27-2019 1:16pm - Create Detail View for each book in the user's bookshelf
Number and name of feature: Features 6, Render User's saved books in an individual detail view when they search for a specific book.
Estimate of time needed to complete: 1 hr

Start time: 12:50am

Finish time: 1:14pm

Actual time needed to complete: 24 mins

## Credits and Collaborations
Powered by: Google Books API
