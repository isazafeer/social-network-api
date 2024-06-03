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

[Link to video](https://drive.google.com/file/d/1Wac8KEBdpseeUio5p-R9xmSC4WjBON28/view?usp=drive_link)