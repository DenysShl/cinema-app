<p align="center">
<img src="images/cinema.jpg" width="686" height="289">
</p>

<p align="center" style="font-size: 32px"> CINEMA-APP </p>

### Project description:

This is an application that represents the Cinema service. It is built using SOLID principles and implemented as such
functionalities such as authentication, registration, selection of all movies, user tickets, list of permitted movie theaters. With the ability to add new ones and delete them
users, tickets and movies. Interaction with the database implemented using `Hibernate`.

## Features 👀️:

- User find by email and create
- Authentication login and register
- Create cinema hall
- Create movie service
- Complete order
- Display all cinema hall, movie, user
- Login and Register

## Realization details

### The project uses the following architecture:

- Data access layer (DAO)
- Application layer (services)
- Security layer (security)

## Technologies that were used to create the service:

- PostgreSQL
- Hibernate
- Maven Checkstyle Plugin

## 🚀️ Installation 🚀️

1. Type git clone, and then paste the URL you copied earlier.
   - `$ git clone https://github.com/DenysShl/cinema-app.git`
2. `pom.xml`

````xml
    <dependency>
        <groupId>org.hibernate</groupId>
        <artifactId>hibernate-core</artifactId>
        <version>5.4.21.Final</version>
    </dependency>
   <dependency>
       <groupId>org.hibernate</groupId>
       <artifactId>hibernate-entitymanager</artifactId>
       <version>5.4.21.Final</version>
   </dependency>
   <dependency>
       <groupId>org.postgresql</groupId>
       <artifactId>postgresql</artifactId>
       <version>42.3.5</version>
   </dependency>
````
### _Database structure_

![](images/structure_db.png)

### _UML_

![](images/Hibernate_Cinema_Uml.png)

### Hibernate Tutorial  [Hibernate](https://www.tutorialspoint.com/hibernate/)
