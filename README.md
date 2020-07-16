# Note-Taker01


## This cool app is designed for users who are willing to take further step saving their notes in a local server so that they can keep track on their plans.

* POST /api/notes receives a new note to save on the request.body, add it to the db.json file, and then return the new note to the client when the save icon is clicked. Here is the screen shot before saving (with the save icon circled):


* DELETE /api/notes/:id receives a query paramter containing the id of a note to delete when the trash can next to the corresponding title is clicked. The note is deleted from the list and from the db.json file.

# IMAGE 
<img width="1440" alt="Screenshot 2020-07-16 at 2 53 29 PM" src="https://user-images.githubusercontent.com/63940676/87726710-6d2cae80-c774-11ea-9ed0-020afb47ebd2.png">


##  User Story

AS A user, I want to be able to write and save notes

I WANT to be able to delete notes I've written before

SO THAT I can organize my thoughts and keep track of tasks I need to complete

 ## Business Context

For users that need to keep track of a lot of information, it's easy to forget or be unable to recall something important. Being able to take persistent notes allows users to have written information available when needed.