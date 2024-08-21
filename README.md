# MySQL Connector/J 9.0 Project file

This project demonstrates how to use MySQL Connector/J 9.0 to connect a Java application to a MySQL database. The MySQL Connector/J 9.0 is a Java driver that allows seamless communication between Java applications and MySQL databases using JDBC and X DevAPI protocols.

## Features
- Connect to MySQL databases
- Execute SQL queries
- Manage transactions
- Perform CRUD operations

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- MySQL Server 5.7 or higher
- MySQL Connector/J 9.0 JAR file

## Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/mysql-connectorj-example.git
    cd mysql-connectorj-example
    ```

2. **Download the MySQL Connector/J 9.0 JAR:**
   - Visit the [official MySQL website](https://dev.mysql.com/downloads/connector/j/) to download the MySQL Connector/J 9.0 JAR file.

3. **Add the JAR file to your project:**
   - Place the downloaded JAR file in the `libs` directory of your project.

4. **Configure the database connection:**
   - Update the `db.properties` file with your MySQL database credentials:
     ```properties
     db.url=jdbc:mysql://localhost:3306/your-database
     db.username=your-username
     db.password=your-password
     ```

5. **Build and run the project:**
    ```bash
    javac -cp "libs/mysql-connector-java-9.0.0.jar" -d bin src/*.java
    java -cp "libs/mysql-connector-java-9.0.0.jar:bin" com.yourpackage.Main
    ```

## Acknowledgments

- [MySQL Connector/J Documentation](https://dev.mysql.com/doc/connector-j/9.0/en/)
- [Oracle MySQL](https://www.mysql.com/)
