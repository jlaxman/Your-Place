<!DOCTYPE html>
<html>
<head>
  <title>YourPlace - Full Stack Web Application</title>
</head>
<body>
  <h1>YourPlace - Full Stack Web Application</h1>

  <h2>Features</h2>
  <ul>
    <li>Users can create an account and log in to the application.</li>
    <li>Users can upload images and share their locations.</li>
    <li>Users can view images and locations shared by other users.</li>
    <li>Users can like and comment on images and locations shared by other users.</li>
    <li>Users can edit and delete their own images and locations.</li>
    <li>The application has a responsive design that works on desktop and mobile devices.</li>
  </ul>

  <h2>Getting Started</h2>
  <p>To run the application locally, follow these steps:</p>
  <ol>
    <li>Clone the repository: <code>git clone https://github.com/jlaxman/Your-Place.git</code></li>
    <li>Install the dependencies: <code>npm install</code></li>
    <li>Start the server: <code>npm start</code></li>
    <li>Open the application in a web browser: <a href="http://localhost:3000">http://localhost:3000</a></li>
  </ol>

  <h2>Deployment</h2>
  <p>The application is deployed on Heroku with a MongoDB cluster. To deploy the application to Heroku, follow these steps:</p>
  <ol>
    <li>Create a Heroku account and install the Heroku CLI.</li>
    <li>Create a new Heroku app: <code>heroku create</code></li>
    <li>Provision a MongoDB cluster: <code>heroku addons:create mongolab:sandbox</code></li>
    <li>Set the <code>MONGODB_URI</code> environment variable to the MongoDB URI: <code>heroku config:set MONGODB_URI=&lt;your-mongodb-uri&gt;</code></li>
    <li>Push the code to the Heroku app: <code>git push heroku main</code></li>
  </ol>

  <h2>Contributing</h2>
  <p>If you would like to contribute to the project, please follow these steps:</p>
  <ol>
    <li>Fork the repository.</li>
    <li>Create a new branch: <code>git checkout -b feature/my-new-feature</code></li>
    <li>Make your changes and commit them: <code>git commit -am 'Add some feature'</code></li>
    <li>Push to the branch: <code>git push origin feature/my-new-feature</code></li>
    <li>Create a pull request.</li>
  </ol>

  <h2>License</h2>
  <p>This project is licensed under the MIT License - see the <code>LICENSE.md</code> file for details.</p>

  <h2>Acknowledgments</h2>
  <p>Thank you to the developers of ReactJS, NodeJS, Express, MongoDB, and Heroku for providing the tools and resources needed to build this application.</p>
</body>
</html>

