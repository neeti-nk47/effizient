#EFFIZIENT

Prerequisites:  <br />  
Node.js and npm installed on your machine.  <br />  
 <br />
Setup:  <br />
1.BACKEND-  <br />
&ensp; Clone the repository to your local machine using the following command: git clone https://github.com/neeti-nk47/effizient.git  <br />
&ensp; Navigate to the backend directory: cd backend  <br />
&ensp; Create a .env file in the backend directory and configure the following environment variables:  <br />
&emsp; PORT= 3000  <br />
&emsp; OPENAI_API_KEY = "Your OpenAI API key"   <br />
&emsp; MONGODB_URL = " URI for your MongoDB database."  <br />
&emsp; EMAIL="Your Email for SMTP"  <br />
&emsp; PASSWORD="Your password of Email"  <br />
&ensp; Install dependencies using npm: npm install  <br />
&ensp; Start the backend server: npm start  <br />
&ensp; The backend will be accessible, and it's ready to receive user data and send mail for SOP generation.  <br />
2. FRONTEND-   <br />
&ensp; Navigate to the frontend directory: cd frontend   <br />
&ensp; Install dependencies using npm: npm install   <br />
&ensp; Start the frontend server: npm run dev   <br />
&ensp; The frontend will be accessible at http://localhost:5173   <br />
 <br /> 
Overview:  <br />
&ensp; Access the web-based UI for the SOP Generation Tool    <br />
&ensp; Fill out the form with the required information.   <br />
&ensp; Upon submission, the data will be sent to the backend for processing.   <br />
&ensp; An email will be generated and sent to the provided email address with a personalised Statement of Purpose (SOP) and all the information entered in the form.   <br />
 
