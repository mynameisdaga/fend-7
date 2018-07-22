# MyReads Project no. 7
## MyReads project for FEND Udacity Scholarship Course

Starter Code:
> https://github.com/udacity/reactnd-project-myreads-starter
This is the starter template for the final assessment project for Udacity's React Fundamentals course.

## Overview

The project is related to SPA (Single Page Application) developed with React library. The aim of the application is to load set of books in three shelves: "Currently Reading", "Want to Read", "Read".
There is also another feature of Search Page, that allows to search for books thanks to usage of regular expressions. Books that have been found according to typed query, can be added to the one of chosen shelves.


### Backend Server

The provided file [`BooksAPI.js`](src/BooksAPI.js) contains the methods you will need to perform necessary operations on the backend:

* [`getAll`](#getall)
* [`update`](#update)
* [`search`](#search)

### Important 

The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend, so don't be surprised if your searches for Basket Weaving or Bubble Wrap don't come back with any results.


### Create React App

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). 

### TL;DR

* install all project dependencies with `npm install`
* start the development server with `npm start`

