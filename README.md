#EFFIZIENT

Prerequisites:
Node.js and npm installed on your machine.

Setup:
1.BACKEND-
Clone the repository to your local machine using the following command: git clone https://github.com/neeti-nk47/effizient.git
Navigate to the backend directory: cd backend
Create a .env file in the backend directory and configure the following environment variables:
PORT= 3000
OPENAI_API_KEY = "Your OpenAI API key"
MONGODB_URL = " URI for your MongoDB database."
EMAIL="Your Email for SMTP"
PASSWORD="Your password of Email"
Install dependencies using npm: npm install
Start the backend server: npm start
The backend will be accessible, and it's ready to receive user data and send mail for SOP generation.
2. FRONTEND-
Navigate to the frontend directory: cd frontend
Install dependencies using npm: npm install
Start the frontend server: npm run dev
The frontend will be accessible at http://localhost:5173 

Overview:
Access the web-based UI for the SOP Generation Tool 
Fill out the form with the required information.
Upon submission, the data will be sent to the backend for processing.
An email will be generated and sent to the provided email address with a personalised Statement of Purpose (SOP) and all the information entered in the form.
 
