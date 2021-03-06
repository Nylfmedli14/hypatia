# HYPATIA
A Comparative Religion App project
- a responsive stack app to catalogue all of the world's practicing religions.
- early MVP release for user feedback expected by last week of December 2017.

![Screenshots](public/styles/pics/login.png)

## Introduction
Hypatia allows you to read entries stored from other users stored into the database. The name Hypatia hearkens back to the historic period when the Library of Alexandria still stood and mystery schools abound. Like Wikipedia, users will also be able to add new entries of religion that will update and store into the database.

## Use Case
Why is this app useful? A typical internet user chats with others in forums and Reddit and a number of other social platforms without an understanding of some basic beliefs held by others. Hypatia is a bridge to facillitate such a dialogue.  

## UX

Initial wireframes for the home page can be seen below. Wireframes of all key processes were designed along with data flow for key data processing tasks.

![Initial Wireframes](public/styles/pics/wireframe.JPG)

The app was designed to work on mobile as well as tablet and desktop. 

## Live Site
You can access HYPATIA at https://young-tundra-49854.herokuapp.com/religion.

## Technical
* The app is built using the MEAN stack. The front-end is built using HTML5, CSS3 and JavaScript, the back-end using NodeJS with ExpressJS as the web server and MongoDB as the database.
* The app is fully responsive, adapting for mobile, table and desktop viewports.
* The app will come fully seeded with up to 52 religions registered in the United States found at http://www.blackrosespiritualcenter.org/wp-content/uploads/2014/08/ReligionsHandbook.pdf. 
* Up to 16 fields may be filled by users although only 6 will be required. This will act as the API once formatted. 
* All routing is handled in the back-end by Express.
* Extensive form validation and error handling is demonstrated throughout the app. On the front-end, field type, value, length etc is validated using HTML. On the back-end a Mongoose schema provides further error checking for field values and uniqueness.
* An extensive API has been built to provide database access to the app using ExpressJS, with separate endpoints constructed.
* The app is fully unit tested on the front and back-end. For the back-end, Mocha and Chai.
* The Mongo database is further secured with Passport authentication. 
* The app is deployed using Heroku.

