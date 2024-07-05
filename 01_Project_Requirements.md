
Design Architecture Diagram

Important!
For the following questions please design Architectural diagram using appropriate products in either AWS, Azure or GCP. This will be part of your evaluation. Use draw.io or Microsoft Visio or GCP Architecture diagram. Choice is yours. Please ensure the architecture ensures 99.999% availability, multi region in three regions( in case of one region being down the other region takes over) use the cloud product that is appropriate, please explain what and why you chose that product. My preference is using AWS for one, Azure for one and GCP for one. Please elaborate as much as possible, during the classwork, it is mandatory to finish atleast one ☝️. Thank you 😊 

Scenario 1: E-commerce Website

Architecture:

1. Presentation Tier (Frontend):

   - Components:Web browser, Mobile app.

   - Technologies:HTML, CSS, JavaScript, React.js, Swift (for iOS app), Kotlin (for Android app).

2. Application Tier (Backend):

   - Components:Web server, API server.

   - Technologies:Node.js with Express.js, Python with Flask/Django, Java with Spring Boot.

3. Data Tier (Database):

   - Components:Database server.

   - Technologies:MySQL/PostgreSQL (for relational data), MongoDB (for NoSQL data).

Scenario:

An e-commerce website where users browse products, add them to the cart, and complete purchases. 

- User Interaction:Users interact with the website or mobile app to search for products, view details, and make purchases.

- Business Logic:The backend server processes product searches, handles user authentication, manages the shopping cart, and processes payments.

- Data Storage: Product information, user accounts, and transaction records are stored in the database.

Flow:

1. The user accesses the e-commerce website or mobile app.

2. The frontend sends requests to the backend to fetch product data.

3. The backend retrieves data from the database and processes it.

4. The backend sends the processed data back to the frontend to display to the user.

5. The user adds products to their cart and proceeds to checkout.

6. The backend processes the payment and updates the transaction data in the database.

Scenario 2: Online Learning Platform

Architecture:

1. Presentation Tier (Frontend):

   - Components:Web browser, Mobile app.

   - Technologies:Angular, HTML, CSS, JavaScript, Flutter (for mobile apps).

2. Application Tier (Backend):

   - Components:Web server, API server.

   - Technologies:Python with Django/Flask, Ruby on Rails, Node.js.

3. Data Tier (Database):

   - Components:** Database server, File storage.

   - Technologies:** PostgreSQL (for relational data), Amazon S3/Google Cloud Storage (for storing course materials).

Scenario:

An online learning platform where users can enroll in courses, watch video lectures, and complete assignments.

- User Interaction:Users interact with the website or mobile app to browse courses, watch videos, and submit assignments.

- Business Logic:The backend server manages user authentication, course enrollment, and assignment submissions.

- Data Storage:Course details, user progress, video files, and assignment submissions are stored in the database and file storage.

Flow:

1. The user logs in to the online learning platform via the website or mobile app.

2. The frontend requests course data from the backend.

3. The backend retrieves course information from the database and sends it to the frontend.

4. The user enrolls in a course and starts watching video lectures.

5. The backend tracks the user's progress and stores it in the database.

6. The user submits assignments, which are processed by the backend and stored.

Scenario 3: Social Media Application

Architecture:

1. Presentation Tier (Frontend):

   - Components:Web browser, Mobile app.

   - Technologies:Vue.js, HTML, CSS, JavaScript, React Native.

2. Application Tier (Backend):

   - Components:Web server, API server.

   - Technologies:** Go with Gin, Node.js with Express.js, Java with Spring Boot.

3. Data Tier (Database):

   - Components:Database server, Cache server.

   - Technologies:** MongoDB (for user posts), Redis (for caching frequently accessed data).

Scenario:

A social media application where users can create profiles, post updates, and interact with each other's content.

- User Interaction:Users interact with the website or mobile app to create profiles, post updates, and comment/like posts.

- Business Logic:The backend server handles user authentication, post creation, and social interactions.

- Data Storage:User profiles, posts, comments, and likes are stored in the database, with frequently accessed data cached for performance.

Flow:

1. The user logs in to the social media application via the website or mobile app.

2. The frontend requests the user's feed from the backend.

3. The backend retrieves posts from the database and caches frequently accessed posts in Redis.

4. The backend sends the feed data to the frontend to display to the user.

5. The user creates a new post, which the backend processes and stores in the database.

6. The user's friends interact with the post (like, comment), and the backend updates the database accordingly.
Flowchart Maker & Online Diagram Software
draw.io is free online diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams
 