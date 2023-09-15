# Employee Management System

## Overview

The Employee Management System is a web application built with React, Java, Spring Boot, Axios, MongoDB, and Material UI. It provides basic CRUD (Create, Read, Update, Delete) operations for managing employee records. This system allows you to easily add, update, delete, and reset employee information, making employee management efficient and streamlined.

## Features

- Create new employee records with essential details.
- Read and display employee information in a user-friendly interface.
- Update existing employee records with the latest information.
- Delete employee records when they are no longer needed.
- Reset employee data to default values if needed.

## Tech Stack

- **Frontend**: React
- **Backend**: Java, Spring Boot
- **Database**: MongoDB
- **HTTP Client**: Axios
- **UI Framework**: Material UI

## Getting Started

Follow these instructions to set up and run the Employee Management System locally on your machine.

### Prerequisites

- Node.js and npm installed.
- Java Development Kit (JDK) installed.
- MongoDB installed and running.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Employee-Management-System.git
   ```

2. Change directory to the frontend folder and install frontend dependencies:

   ```bash
   cd Employee-Management-System/frontend
   npm install
   ```

3. Change directory to the backend folder and install backend dependencies:

   ```bash
   cd ../backend
   # Use your preferred package manager for Java projects (e.g., Maven or Gradle)
   # For Maven:
   mvn clean install
   ```

### Configuration

1. Configure the MongoDB connection by editing the `application.properties` file in the `backend/src/main/resources` directory.

2. Make any necessary adjustments to the frontend configuration in the `frontend/src/config.js` file.

### Running the Application

1. Start the backend server:

   ```bash
   cd ../backend
   java -jar target/employee-management-system.jar
   ```

2. Start the frontend development server:

   ```bash
   cd ../frontend
   npm start
   ```

3. Access the application in your web browser at `http://localhost:3000`.

## Usage

1. Launch the application and navigate to the homepage.

2. Use the provided interface to perform CRUD operations on employee records.

3. Enjoy streamlined employee management!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to the open-source community for providing the tools and libraries used in this project.
- Special thanks to our contributors for their valuable contributions.

## Contact

For any questions or suggestions, please feel free to contact us at [your-email@example.com](mailto:your-email@example.com).

Happy Employee Management! 🚀
