
## Deployed instance

 `http://34.219.63.63:3000`

Surveyapp provides a platform for users to create and take survey. The user is offered a variety of options to create questions for the survey. The surveyors are invited to take the survey either through email or QRcode. The Surveyor can see the statistics for each survey and will be analyze the results. We have options for user to take the survey anonymously as well. A user can sign up for suveyape account and he would be sent a confirmation mail to activate his account. The application was developed using Spring boot for the backend, JPA with Hibernate as the provider for persistence, MySQL for the database and ReactJS for the frontend.


Build instructions: 

1. Clone repository
2. Install Node.js to location of directory SurveyApeFrontEnd
3. Install NPM to location of directory
4. Run "npm install" to load all node dependencies
5. Run frontend application by "npm start"
6. Install Java JDK 1.8.1
7. Maven import to root SurveyApe directory location
8. Run "mvn clean package" to root SurveyApe directory
9. Run "java -jar <SNAPSHOT jar name>"

