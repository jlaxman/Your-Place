<h1>YourPlace - Full Stack Web Application</h1>


YourPlace is a web application that allows users to share images and locations with each other. It was built using ReactJS for the frontend, NodeJS and Express for the backend, and MongoDB for the database. The application is deployed on Heroku with a MongoDB cluster.

<h1>Features</h1>
Users can create an account and log in to the application.
Users can upload images and share their locations.
Users can view images and locations shared by other users.
Users can like and comment on images and locations shared by other users.
Users can edit and delete their own images and locations.
The application has a responsive design that works on desktop and mobile devices.

<h1>Getting Started </h1>
To run the application locally, follow these steps:

Clone the repository: git clone https://github.com/jlaxman/Your-Place.git
Install the dependencies: npm install
Start the server: npm start
Open the application in a web browser: http://localhost:3000


<h1>Deployment </h1>
The application is deployed on Heroku with a MongoDB cluster. To deploy the application to Heroku, follow these steps:

Create a Heroku account and install the Heroku CLI.
Create a new Heroku app: heroku create
Provision a MongoDB cluster: heroku addons:create mongolab:sandbox
Set the MONGODB_URIenvironment variable to the MongoDB URI: heroku config:set MONGODB_URI=<your-mongodb-uri>
Push the code to the Heroku app: git push heroku main
  
<h1>Contributing </h1>
If you would like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/my-new-feature
Make your changes and commit them: git commit -am 'Add some feature'
Push to the branch: git push origin feature/my-new-feature
Create a pull request.
  
<h1>License </h1>
This project is licensed under the MIT License - see the LICENSE.md file for details.

<h1>Acknowledgments </h1>
Thank you to the developers of ReactJS, NodeJS, Express, MongoDB, and Heroku for providing the tools and resources needed to build this application.
