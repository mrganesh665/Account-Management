# React + Vite


Here’s the edited version formatted for GitHub:

Account Management :
Overview :-
This project is a React-based application that includes user registration, login, and the ability to manage user information. Users can register, log in, edit, and delete information.

Prerequisites :-
-Node.js (v14+)
-npm (v6+)
-json-server

Installation and Setup :-

1. Clone the repository:
git clone <repository-url>
cd <project-directory>

2. Install dependencies: 
npm install

3. Start the React development server:
npm run dev

4. Start the JSON server:
Open a new terminal and run:
npx json-server backend/db.json --watch --port 5000

Usage :-

1. Register a new account:
-Open the application and navigate to the Register page.
-Fill in the required details and submit the form.

3. Login to your account:
-Navigate to the Login page and enter your credentials to log in.

3. Manage user information:
-Navigate to the Users page to see a list of registered users.
-You can edit or delete user information using the corresponding buttons.


Notes:-
-Ensure that the JSON server is running on port 5000 while using the application.
-The backend database is managed using a db.json file within the backend directory.

Commands Summary:-
-Start React Dev Server: npm run dev
-Start JSON Server: npx json-server backend/db.json --watch --port 5000
