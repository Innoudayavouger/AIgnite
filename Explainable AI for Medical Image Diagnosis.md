2. Explainable AI for Medical Image Diagnosis


Description: Develop a medical imaging AI model capable of identifying diseases from X-rays, MRIs, or CT scans. The twist: the model must provide detailed, human-understandable explanations for its predictions to ensure transparency and trust.




User Management
Database Setup: Ensure the Users table is created in the database when the backend server starts. If the table already exists, no action is needed.

User Registration: Create an API to register users. During registration:
Encrypt the user's password before storing it in the database (do not store plaintext passwords).
Ensure the username and email fields are unique.

User Login: Develop an API for user login. Validate the provided username and password, and generate a JWT token upon successful authentication.

Update User Details: Build an API to update user information. The request must include a valid JWT in the headers to authenticate the user before making updates.

Retrieve User Details: Create an API to fetch user details. The API should validate the JWT token from the headers and only return details for the authenticated user.Hints

Database Choice: You can choose any database for this task. However, MySQL or PostgreSQL is preferred.

Backend Technology: Feel free to select any backend technologies or frameworks that you are comfortable with or prefer.

Database Schema: You have the flexibility to finalize the database columns based on the needs of your project.

API Payloads: The structure of the request payloads or JSON objects for API requests can be defined by you.

The backend implementation should be the main focus. Once the backend is completed, please notify us.
