# AirBnB Clone - MySQL

This project is an AirBnB clone developed using MySQL as the database storage. It is part of the Enterprise Web Development curriculum and is implemented by a team of two people: Pius Pius and Henriette Tuombe.

The main objective of this project is to create a fully functional AirBnB clone that supports user registration, property listing, property booking, and other essential features. The project utilizes MySQL as the database management system to store and retrieve data.

## Getting Started

To get started with the project, follow the instructions below:

1. Clone the project repository from GitHub.
2. Set up a MySQL database and configure the necessary environment variables.
3. Install the required dependencies.
4. Run the application and access it through a web browser.

## Prerequisites

Before running the project, make sure you have the following prerequisites installed:

- Python 3.8 or higher
- MySQL database management system
- Pip package manager

## Installation

Follow the steps below to install and configure the project:

1. Clone the project repository:

   ````bash
   git clone https://github.com/henriettetuombe/alu-AirBnB_clone_v2.git
   ```

2. Create a virtual environment (optional but recommended):

   ````bash
   python3 -m venv env
   source env/bin/activate
   ```

3. Install the required dependencies:

   ````bash
   pip install -r requirements.txt
   ```

4. Configure the environment variables:

   Create a `.env` file in the project root directory and set the following variables:


5. Create the MySQL database:

   Use the MySQL command-line tool or a MySQL GUI to create the database specified in the `HBNB_MYSQL_DB` environment variable.

6. Run the application:

   ````bash
   python run.py
   ```

   The application will start running on `http://localhost:5000`.

## Usage

The AirBnB clone provides a web interface for users to perform various actions, such as:

- User registration and authentication
- Property listing and search
- Property booking and reservation management
- User profile management

Access the application through a web browser by navigating to `http://localhost:5000`.

## Testing

To run the project's unit tests, execute the following command:

```bash
python -m unittest discover -v
```

The tests will be executed, and the results will be displayed in the console.

## Contributors

- Pius Ezekiel Adakole (PiusEzekiel)
- Henriette Tuombe (henriettetuombe)
