
**1 Run Your Application**

Start MongoDB:
If you haven't already, start your MongoDB server.

Run Your Application:
In Command Prompt or PowerShell, navigate to your project directory (todo-api) and run:

**node index.js**
This will start your Express server on http://localhost:3000 (or another port if you specified in .env).

**2 Test Your API**

You can test your API using tools like Postman or by writing unit tests.

Using Postman:

Create requests (GET, POST, PATCH, DELETE) to http://localhost:3000/todos.
Set headers and body as required.
Send requests and verify responses.

Writing Unit Tests:

Use a testing framework like Mocha and an assertion library like Chai.
Write test cases for each route and expected behavior.
Mock the MongoDB connection and operations for testing purposes.
