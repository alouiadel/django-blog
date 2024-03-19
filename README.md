# Django Blog Project

This is a Django blog project developed to showcase my skills.

## Prerequisites

Before running the project, make sure you have the following installed:

- Python 3.x
- Django
- Virtual environment (optional but recommended)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/alouiadel/django-blog.git
    ```

2. Navigate to the project directory:

    ```bash
    cd django-blog
    ```

3. Create and activate a virtual environment (optional):

    ```bash
    python -m venv django-blog
    source django-blog/bin/activate
    ```

4. Install the project dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5. Run database migrations:

    ```bash
    python manage.py migrate
    ```

6. Start the development server:

    ```bash
    python manage.py runserver
    ```

7. Open your browser and visit `http://localhost:8000` to see the blog.

## Features

- User authentication
- Create, read, update, and delete blog posts
- Commenting system
- Search functionality

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
