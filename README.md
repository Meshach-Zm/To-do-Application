# To-do-Application
A Simple Spring boot + Next.js todo application
Used Spring Data JPA for CRUD operations on a SQLite database, And Next.js frontend
On Local host, both spring boot and Next.js server are run at the same time and http requests are made from the frontend and handled by spring boot crontroller methods. Security is handled by NextAuth and session data is send and stored to the database via axios post menthod. 
Altenatively, the backend can be deployed on heroku and next.js on vercel and interact via http requests


<h3>Tools used </h3>
<ul>
<li>Spring Boot 3</li>
<li>Spring Framework 6</li>
<li>Spring Data JPA</li>
<li>Hibernate</li>
<li>Spring MVC</li>
<li>Apache Maven</li>
<li>SQLite</li>
<li>Next.js</li>
<li>NextAuth</li>
<li>React</li>
<li>axios</li>
<li>VS Code </li>
</ul>
AWS Elastic Beanstalk, EC2 & RDS, Localhost or Heroku for deployment

<h3> How to Get Started <h3>
<h5>clone this repository into your local machine</h5>
<h5>cd my-to-do-list</h5>
<h5> run application in the sr src/main folder</h5>
<h5>open another terminal </h5>
<h5>cd mytodoclientside and npm install</h5>
<h5>run the next.js development server after node modules installation: npm run dev</h5>
<h5>view todo app in your browser: localhost:3000</h5>
Done!
