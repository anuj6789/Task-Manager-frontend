# Task Manager Frontend

A clean, dynamic, and responsive user interface for the Task Manager application. This project was built with vanilla JavaScript, HTML, and Tailwind CSS to create a modern single-page application experience.

![App Screenshot](https://i.imgur.com/your-screenshot-url.jpg)
*(Suggestion: Take a screenshot of your running frontend, upload it to a site like Imgur, and paste the link here)*

## Features

-   **Dynamic UI:** Seamlessly switch between Login and Registration forms.
-   **Full Task Management:** Create, view, update status, and delete tasks without ever reloading the page.
-   **Local Session Persistence:** Uses `localStorage` to keep the user logged in even after closing the browser tab.
-   **Visually Appealing:** Features a dark theme with a dynamic, animated "rain" background effect.

## Tech Stack

-   **HTML5**
-   **Tailwind CSS** (for styling)
-   **Vanilla JavaScript** (for all logic and API communication)

## Setup and Configuration

This is a static frontend project and does not require a build step.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/task-manager-frontend.git](https://github.com/your-username/task-manager-frontend.git)
    ```
2.  **Configure the API URL:**
    Open the `index.html` file and find the following JavaScript variable:
    ```javascript
    const API_BASE_URL = 'https://localhost:7213';
    ```
    Change the URL to match the address where your backend API is running.

3.  **Run the application:**
    The easiest way to run this is with the "Live Server" extension in Visual Studio Code.
    -   Install the **Live Server** extension.
    -   Right-click the `index.html` file and select "Open with Live Server".

4.  **Make sure the backend API is running** for the frontend to be able to fetch and manage data.

