# session-based-authentication-api
 secure session-based authentication system using Node.js, Express.js, and cookies to manage user sessions, enabling seamless login, protected access to routes, and enhanced security.

# Features
✅ User Authentication using bcrypt.js for secure password hashing

✅ Session Management using express-session to store session data securely on the server

✅ Secure Cookie Handling with HTTP Only & Secure cookies to prevent XSS and session hijacking

✅ Protected Routes ensuring only authenticated users can access sensitive data

✅ Session Expiration & Renewal to improve security and user experience

✅ Defense Against Attacks including Session Fixation and Cross-Site Scripting (XSS)


 # Technologies Used
Node.js - JavaScript runtime environment

Express.js - Web framework for Node.js

bcrypt.js - Secure password hashing

express-session - Session management middleware

dotenv - Loads environment variables

 # API Endpoints
Method  	Endpoint	  Description	                          Protected
POST	    /register	   Register a new user	                  ❌
POST	    /login	     Authenticate user & start session	    ❌
GET	    /dashboard	   Access protected dashboard	            ✅
GET	    /logout	       Destroy session & logout user	        ✅

 # Future Enhancements
✅ Implementing OAuth (Google, GitHub) authentication

✅ Storing sessions in a Redis database for scalability

✅ Multi-factor authentication (MFA) for extra security

