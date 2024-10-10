## MongoDB Flask App
# Overview
This project is a simple web application built using Flask, a micro web framework for Python. The application allows users to manage a list of "todo" items, where each todo item has associated content and a degree of importance (either "Important" or "Unimportant"). The todo items are stored in a MongoDB database.

# Features
Add Todo Items: Users can submit new todo items through a simple form, specifying the content and importance.
View Todo List: All todo items stored in the database are displayed on the main page, showing their content and importance level.
Delete Todo Items: Each todo item can be deleted by submitting a confirmation form, removing it from the database.

# Technologies Used
Flask: The main framework used to create the web application.
MongoDB: A NoSQL database for storing todo items.
HTML/CSS: Used for structuring and styling the web application.
Jinja2: A templating engine for rendering dynamic content in HTML.

pip install flask pymongo

git clone <repository-url>
cd <repository-directory>

python app.py


# Usage
To add a new todo item, enter the content in the text input field, select the degree of importance, and click the "Submit" button.
The todo items will be displayed below the form, and you can delete any item by clicking the "delete todo" button next to it.



