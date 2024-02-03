# Setting up Virtual Environment for Django Project

## Prerequisites
- [Python](https://www.python.org/downloads/) installed
- [pip](https://pip.pypa.io/en/stable/installation/) installed

## Steps to Set Up Virtual Environment and Run Django Project

1. Open the command line terminal and navigate to the desired directory for your Django project, for example, the Desktop:

    ```bash
    cd Desktop
    ```

2. If you haven't installed `virtualenv` yet, install it using `pip`:

    ```bash
    pip install virtualenv
    ```

3. Create a virtual environment. Replace `(name the folder)` with your desired virtual environment folder name:

    ```bash
    virtualenv (name the folder)
    ```

4. Activate the virtual environment. On macOS/Linux:

    ```bash
    source (name the folder)/bin/activate
    ```

    On Windows:

    ```bash
    .\venv\Scripts\activate
    ```

5. Install Django inside the virtual environment:

    ```bash
    pip install django
    ```

6. Create a new Django project. Replace `(name of the project)` with your desired project name:

    ```bash
    django-admin startproject (name of the project)
    ```

7. Navigate to the project directory:

    ```bash
    cd (name of the project)
    ```

8. Start the Django development server:

    ```bash
    python manage.py runserver
    ```

   The development server will run, and you can access your Django project at [http://localhost:8000/](http://localhost:8000/).

9. To stop the server, press `Ctrl+C` in the terminal.

10. When you are done working on your project, deactivate the virtual environment:

    ```bash
    deactivate
    ```

That's it! You have set up a virtual environment and started your Django project. Happy coding!
