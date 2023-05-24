# API Documentation

This is the documentation for the API endpoints provided by the application. The API allows users to manage users, orders, and products.

## Getting Started

### Prerequisites

- Python 3.7 or above
- MongoDB

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your/repository.git

Install the required dependencies:

pip install -r requirements.txt


Update the MongoDB URI in the code:

Open the app.py file and locate the following line:

uri = "mongodb+srv://isbravo:ktLGzXsKDnufOr3g@cluster1.kabn980.mongodb.net/?retryWrites=true&w=majority"

Replace the uri variable value with your own MongoDB connection URI.

Running the Application
To run the application, execute the following command:

python app.py


The application will start running on http://localhost:5000.

Endpoints
Users
Create a User
URL: /api/v1/users
Method: POST
Request Body:

{
  "username": "jase",
  "password": "111112"
}

{
  "status": "Usuario creado con éxito"
}



User Login
URL: /api/v1/login
Method: POST
Request Body:



Get All Users
URL: /api/v1/usersAll
Method: GET
Response:
Success: 200 OK
