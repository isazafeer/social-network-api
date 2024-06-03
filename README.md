# social-network-api

This project's primary focus is on the back end functionality, which will allow users to carry out CRUD (create, read, update, delete) operations. Express.js and Node.js will be utilized to construct and set up API routes. To store social networking data and specify the schema/models, Mongoose will function in tandem with MongoDB.

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Installation

- - Clone the repository using `git clone https://github.com/isazafeer/social-network-api.git` in the command line and run `npm i` to install dependencies.
- - Run `npm run start` in the command line to connect to the database.
- - Use Insomnia to test requests and responses
 
## Images of project

<img width="687" alt="Screenshot 2024-06-03 at 18 19 00" src="https://github.com/isazafeer/social-network-api/assets/116819407/d06e06f0-037f-48c8-88f7-122f56c08eab">

<img width="684" alt="Screenshot 2024-06-03 at 18 18 41" src="https://github.com/isazafeer/social-network-api/assets/116819407/52ec77ab-a376-4838-a5c2-0288d8a5ff15">


[Link to video](https://drive.google.com/file/d/16h0g_9Nc_exxcXVUSf9m2kvQqQBd12bk/view?usp=drive_link)
