Expense Tracker
Project Description
My project is an Expense Tracker website. It helps users record their expenses and check their spending. Users can add, view, update, and delete transactions.
Technologies Used
* HTML
* CSS
* JavaScript
* Node.js
* Express.js
* MySQL
* XAMPP
* Visual Studio Code
Main Features
* Add expenses
* View all expenses
* Update expenses
* Delete expenses
* View the financial summary
* Validate user input
* Refresh totals after transaction changes
Project Structure
* public/ - Contains the HTML, CSS, and JavaScript files.
* src/server.js - Starts the server.
* src/config/database.js - Handles the database connection.
* src/controllers/expenseController.js - Handles expense operations.
* src/middleware/logger.js - Logs requests.
* src/middleware/validateExpense.js - Checks expense input.
* src/routes/expenseRoutes.js - Contains the API routes.
API Routes
Method	Endpoint	Purpose
GET	/api/expenses	View all expenses
POST	/api/expenses	Add an expense
GET	/api/expenses/summary	View the financial summary
PUT	/api/expenses/:id	Update an expense
DELETE	/api/expenses/:id	Delete an expense
How to Run the Project
1. Install Node.js and XAMPP.
2. Start MySQL using XAMPP.
3. Set up the database and the .env file.
4. Open the project folder in VS Code.
5. Install the required packages using npm install.
6. Start the server using node src/server.js.
7. Open http://localhost:3000 in your browser.
Current Progress
The server setup, API routes, frontend files, and middleware have been created. The features still need to be tested to make sure they work properly
