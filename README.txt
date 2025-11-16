Garage Booking - Module 1 sample project
Structure:
- src/main/java/com/quang/quanlynguoidung/{model,dao,controller}
- JSP files in src/main/webapp/

How to use:
1. Edit DatabaseConnection.java: set DB_URL, DB_USER, DB_PASS.
2. Create MySQL database and table using the provided SQL file.
3. Build with: mvn clean package
4. Deploy the generated WAR (target/garage-booking.war) to Tomcat or another servlet container (Tomcat 9+).
5. Access: http://localhost:8080/garage-booking/

SQL file: sql/create_table.sql
