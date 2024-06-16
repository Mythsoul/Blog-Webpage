# Blog Application
This is a simple blog application built with Node.js, Express.js, and Axios, allowing users to create, read, update, and delete blog posts.

# Features
View all existing blog posts.
View a specific blog post by ID.
Create new blog posts.
Edit existing blog posts.
Delete blog posts.

# Technologies Used
Node.js

Express.js

Axios

Ejs/CSS (for front-end templates)

# Installation

1 . Clone the repository:

``` bash
git clone https://github.com/Mythsoul/Blog-Webpage.git  

```
2 . Open project folder
```bash
cd Blog-Webpage 
```

3 . Install dependencies:

```bash
npm install
```

4 . Start the Api & Backend  server:

```bash
 nodemon server.js 
 nodemon index.js
```

# Usage
View All Posts: Navigate to http://localhost:3000 to view all existing blog posts.

Create New Post: Click on the "New Post" link to create a new blog post.

Edit Post: Click on the "Edit" link next to each post to edit its content.

Delete Post: Click on the "Delete" link to delete a post.

# API Endpoints
GET /posts: Retrieves all blog posts.

GET /posts/:id: Retrieves a specific blog post by ID.

POST /posts: Creates a new blog post.

PATCH /posts/:id: Updates a specific blog post by ID.

DELETE /posts/:id: Deletes a specific blog post by ID.

# Contributing
Contributions are welcome! If you have any suggestions, improvements, or issues, please feel free to open an issue or create a pull request.