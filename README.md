# InteractWeb

InteractWeb is a project that enables interaction between the physical world and a web application. It allows you to control and monitor the web application using physical devices connected to an Arduino.

## Project Overview

The project consists of two main components:

1. Backend: Built with Django, the backend handles the web application's logic, database management, and communication with the Arduino.

2. Frontend: Built with Svelte, the frontend provides the user interface for interacting with the web application and displays real-time data from the Arduino.

## Prerequisites

To set up and run the InteractWeb project, you'll need the following:

- Python (version 3.6 or higher) installed on your machine.
- Arduino board with the necessary components and sensors.
- Basic knowledge of Django, Svelte, and web development.

## Installation

Follow these steps to install and set up the project:

1. Clone the repository:

   ```bash
   https://github.com/NCRT-DaZZle/InteractWeb
   ```

2. Navigate to the project directory:

   ```bash
   cd InteractWeb
   ```

3. Install the required Python packages. Assuming you have pip installed, run:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up the Django backend:

   - Migrate the database:

     ```bash
     python manage.py migrate
     ```

   - Create a superuser (optional):

     ```bash
     python manage.py createsuperuser
     ```

5. Set up the Svelte frontend:

   - Navigate to the `frontend` directory:

     ```bash
     cd frontend
     ```

   - Install the dependencies:

     ```bash
     npm install
     ```

6. Connect the Arduino to your machine and upload the Arduino code located in the `arduino` directory to your Arduino board.

## Usage

To run the project, follow these steps:

1. Start the Django backend server:

   ```bash
   python manage.py runserver
   ```

2. Start the Svelte frontend development server:

   - Navigate to the `frontend` directory:

     ```bash
     cd frontend
     ```

   - Start the development server:

     ```bash
     npm run dev
     ```

3. Access the web application by visiting `http://localhost:5000` in your web browser.

4. Interact with the physical devices connected to your Arduino, and observe the real-time data and functionality in the web application.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please [create an issue](https://github.com/NCRT-DaZZle/InteractWeb/issues) or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).