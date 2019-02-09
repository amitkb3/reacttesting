# React Testing App

This app was developed based on the training from Udemy Course [Advanced React and Redux: 2018 Edition](https://www.udemy.com/react-redux-tutorial/) taught by Stephen Grider

### User Stories

* User can type comments in a text area and submit by pressing button.
* The textarea will be cleared after each submit
* The User's comments will be displayed below in the comment list area
* The User can also fetches list of comments from the JsonPlaceholder Api's comment endpoint by pressing 'Fetch Comments' button
* The fetch comments will also be displayed in the Comment List Area

### Purpose

The purpose of this app is to use Jest and Enzyme packages to conduct unit and integration Testing.

Following Tests were performed:
1. Unit Tests for App Component
  * shows a comment box 
  * shows a comment list 
2. Unit Tests for Comment Box Component
  * has a text area and two button 
  * has a text area that users can type in
  * when form is submitted,text area gets emptied 
3. Unit Tests for Comment List Component
  * creates one LI per comment 
  * shows the text for each comment
4. Unit Tests for Reducers
  * handles actions of type SAVE_COMMENT
  * handles action with unknown type 
5. Unit Tests for Actions
  * has the correct type
  * has the correct payload
5. Integration Test for App
  * can fetch a list of comments and display them
