Complete DevOps Structure PipeLine

<img width="1156" height="829" alt="Screenshot 2025-08-08 134024" src="https://github.com/user-attachments/assets/84a8a15d-f69c-4b7a-ade4-9b539e8d5a3c" />

<img width="1919" height="927" alt="Screenshot 2025-08-08 134555" src="https://github.com/user-attachments/assets/cd010dd3-5de9-4c3f-a8a5-82ad1a996abe" />
<img width="1919" height="929" alt="Screenshot 2025-08-08 134500" src="https://github.com/user-attachments/assets/9ff89b36-8069-4489-9277-5687d6316646" />

Using MobaXterm Software for : ( Master , Slave , Jenkins , Nexus , SonarQube and Required virtual Machines
<img width="1919" height="1079" alt="Screenshot 2025-08-08 134705" src="https://github.com/user-attachments/assets/20d601be-7d14-49c8-ad5a-aa7b9ae66788" />
<img width="1915" height="1079" alt="Screenshot 2025-08-08 135125" src="https://github.com/user-attachments/assets/4afce17f-95eb-4fda-94bc-49f218c1064b" />

**Encorporating the CI/CD Pipe Lines **
<img width="1919" height="929" alt="Screenshot 2025-08-08 135451" src="https://github.com/user-attachments/assets/0f11538d-3103-4ba1-8d9c-db327415acd0" />
<img width="1918" height="542" alt="Screenshot 2025-08-08 135516" src="https://github.com/user-attachments/assets/e881164e-e268-476c-9c88-5ab750e4f194" />

**SonarQube Analysis **
<img width="1918" height="926" alt="Screenshot 2025-08-08 135626" src="https://github.com/user-attachments/assets/123c5f13-988f-49ad-b1ba-9c17413e9137" />

**Nexus Repository **
<img width="1919" height="569" alt="Screenshot 2025-08-08 135724" src="https://github.com/user-attachments/assets/0152c45e-d0e5-423b-8f50-33cc69974956" />

**CI/CD Deployment **
<img width="1905" height="695" alt="Screenshot 2025-08-08 135921" src="https://github.com/user-attachments/assets/a8400af1-f909-4418-8997-9f6dea0bfbd5" />

**Email - Notification **

# BoardgameListingWebApp

## Description

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊
