File Management App

This is a simple file management application built using Node.js, Express.js, and EJS for templating. It allows users to create, view, edit, and delete text files through a web-based interface.

Features

Create new text files with custom content

View the list of available files

Read the contents of a selected file

Edit filenames

Delete files

Technologies Used

Node.js

Express.js

EJS (Embedded JavaScript)

Tailwind CSS

File System (fs) module

Installation

Clone the repository:

git clone https://github.com/your-repo.git

Navigate to the project directory:

cd file-management-app

Install dependencies:

npm install

Usage

Start the server:

node app.js

Open a browser and go to:

http://localhost:3000

Routes

GET / - Displays the list of available files

POST /create - Creates a new file with the given title and content

GET /files/:filename - Displays the contents of a specific file

GET /edit/:filename - Shows the edit page for renaming a file

POST /edit - Updates the filename

POST /delete/:filename - Deletes a file

Folder Structure

project-root/
│── public/            # Static files (CSS, JS, images)
│── views/             # EJS templates
│── files/             # Stored text files
│── app.js             # Main server file
│── package.json       # Project metadata and dependencies

Dependencies

express

ejs

fs (built-in Node.js module)

path (built-in Node.js module)

License

This project is open-source and available under the MIT License.

