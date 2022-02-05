# spring-oauth-login-starter
Starter Spring Boot project for OAuth login with Google , facebook and GitHub

Simple starter for a Spring Boot Web application with Google , facebook and GitHub OAuth support.

Steps:
1. Add your client Id and secret to the 'application.yml' file and you are good to go. 
2. Update client Id in index.html file and call back uri as well.
3. Run the Spring Boot App. You should be able to login with Google , facebook and GitHub.

After login, you will be redirected back to the login page, but you can validate the authorized principal is created by accessing the `/user` API. 
