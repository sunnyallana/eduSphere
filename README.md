# eduSphere - Online Course App

eduSphere is a Django-based web application designed for managing online courses. It utilizes SQLite as the database backend.

## Features

- User authentication: Allow users to create accounts, log in, and manage their profiles.
- Course management: Create, update, and delete courses with details such as title, description, and content.
- Enrollment: Users can enroll in courses and track their progress.

## Technologies Used

- Django: The web framework used to develop the application.
- SQLite: The database management system for storing application data.

## Prerequisites

#### Before running the application, make sure you have the following installed:

- Python 3.x
- Django

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/eduSphere.git
   ```
   
2. Navigate to the project directory:

  ```bash
  cd eduSphere
  ```

3. Install dependencies:

  ```bash
  pip install -r requirements.txt
  ```

4. Apply migrations:

  ```bash
  python manage.py migrate
  ```

5. Run the development server:

  ```bash
  python manage.py runserver
  ```

#### The application will be accessible at http://127.0.0.1:8000/.

## Usage

1. Create a superuser to manage the Django admin interface:

  ```bash
  python manage.py createsuperuser
  ```

#### Access the admin interface at http://127.0.0.1:8000/admin/ and log in with the superuser credentials.

2. Create courses, manage users, and perform administrative tasks through the Django admin.

#### Visit the main application at http://127.0.0.1:8000/ to explore and use the online course features.

## Contributing

#### If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: git checkout -b feature-name.
3. Commit your changes: git commit -m 'Add new feature'.
4. Push the branch to your fork: git push origin feature-name.
5. Create a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
