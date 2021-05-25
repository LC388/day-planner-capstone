# Day Planner Capstone

Are you stuck in a rut? click on this application to help you figure out your next day in, or out.

### 1. Working Prototype (to do later)

(Example) You can access a working prototype of the React app here: https://your-app-client.herokuapp.com/ and Node app here: https://your-app-server.herokuapp.com/

### 2. User Stories (to do now)

This app is for two types of users: a visitor and a logged-in user

###### Landing Page (Importance - High) (Est: 1h)
- as a visitor
- I want to understand what I can do with this app
- so I can decide if I want to use it

###### Login Page (Importance - High) (Est: 3h)
- as a visitor
- I want to login so I can use this app
- so I can plan my day

###### Registration Page (Importance - High) (Est: 3h)
- as a visitor
- I want to register
- so I can plan my day

###### Landing Page (Importance - High) (Est: 1h)
- as a registered user
- I want to choose day in or day out
- so I can see places or recipies related to my choice

###### Search Out (Importance - High) (Est: 1h)
- as a registered user
- If I choose day out I want to set my location and preferences
- In order to see places to go and restaurants

###### Results Out(Importance - High (Est: 3h)
- as a registered user
- I will have a list of places and restaurants to select from based on my input
- In order to plan my day out

###### Search In (Importance - High) (Est: 1h)
- as a registered user
- If I choose day in I want to set my prefrences
- In order to see recipies and movie suggestions

###### Results In (Importance - High (Est: 3h)
- as a registered user
- I will have a list of recipies and movies to choose from based on my input
- in order to plan my day in

### 3. Functionality (to do now)

The app's functionality includes:

- Every User has the ability to land on home page to read and understand what the page is about
- Every User has the ability to choose to plan a day in or day out
- Every User has the ability to plan a day out for places to go (restaurants park and museums)
- Every User has the ability to plan a day in recipes suggestions or movies;

### 4. Technology
* Front-End: HTML5, CSS3, JavaScript ES6, React
* Back-End: Node.js, Express.js, Mocha, Chai, RESTful API Endpoints, Postgres
* Development Environment: Heroku, DBeaver

### 5. Wireframes (to do now)

(Example) Landing Page
:-------------------------:
![Landing Page](/github-images/wireframes/landing-page-wireframe.png)
Register Page
![Register Page](/github-images/wireframes/register-page-wireframe.png)

### 6. Front-end Structure - React Components Map (to do later)
* (Example) __Index.js__ (stateless)
    * __App.js__ (stateful)
        * __LandingPage.js__ (stateful) - gets the _"prop name"_ and the _"callback prop name"_ from the __App.js__
            * __Login.js__ (stateful) -
            * __Register.js__ (stateful) -
        * __Navbar.js__ (stateless) -



### 7. Back-end Structure - Business Objects (to do later)
* Users (database table)
    * id (auto-generated)
    * username (email validation)
    * password (at least 8 chars, at least one alpha and a special character validation)
    * location (varChar 255)

* Favorites (database table)
    * id (auto-generated)
    * user_id (foreign key connecting to users table)
    * title (varChar 255)
    * type (varChar 255) (recipes, restaurants)
    * details (text)

### 8. API Documentation (to do later)

#### API Overview

```text
    /api
    .
    ├── /auth
    │   └── POST
    │       ├── /login
    ├── /users
    │   └── POST
    │       └── /
```

### 9. Screenshots (to do later)

(Example) Landing Page
:-------------------------:
![Landing Page](/github-images/screenshots/landing-page-screenshot.png)
Register Page
![Register Page](/github-images/screenshots/register-page-screenshot.png)

### 10. Development Roadmap (to do later)

This is v1.0 of the app, but future enhancements are expected to include:

- (Example) add more functionality

### 11. How to run it (done)
Use command line to navigate into the project folder and run the following in terminal

##### Local React scripts
* To install the react project ===> npm install
* To run react (on port 3000) ===> npm start
* To run tests ===> npm run test

##### Local Node scripts
* To install the node project ===> npm install
* To migrate the database ===> npm run migrate -- 1
* To run Node server (on port 8000) ===> npm run dev
* To run tests ===> npm run test
