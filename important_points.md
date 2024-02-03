# Django URLs and Views

## 1. URL Routing in Django
   - Django uses a `urls.py` file to manage URL routing.
   - The `urls.py` file contains a list of paths, each associated with a specific function.
   - URLs are patterns that trigger functions when matched.

## 2. Creating Views
   - Views are functions that handle HTTP requests and return responses.
   - Views are associated with specific URL patterns in `urls.py`.
   - Views can take a `request` parameter, representing the HTTP request.

## 3. Dynamic URLs
   - Dynamic URLs are created using angle brackets in the `urls.py`.
   - Parameters can be added to the URL pattern, passed to the associated view function.
   - Example: `projects/<str:project_id>/`

## 4. Organizing Views and URLs
   - It's recommended to separate views and URLs into different files for better organization.
   - Create a `views.py` file in the app to store views.
   - Create a separate `urls.py` file to manage URLs within the app.

## 5. Using `include` in `urls.py`
   - The `include` function is used to include URLs from another file.
   - Helps organize and modularize the project.
   - Example: `include('app_name.urls')`

## 6. URL Naming
   - Naming URLs with meaningful names using the `name` parameter.
   - Helps in referencing URLs in templates or other parts of the code.
