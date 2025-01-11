Blogging API
A Blogging API built using Django and Django REST Framework (DRF), allowing users to register, authenticate , create and manage blog posts.

Features
User Authentication: Register and log in.
Blog Post Management: Create, view, update, and delete blog posts.
Permissions: Secure endpoints .
Technologies Used
Django

sqlite (for production)

Heroku (for deployment)

python manage.py runserver
API Endpoints
POST /api/token/: Obtain JWT access and refresh tokens.
POST /api/token/refresh/: Refresh your JWT token.
GET /posts/: List all blog posts.
POST /posts/: Create a new blog post.
GET /posts/{id}/: Retrieve a single blog post by ID.
PUT /posts/{id}/: Update a blog post by ID.
DELETE /posts/{id}/: Delete a blog post by ID.
GET /comments/: List all comments.
POST /comments/: Create a new comment on a post.
Deployment
The API will be  deployed on Heroku.
