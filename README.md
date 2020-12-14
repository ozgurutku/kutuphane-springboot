# Spring Boot Intern Project

#### Project Features
* Author Definition can be made. (Author Name, Description)
* Publisher Definition can be made. (Publisher Name, Description)
* The book can be promoted. (book title, book sub-name, book series name, author, publisher, isbn number, description)
* N books can be defined for an Author.
* N books can be defined for a Publisher.
* It can be searched by the name of the book.
* Changes can be made to an existing record.
* Existing records can be reviewed.
* An existing record can be deleted.

**Dependencies:** Java 11.0.9, Maven, MySQL 8.0.22

### Create Database 
```sh
$ mysql -u root -p -e "create database kutuphane";
```

### Default Database Configuration
You can change these settings in the **application.properties** file. If you do not edit these properties, you will encounter an **error** in the **Install dependencies**  step.

`spring.datasource.url = jdbc:mysql://localhost:3306/kutuphane?useSSL=false&serverTimezone=UTC&useLegacyDatetimeCode=false`

`spring.datasource.username=root`

`spring.datasource.password=123456`

### Install depedencies

```sh
$ mvn clean install
```

### Start

```sh
$ mvn spring-boot:run
```
or

```sh
$ java -jar target/kutuphane-0.0.1-SNAPSHOT.jar
```

### Usage
For admin use
`Admin user name = ozgurutku Admin password = ozgurutku`

For member use
`register as a member`