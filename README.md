# Blog API

This is a Django-based Blog API for creating, reading, updating, and deleting blog posts. The API supports token-based authentication and includes pagination, post-author assignment, and more features.

## Features

- **Create Post**: Authenticated users can create blog posts.
- **List Posts**: Anyone can view the list of blog posts.
- **Update Post**: Only the post's author can update it.
- **Delete Post**: Only the post's author can delete it.
- **Pagination**: Supports pagination of posts.
- **Authentication**: Token-based authentication (JWT).

## Technologies Used

- **Django**: The web framework used to build the API.
- **Django REST Framework**: Used to build the API endpoints.
- **PostgreSQL**: The database used for storing blog posts.
- **Supabase**: Database service for PostgreSQL.
- **Railway**: Hosting service for the production environment.

## Installation

### Requirements

- Python 3.9+
- PostgreSQL
- Django 4.x
- Django REST Framework
- djangorestframework-simplejwt (for JWT authentication)
