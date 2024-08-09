**VoIP Dashboard**
This project is a VoIP Dashboard built with Vue.js and Node.js, leveraging Twilio's API for making outbound calls.

**Installation**
Clone the repository: git clone https://github.com/Steveuseful/voip-dashboard.git and cd voip-dashboard.

Install the dependencies for the frontend: npm install.

Navigate to the backend directory and install the dependencies: cd backend and npm install.

**Usage**
Running the Frontend
To start the frontend development server, run: npm run serve. The server will start on http://localhost:8080.

**Running the Backend**
To start the backend server, run: node make_call.js. The backend server will start on http://localhost:3000.

**Configuration**
Create a .env file in the backend directory with your Twilio credentials:

**Makefile:**
TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
Replace your_account_sid and your_auth_token with your actual Twilio Account SID and Auth Token.

**Scripts**
Frontend Scripts:

npm run serve: Starts the frontend development server.
npm run build: Builds the frontend for production.
npm run lint: Lints the frontend code.

**Backend Scripts:**

node make_call.js: Starts the backend server and makes a call using Twilio's API.

**License**
This project is licensed under the MIT License. See the LICENSE file for more information.

