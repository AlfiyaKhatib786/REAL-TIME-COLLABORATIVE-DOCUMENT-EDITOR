# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ALFIYA KHATIB

*INTERN ID*: CT06DG2534

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

This project is a real-time collaborative editor application built using React for the frontend and Node.js for the backend. It demonstrates how modern JavaScript technologies can be combined to create a responsive, interactive, and real-time editing experience, similar to popular tools like Google Docs or online code editors. The frontend is set up using Create React App, and the backend is managed using Express.js and optionally Socket.IO for real-time bi-directional communication.

The frontend code resides in the client directory and is structured using the standard React conventions. The main entry point is index.js, which uses ReactDOM.createRoot() to render the <App /> component into the HTML element with the ID root. This setup ensures that the app follows the modern rendering approach using React’s strict mode for highlighting potential problems. Supporting files like App.js, App.css, and various assets are organized within the src directory, making the codebase clean and modular. The design is styled using custom CSS or utility libraries, and the project supports hot-reloading during development.

To run the frontend, the user navigates to the client directory in the terminal and runs the command npm start, which launches the development server on port 3000 by default. If the port is already in use, the app offers to run on the next available port or can be configured to run on a different port via a .env file or terminal environment variable. This flexibility is useful for avoiding port conflicts when running multiple services simultaneously.

On the backend side, the root directory (collab-editor/) contains the server-side logic in server.js, typically running on port 5000. This backend might be used to manage user sessions, broadcast real-time updates using WebSockets, and serve static files or APIs. The backend is started with the command node server.js or using nodemon for live-reloading during development. Dependencies are managed using package.json, which includes libraries like express and socket.io, making it easy to install everything with npm install.

One key feature of this setup is the ability to enable real-time collaboration, where multiple users can see updates to a document or interface simultaneously. While the actual logic for this may vary depending on your implementation, common approaches involve broadcasting state changes using Socket.IO or polling APIs from the React frontend.

This project provides an excellent foundation for understanding how to build and manage full-stack applications. It highlights the developer's ability to work with multiple tools, manage frontend-backend integration, and troubleshoot port configurations. During development, the user may encounter Git or environment-related warnings, such as "unsafe repository," which can be resolved using Git commands or administrative privileges.

#output

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d781922-5c28-4650-8ea5-16ab4af7c7a9" />

