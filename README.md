
A Quora-like Q&A platform backend built , providing RESTful API endpoints to create, read, update, and delete questions and answers. This backend serves a frontend built with EJS templates, HTML, CSS, and JavaScript.

🚀 Features
Question & Answer Management: CRUD operations on questions and answers.

RESTful API: Well-structured endpoints following REST best practices.

Server-Side Rendering: Uses EJS templates for dynamic page rendering.
Exception Handling: Custom exception responses for better error management.

🛠️ Tech Stack
Layer	Technology
Frontend	EJS, HTML, CSS, JavaScript
Backend	NodeJs

📦 Installation & Setup
Prerequisites

Node.js & npm 

Steps to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/SameerSinha1234567/restfulapi.git
cd restfulapi


Update database connection details in src/main/resources/application.properties:

Access the app

Open your browser at http://localhost:8080.

The server renders pages using EJS templates; API endpoints are accessible for integration.

⚙️ Usage
Navigate to the homepage to view existing questions.

Create, update, or delete questions and answers via UI forms.

Backend REST APIs available for all CRUD operations on questions and answers:

HTTP Method	Endpoint	Description
GET	/questions	List all questions
GET	/questions/{id}	Get question details
POST	/questions	Create new question
PUT	/questions/{id}	Update a question
DELETE	/questions/{id}	Delete a question
GET	/questions/{id}/answers	List answers for question
POST	/questions/{id}/answers	Add answer to question
PUT	/answers/{id}	Update an answer
DELETE	/answers/{id}	Delete an answer
