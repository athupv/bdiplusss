# Task List App


## Description



This application is a Task List that allows users to create, read, update, and delete tasks (CRUD). It is built with Django Rest Framework on the backend and React with Vite on the frontend.

### Features

 -Create a new task
-Read all tasks
 -Update an existing task
-Delete a task



 Requirements

- Python 3.x
- Node.js
- npm o yarn / npm or yarn

 Setup and Execution

### Backend (Django)



 / Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  ` / On Windows use `venv\Scripts\activate`
    ```

/ Install the backend dependencies:
    ```sh
    pip install -r requirements.txt
    ```

/ Apply the migrations:
    ```sh
    python manage.py migrate
    ```

 / Start the Django development server:
    ```sh
    python manage.py runserver
    ```

### Frontend (React con Vite / React with Vite)

/ Open a new terminal and navigate to the frontend directory:
    ```sh
    cd client
    ```

 / Install the frontend dependencies:
    ```sh
    npm install  `yarn` Or use `yarn` if you prefer
    ```

/ Start the Vite development server:
    ```sh
    npm run dev  # O `yarn dev`
    ```

 / Usage



Once both servers are running, open your browser and navigate to `http://localhost:5173` to interact with the Task List application.

## API


The application's API follows REST standards and can be used to perform CRUD operations on tasks.

### Endpoints

- `GET /tasks/api/v1/tasks/` -  / Get all tasks
- `POST /tasks/api/v1/tasks/` -  / Create a new task
- `GET /tasks/api/v1/tasks/:id/` -  / Get a specific task
- `PUT /tasks/api/v1/tasks/:id/` -  / Update an existing task
- `DELETE /tasks/api/v1/tasks/:id/` - / Delete a task




