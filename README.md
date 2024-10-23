# Account Management :


Overview :-  <br>
This project is a React-based application that includes user registration, login, and the ability to manage user information. Users can register, log in, edit, and delete information.

Prerequisites :-
-Node.js (v14+)  <br>
-npm (v6+)      <br>
-json-server   <br>
 
Installation and Setup :-  <br>

1. Clone the repository :  <br>
 git [clone repository-url]  <br>
 cd [project-directory]

2. Install dependencies : <br>
 npm install  <br>
 
3. Start the React development server : <br>
 npm run dev <br>

4. Start the JSON server :  <br>
Open a new terminal and run :  <br>
npx json-server backend/db.json --watch --port 5000  <br>

Usage :- <br>

1. Register a new account :  <br>
-Open the application and navigate to the Register page.  <br>
-Fill in the required details and submit the form.  <br>

3. Login to your account :  <br>
-Navigate to the Login page and enter your credentials to log in. <br>

3. Manage user information : <br>
-Navigate to the Users page to see a list of registered users. <br>
-You can edit or delete user information using the corresponding buttons. <br>


Notes :-  <br> 
-Ensure that the JSON server is running on port 5000 while using the application.  <br>
-The backend database is managed using a db.json file within the backend directory. <br>

Commands Summary : <br>
 Start React Dev Server: npm run dev <br>
 Start JSON Server: npx json-server backend/db.json --watch --port 5000
