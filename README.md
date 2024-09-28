
# Django Blog Project

This is a simple blog application built with Django. The application allows users to create and edit blog posts, display posts to users, assign categories to posts, and allow users to comment on posts.

## Features

- Set up a new Django project
- Create and edit blog posts
- Display posts to the user
- Assign categories to posts
- Allow users to comment on posts

## Prerequisites

- Python 3.x
- Django 3.x or higher

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/django-blog.git
   cd django-blog

2. **Create a virtual environment**:
   ```sh
   python3 -m venv venv
    ```

    MACOS:
    ```sh
    source venv/bin/activate
    ```
    WIN:
    ```sh
    .\venv\Scripts\activate
    ```
    deactivate environment
    ```sh
    deactivate
    ```
3. **Install dependencies**:
    ```sh
    python -m pip install Django
    ```
4. **Apply migrations**:
   ```sh
   python manage.py migrate
   ```
5. **Run the development server**:
    ```sh
    python manage.py runserver
    ```
6.  **Access the application**: 
   Open your web browser and go to `http://127.0.0.1:8000/`.
## Usage

### Creating and Editing Blog Posts

1.  Log in to the admin site at `http://127.0.0.1:8000/admin/`.
2.  Navigate to the "Posts" section.
3.  Add a new post or edit an existing one.

### Displaying Posts to Users

-   Users can view the list of blog posts on the homepage.
-   Clicking on a post title will take the user to the post detail page.

### Assigning Categories to Posts

1.  In the admin site, navigate to the "Categories" section.
2.  Add new categories as needed.
3.  When creating or editing a post, assign one or more categories to the post.

### Allowing Users to Comment on Posts

-   Users can add comments to posts from the post detail page.
-   Comments will be displayed below the post content.
