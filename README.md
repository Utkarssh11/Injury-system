# Injury Tracking System

The Injury Tracking System is a web application designed for organizations, such as the police, to efficiently record and monitor injury reports submitted by individuals. This system offers a user-friendly interface with various features, including report management, body map image annotation, injury details, and user authentication.

## Features

### Report Management

- **Create, View, Update, and Delete Reports**: Users can easily create new injury reports, view existing ones, update report details, and delete reports when necessary.

- **Injury Report Information**: Each injury report includes the following information:
  - Name of the reporter
  - Date and time of the injury

### Body Map Image Annotation

- **Body Map Annotation**: Users can encircle different areas of injury on a body map image. The system automatically labels each circled area with a unique identifier (e.g., 1, 2, etc.).

- **Injury Details**: For each encircled area, users can provide detailed information about the injuries, such as type, severity, or any relevant notes.

### List of Reports

- **List/Table of Injury Reports**: Users can view a list or table displaying all the reported injuries. The list includes the following information for each report:
  - Name of the reporter
  - Date and time of the injury
  - Date and time of the report

- **Sorting**: Users can sort the list by any of the fields mentioned above to easily find and categorize reports.

- **Searching by Name**: A search functionality allows users to find specific reports by the name of the reporter.

- **Filtering**: Users can filter reports based on the start and end dates of the injury and the date and time of the report.

### User Authentication

- **User Registration**: Users can register for an account within the app using a username and password. Additionally, options for Google login and email login are available.

- **Authentication using Auth0**: User authentication is implemented using Auth0, a secure and widely-used identity management platform.

- **User Account Management**: Registered users can log in and log out of their accounts and access a history of their submitted injury reports.

### UI/UX

- **User-Friendly Interface**: The application features a clean and user-friendly interface built using Grommet or Ant design libraries. The design is responsive and optimized for both desktop and mobile devices.

- **Visual Appeal**: The interface is visually appealing, making it easy for users to navigate and interact with the application.

---
