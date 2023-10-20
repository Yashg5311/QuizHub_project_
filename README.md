# QuizHub_project_
<div align="center">
  <a href="https://github.com/Yashg5311/QuizHub_project_">
    <img width="255" alt="logo" src="https://github.com/Yashg5311/QuizHub_project_/assets/91370994/e512e2d5-21ce-4eb6-a0bb-274ad6585922">
  </a>

  <h2 align="center">QuizHub</h2>

  <p align="center">
    Build with the MERN stack (MongoDB, Express, React and NodeJS).
    <br />
    <a href="https://quizhub-site.onrender.com/login"><strong>Explore the Project »</strong></a>
    <br />
    <br />
  </p>
</div>


## MERN Stack Quiz Application

  * [Introduction](#introduction)
  * [Key Features](#key-features)
  * [Technologies used](#technologies-used)
      - [Frontend](#frontend)
      - [Backend](#backend)
      - [Database](#database)
  * [Configuration and Setup](#configuration-and-setup)
  


## Introduction
This is a MERN Stack project based on Quiz Application Portal. The entire application is based on two roles: User and Admin.Users can give exam , see the instructions,give the test based on time, can see the ans which are correct and wrong and also can retake the exam. Users can see the reports on the exams given by them based on date, passing marks and verdict.
Users acn also see the profile Page. The same functionality is also added for Admins. Admins also can create Quiz and create the tests, add questions.Have a Look at Entire Application!
Login Page:
![Screenshot (23)](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/cee82063-3f73-4d81-82bc-ab68da19fc96)

Home page:
![Screenshot (25)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/2cde1ef3-9071-4b6b-a8ff-564bb18ae7c8)

Reports page for User:
![Screenshot (26)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/a6312a1c-e63d-463d-8206-36b6452ae7e4)

Profile page for Users:
![Screenshot (27)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/7f62243f-3e3a-4712-897a-8d6f84025e7f)

Instruction Page for Quiz:
![Screenshot (28)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/ecdb6a73-c4c5-40b6-aabb-226041b8525b)

Question Page with Options and Timer:
![Screenshot (30)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/a259d8b3-796e-4177-8e07-674fed180617)

Result Page with Marks:
![Screenshot (31)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/fde47348-f0a3-4ce1-b579-b2fa0ca9762b)

Correct Answers Page with Review:
![Screenshot (32)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/e6b80396-72e4-48b8-b530-3c4e26ef4558)

Admin Home Page:
![Screenshot (33)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/efee5b9e-a24d-409b-9445-5e84a886560b)

Exams Page for Admin:
![Screenshot (34)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/5c1d4dd4-8fd5-4611-a1b8-40956b81a9a2)

Add Exam Page for admin:
![Screenshot (35)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/1c674b28-477f-449e-bb6e-465121fac31d)

Edit Exam Page for admin:
![Screenshot (36)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/0155c6fb-7598-4fa3-8029-bcec44b9ccd4)

Edit Exam for admin:
![Screenshot (37)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/f99eefed-b4ec-4461-bee7-bf0cc9307d58)

Add Question for Admin:
![Screenshot (38)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/6c53780b-2c18-4536-a820-dd124d60dabc)

Search Reports based on Exam and Profile:
![Screenshot (39)edit](https://github.com/Yashg5311/QuizHub_project_/assets/91370994/4359c168-4281-472f-a49d-c7e8e7a6cee1)

## Key Features
- Engineered a dynamic application that facilitates quiz participation for users and enables quiz creation for
administrators.
- Incorporated features that allow administrators to review responses, generate comprehensive quiz reports
- Created Separate Portal for User and Admin.
- Admin can add question , search reports.
- Used Antd library in React.
- Used Redux for State Management
- Delpoyed on Render.


## Technologies used
This project was created using the following technologies.

#### Frontend

- React JS
- Antd library
- Redux
- JavaScript
- Axios

#### Backend

- ExpressJS
- NodeJs
- Mongoose
- JWT (For authentication)
- Bcryptjs (for data encryption)

#### Database
MongoDB (MongoDB Atlas)

## Configuration and Setup
In order to run this project locally, simply fork and clone the repository. 
- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the client on one terminal and the server on the other terminal)

In the first terminal

$ cd client
$ npm install (to install client-side dependencies)
$ npm start (to start the client)


For setting up backend
- cd create a .env file in the root of your directory.
- Supply the following credentials

MONGO_URL=
JWT_SECRET=





Provide some random key in ACCESS_TOKEN_SECRET or you could generate one using node enter the below command in the terminal to genrate a random secret key 


node -e "console.log(require('crypto').randomBytes(256).toString('base64'));"


In the second terminal (*in the project root directory (server)).

```
$ npm install (to install server-side dependencies)
& nodemon server (to start the server)
