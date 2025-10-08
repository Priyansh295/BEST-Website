# BEST Labs Website

https://best-ai-labs.pages.dev/
This project is a web-based platform for students to interact with and run code from their lab assignments. It provides a user-friendly interface to view lab materials, write and execute code in different programming languages, and see the output in real-time.

## Project Description

The BEST Labs Website is designed to supplement traditional lab manuals by offering an interactive online environment. Students can select their unit and lab, view the provided code, and run it directly in the browser. The backend server supports code execution in Python, C++, and JavaScript.

## Tech Stack

### Frontend

*   **React.js**: A JavaScript library for building user interfaces.
*   **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
*   **Monaco Editor**: A code editor that powers VS Code, providing a rich code editing experience.
*   **React Syntax Highlighter**: A component for syntax highlighting code snippets.

### Backend

*   **Node.js**: A JavaScript runtime environment for building server-side applications.
*   **Express.js**: A minimal and flexible Node.js web application framework.
*   **CORS**: A Node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options.
*   **Body Parser**: A Node.js body parsing middleware.

## Features

*   **Unit and Lab Selection**: Students can easily navigate through different units and labs.
*   **Interactive Code Editor**: An in-browser code editor with syntax highlighting and a familiar development environment.
*   **Multi-language Support**: The platform supports running code in Python, C++, and JavaScript.
*   **Real-time Code Execution**: Code is executed on the server, and the output is displayed to the user in real-time.
*   **Responsive Design**: The user interface is designed to work on different screen sizes.

## Getting Started

### Prerequisites

*   Node.js and npm installed on your machine.
*   Python, G++ (for C++), and Node (for JavaScript) installed and available in your system's PATH.

### Installation

1.  Clone the repository:
    ```sh
    git clone https://github.com/your-username/best-website.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd best-website/bestlabs-main/ta-labs-website
    ```
3.  Install the dependencies:
    ```sh
    npm install
    ```

### Running the Application

1.  Start the backend server:
    ```sh
    node server.js
    ```
2.  In a new terminal, start the frontend development server:
    ```sh
    npm start
    ```
3.  Open your browser and navigate to `http://localhost:3000` to see the application.

## Project Structure

```
ta-labs-website/
├── public/               # Static assets and HTML template
├── src/                  # React application source code
│   ├── components/       # React components
│   ├── data/             # Lab data and content
│   └── ...
├── server.js             # Express backend server
├── package.json          # Project dependencies and scripts
└── ...
```
