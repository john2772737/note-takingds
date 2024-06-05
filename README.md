MAIN OBJECTIVE
SwiftNotes is a web application dedicated to note/document-taking and 
collaboration. Its primary goal is to offer users an ideal platform for creating, 
editing, and sharing notes in real-time. The focus of the developers is to simplify
the collaborative process, enabling users to effortlessly create, share, and modify 
documents together. Whether it's an individual organizing their thoughts or a 
team collaborating on a project. 

APPLIED TECHNOLOGY
The application utilized technologies to make things work smoothly. 
Firebase Authentication and the Quill Docs Editor API were utilized to authenticate 
users, manage user sessions, and enable rich text editing capabilities, 
respectively. React Vite facilitated efficient frontend development, while 
MongoDB served as the backend database management system. Axios handled 
seamless HTTP requests between the frontend and backend, ensuring smooth 
communication. The frontend is crafted with HTML, CSS, and Tailwind CSS with
Framer Motion used for animation, ensuring a responsive and visually appealing 
user interface. Express.js and Socket.io were utilized to establish connections for 
both the database and web sockets. Additionally, Nodemon, a utility that 
monitors changes in Node.js applications and automatically restarts the server, 
was used to streamline the development process.

PROGRAM STRUCTURE 
• client: Contains all frontend-related files and folders.
• server: Contains all backend-related files and folders.
Main Components/Dependencies:
• Firebase Authentication: Manages user authentication and authorization.
• Quill Docs Editor API: Provides rich text editing functionality for note-taking.
• React Vite: Facilitates efficient development of the frontend React 
application.
• Express.js: Builds the backend server and handles HTTP requests.
• MongoDB: Manages data storage and retrieval for user notes.
• Socket.io: Enables real-time communication for collaborative editing.
• HTML, CSS, Tailwind CSS, and Framer Motion: Craft the animation,
responsive design, and visually appealing frontend user interface.
Libraries:
Within React.js and Express.js:
• Toastify: React-Toastify for displaying notifications (toasts) in React 
applications.
• useEffect: A built-in React Hook for handling side effects in functional 
components.
• Motion: Framer Motion is used for animating the user login.
• useNavigate: A hook provided by React Router v6 for programmatically 
navigating between different routes.
• Router: In Express.js, a built-in middleware used to create modular, 
mountable route handlers.
• Route: The basic building block of React Router, rendering a component 
based on the URL path.
• Routes: Introduced in React Router v6, a component used to define 
multiple routes in one place.
• Private Route: A custom route component that checks if the user is 
authenticated before rendering the specified component.
Within Firebase Authentication:
• Firebase Provider: Provider objects for different authentication methods 
supported by Firebase, used for configuring sign-in methods or linking 
accounts.
• auth: A key component of Firebase Authentication, providing access to 
various authentication-related methods and functionalities.
• onAuthStateChanged: Method used to set up a listener that triggers 
whenever the user's authentication state changes.

SETTING IT UP LOCALLY
1. Install Visual Studio Code: 
- Download and Install Visual Studio Code from code.visualstudio.com.
2. Install Node.js: 
- Ensure Node.js is installed on your system. Download it from nodejs.org.
3. Clone the Repository: 
- Sign in to GitHub, copy the repository link, and open Visual Studio Code.
REPOSITORY LINK:
https://github.com/john2772737/note-taking.git
- Click Clone Repository and paste the link. Then, choose folder to clone the 
repository.
4. Run the Client: Open the terminal within Visual Studio Code and navigate to 
the client directory by typing ‘cd client’. Next, install the dependencies by 
running ‘npm install -g yarn’. Then, install Vite using ‘yarn add vite’. Finally, 
start the development server by running ‘yarn run dev’.
5. Run the Server: Open another terminal within Visual Studio Code and 
navigate to the server directory by typing ‘cd server’. Install the 
dependencies by running ‘npm install’. Finally, start the server by running 
‘npm start’
