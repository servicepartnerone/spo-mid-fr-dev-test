# SPO recruitment task for mid-level front-end developers

Hello! If you are here then you reached the coding challenge for mid-level front-end developers at SPO! 
Bellow you will find some description, about the coding challenge that we would like you to complete.

The source code of the solution should be provided as a bunch of files. It is highly recommended to use some build tools (preferably gulp or webpack) and push all the sources to git repository so you will be able to demonstrate also your ability of working with build tools and git itself. Please note that **code quality** is also important for us.

Good luck to you and hope you will enjoy the process while solving this task!


## Create a photo gallery application

The aim of this exercise is to create a photo gallery application using React & Redux. You can use 'npm mock-json-server' to mock the server data and do the proper API calles. You need to use *REST API* to get the data.

You should take no more than 4h to complete this task.

You should start by rendering a single page view with photo list.


### Technical requirements


1. Mock the data and create API layer using axios or isomorphic-fetch libraries to retrieve the mocked data.

2. Organize the data flow using Redux. Dispatch some actions to retrieve the data and store the data, coming from API calls, in the Redux stores

3. Show photo thumbs in the single page. The page should be responsive.

4. Allow the user to select a photo by clicking on it and then open a popup to show the photo with original size and with some description.

5. Inside the popup the user has ability to add some comment. If the user adds some comment it should be saved in the Redux store by dispatching proper actions inside the component.


### Bonus (optional)

Writing unit tests for the available features will be considered as a big plus.

