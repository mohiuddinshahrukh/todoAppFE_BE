# todoAppFE_BE

Changes: 
    Added a Dockerfile 
    Utilized a .env config file 
    Separated business logic into services
    Implemented proper error handling
    Included unit tests

To spin an image run the following two commands after cd-ing into the project backend root directory: 
(i) docker build -t todo_cowlar_backend .
(ii) docker run -d -p 5001:5001 todo_cowlar_backend

Then you just need to use npm start to run the frontend.
_______________________________________________________________________________________________________
This file contains two folders. One for the frontend (i) the other for the backend (ii) of the todo app.
The node modules are not contained therefore "npm i" would have to be run in both the folders (i & ii).

One that is done, the script npm start can be used in both applications to start them and run them.

(i) will run on port 3000
(ii) will run on port 5001

Frontend should have a logical flow hence i have integrated (without backend) a login and registration page.
Upon clicking "login", the user is navigated to home route where the CRUD functionality is implemented.

The menu/bars allow to filter the todos
The chevron-down allow to toggle the todos list.

The rest is intuitive.


I hope this much is enough to get a user ongoing with usage!

PS. I tried to deploy the application aswell... that unfortunately was a fail because the backend kept crashing even though it showed in logs it was running.

Frontend link: https://todo-app-frontend-liart.vercel.app/
Backend link: https://glitch.com/edit/#!/exciting-lackadaisical-jasper

If you want specific frontend and backend git repo links they are as follows:
Frontend: https://github.com/mohiuddinshahrukh/todoAppFrontend.git
Backend: https://github.com/mohiuddinshahrukh/todoAppBackend.git

