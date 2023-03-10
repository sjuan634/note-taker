# Note Taker

## Description

This web app allows you to write down and save notes. The backend uses express.js to handle GET and POST request from the frontend. When a note is saved in the frontend the backend uses ``` fs ``` node.js module to append the note to a ``` json ``` file. The backend also has a route that handles the deletion of a note from the frontend.

## User Story

```md
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

## Acceptance Criteria

```md
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```

## Usage
[NOTE TAKER](https://gentle-island-34502.herokuapp.com/)
---
[Demo Video](https://drive.google.com/file/d/1uXixhL_pVMv8E2_pnP0OmvGQ0_VYX7xN/view)