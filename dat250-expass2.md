
## DAT250 Expassignment 2 Report

Link to my repository for the code: https://github.com/mathiasskauge/dat250-jpa-tutorial

## Technical Problems with JPA Installation and Resolution.

I didn't experience any major issues with the installation.

## Inspecting the database tables

For inspecting the databases I've tried to establish a connection with mySQL workbench but havnt quite figured it out so far. I tried changing the persistence.xml file to have the database connect to the workbench and also added a "MySQL JDBC driver" to the classpath. I didn't manage to establish a connection with it yet.


## Questions:

The database H2 is an embedded database. It means that the database engine runs within the Java application, and it is not a separate server like MySQL. 
It starts when the application starts and saves data in a file named "DB" in the project's root directory. 

Yes, I just change the value of hibernate.format_sql to "true" to get the sql
Hibernate: 
    create table Customer (
        id bigint generated by default as identity,
        name varchar(255),
        primary key (id)
    )





