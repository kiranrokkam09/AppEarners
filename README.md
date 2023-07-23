# Django REST API for AppEarners

AppEarners is a web application that allows administrators to add Android apps and assign points to users for downloading those apps. Users can sign up, log in, view their profiles, check their earned points, and submit screenshots as proof of completing tasks.

## Features

- **Admin Facing:**
  - Add Android apps and assign points for downloads.
  - Custom admin panel for managing apps and points (non-default Django admin).
  - Exposed REST API endpoints with proper permissions, authentication, and documentation.

- **User Facing:**
  - User registration and login with secure authentication.
  - User profile page displaying their name, earned points, and completed tasks.
  - Option to upload a screenshot as proof for task completion (drag and drop feature).
  - View list of apps added by the admin and their corresponding points.

## Technologies Used

- Django: Backend framework for handling API, authentication, and database operations.
- Django REST Framework (DRF): To create the RESTful API.
- SQLite: As the relational database to store app and user data.

## Getting Started

### Prerequisites

- Python 3.x

### Setting Up the Project

1. Clone the repository:
   ```
   git clone https://github.com/kiranrokkam09/AppEarners.git
   cd AppEarners
   ```

2. Create a virtual environment and activate it:
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install Python dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```
   python manage.py migrate
   ```

5. Create a superuser for accessing the admin panel:
   ```
   python manage.py createsuperuser
   ```

6. Run the Django development server:
   ```
   python manage.py runserver
   ```


## Contributing

Contributions are welcome! If you find any issues or have suggestions, please create an issue or submit a pull request.


## Contact

For any questions or inquiries, please contact `[kiran.rokkam456@gamil.com]`.
