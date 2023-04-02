PostgreSQL [(link to website here)](https://www.postgresql.org/) is an open-source relational database management system (RDBMS).
As an RDBMS, PostgreSQL stores its data in the form of relations, or tables.
In addition to being a relational database, it also supports some of the features of object databases, making it an object-relational database.
PostgreSQL uses a client-server model, so users must use a database server in order for it to setup and run over a network. 
For Java to access it, users must download a PostgreSQL JDBC driver to connect Java to the PostgreSQL database server.
The driver allows Java programs to connect to a PostgreSQL database using standard, database independent Java code.
JDBC drivers usually include functionality like creating and maintaining a connection to a database, sending commands to that database, and
delivering the database response back to the Java program.


# Sources:
### https://www.postgresql.org/
### https://hevodata.com/learn/sqlite-vs-postgresql/#intro_postgresql
### https://www.postgresqltutorial.com/postgresql-jdbc/connecting-to-postgresql-database/#:~:text=To%20connect%20to%20the%20PostgreSQL,file%20is%20a%20jar%20file.
### https://jdbc.postgresql.org/



The PostgreSQL JDBC Driver allows Java programs to connect to a PostgreSQL database using standard, database independent Java code. pgJDBC is an open source JDBC driver written in Pure Java (Type 4), and communicates in the PostgreSQL native network protocol. Because of this, the driver is platform independent; once compiled, the driver can be used on any system.
