# role-based-login-spring-boot

Spring Boot Login and Registration example with MySQL, JWT, Rest API and Spring Security


Reference: https://github.com/bezkoder/spring-boot-login-example/

Blog: https://www.bezkoder.com/spring-boot-login-example-mysql/


There are three roles:

Admin -> Admin, Moderator and User board access

Moderator -> Moderator and User board ccess

User -> User board access


Signup and signin:

- Everyone has to be signed up and then signed in to see their board

- Public content can be accessed by all without signup or signin

Sample Data:

{
  "username": "admin",
  "email": "admin@bezkoder.com",
  "password": "12345678",
   "role": ["admin"]
}

{
  "username": "mod",
  "email": "mod@bezkoder.com",
  "password": "mod1234",
   "role": ["user", "mod"]
}

{
  "username": "zkoder",
  "email": "user@bezkoder.com",
  "password": "user1234",
   "role": ["user"]
}

{
  "username": "test1",
  "email": "test1@test.com",
  "password": "12345678",
   "role": ["user"]
}

{
  "username": "test2",
  "email": "test2@test.com",
  "password": "12345678",
   "role": ["mod"]
}


