Travlr Getaways Full Stack Web Application
Architecture

In this project, I implemented both traditional Express-based HTML with JavaScript and a single-page application (SPA) using Angular. Express HTML allowed for quick server-rendered pages and simple form handling, while the SPA enabled a more dynamic user experience with seamless page transitions and reactive components. Combining these approaches allowed the customer-facing SPA to be highly interactive, while the admin side benefited from server-rendered pages with secure authentication.

The backend uses a NoSQL MongoDB database because the application stores flexible and dynamic data such as travel packages, user profiles, and trip details. MongoDB allows for schema-less design, making it easier to adapt to changing requirements without complex migrations, which is ideal for rapidly evolving applications like Travlr Getaways.

Functionality

JSON is a lightweight data-interchange format that is syntactically similar to JavaScript but independent of it. Unlike JavaScript objects, JSON is text-based and can easily be sent between a frontend and backend over HTTP. In this project, JSON served as the bridge between the frontend SPA and the backend API endpoints, allowing data such as trips, bookings, and user information to flow efficiently between the client and server.

Throughout development, I refactored code to improve functionality and efficiency. For example, reusable UI components for trip cards, navigation menus, and forms were created to standardize look-and-feel across the application. This reduced duplication, simplified maintenance, and enabled faster feature development since components could be reused in multiple parts of the application.

Testing

API testing involved sending requests to endpoints and verifying the correct responses, status codes, and error handling. Methods like GET, POST, PUT, and DELETE were tested to ensure CRUD operations functioned properly. Security features, such as admin login authentication, introduced additional challenges, requiring testing of token validation, session management, and role-based access control. These layers ensured that sensitive administrative operations remained protected while customer-facing endpoints remained accessible.

Reflection

This course has significantly advanced my full stack development skills, giving me practical experience with frontend frameworks, backend APIs, and database management. I have developed proficiency in integrating SPAs with RESTful APIs, handling NoSQL databases, implementing secure authentication, and creating reusable components. These skills make me a more competitive candidate for roles in web development, software engineering, and full stack development. Additionally, the experience of debugging, testing, and refactoring a complete application has strengthened my problem-solving and project management abilities, preparing me for professional software development environments.
