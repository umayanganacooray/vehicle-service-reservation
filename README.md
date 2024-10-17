# Vehicle Service Reservation Web Application 🚗 
A dynamic web application designed for vehicle service reservations, with a strong emphasis on security by addressing OWASP Top 10 vulnerabilities. The application integrates user authentication and access control using OAuth 2.0, facilitated by Asgardeo as the Identity Provider (IDP).

### Key Features: ✨ 
- User Profile Display: Shows authenticated user's information including username, full name, email, contact number, and country.
- Reservation System: Users can book vehicle services by providing details such as service date, preferred time, location, vehicle registration number, current mileage, and additional notes.
- Reservation Management: Allows users to view and delete upcoming reservations while maintaining a history of past reservations.
- Input Validation & Security: Incorporates input validation and sanitization to prevent common security threats like SQL injection and Cross-Site Scripting (XSS).

### Technologies Used: 🛠️
- Frontend: JSP (Java Server Pages) for dynamic content rendering.
- Backend: MySQL database, Apache Tomcat as the web server.
- Authentication: OAuth 2.0 via Asgardeo for secure user login and access control.
- Security Measures: Prepared statements for SQL injection prevention, input validation, and sanitization to mitigate XSS vulnerabilities.

### Security Highlights: 🔒
- Protection against SQL Injection by using prepared statements.
- Mitigation of XSS vulnerabilities through robust input sanitization.
- Access control enforced to ensure users can only manage their own reservations.

🔎 For further details and configuration instructions, check out my blog articles on this project below: 

### Blog Articles 🌐
-📌 https://medium.com/@ume.cooray/strengthening-security-and-authentication-in-vehicle-reservation-web-application-addressing-owasp-39f69ac958cd
