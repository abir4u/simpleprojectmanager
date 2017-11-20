# Simple Project Manager (Primitive PoC)
This is a simple POC using React.js where I can add/delete a set of projects stored at the frotend.


To make this project work, the following steps must be followed:

## Prereqeuisites:
Have NodeJS and NPM installed in your machine by downloading it from nodejs.org

## Steps:
1. Go to your project folder from Terminal/Command Prompt
2. Run the command `npm install -g create-react-app` (if you have already not done it beforehand)
3. Run the command `create-react-app xyz` (where 'xyz' could be anything. It is the name of the project you want to put)
4. Use Finder/Windows Explorer to navigate into your local project and open folder 'src'
5. Paste the content of this repository in src
6. Go back to Terminal/Command Prompt and 'cd' into your project folder
7. Run the command `npm start`

Once the application is built, it should look like the below screenshot:

![this image](https://github.com/abir4u/simpleprojectmanager/blob/master/App_Screenshot.png?raw=true "Optional Title")

## How to use the App
There are two functionalities that you can perform on this app:
1. Add details of a new App
2. Delete existing App details
3. Display error message

#### Add details of a new App
To add details of a new app, type in a title in the 'Title' field and choose an app category from 'Category' field and click on 'Submit' button. The details will get added below the list of App details available.

#### Delete existing App details
To delete an existing App details, click the 'Remove' button corresponding to the details you want to delete.

#### Display error message
If you click on Submit without filling up the 'Title' field, you will receive an alert saying 'Title is missing'.
