# How to connect (MySQL)
 - Go to conn.java
 - Configurate
 ```
    // 10. Check your connection here...
    jdbc:mysql://localhost:[port]/[database_name]
    private static final String URL = "jdbc:mysql://localhost:3307/finals";
    private static final String USER = "root"; // Set the username of the database connection
    private static final String PASSWORD = "root"; // Set the password of MySQL connection
 ```
- jdbc:mysql://localhost:[port, this usually 3306, you can see it on]/[database_name]

![localhost](https://github-production-user-asset-6210df.s3.amazonaws.com/109123846/578355264-ed90d1ee-49d3-4b11-afdd-9aecb909bc00.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260415%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260415T031303Z&X-Amz-Expires=300&X-Amz-Signature=2c2083e48ed3cbb9700d23fce37949becd265426203eb7c3fcdf1a6dfc490fac&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng)