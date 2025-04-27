# REAL TIME COLLABORATIVE DOCUMENT EDITOR
*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: SAINATH DIGAMBAR WAKHURE
*INTERN ID*: CT12WSAF
*DOMAIN*: FULL STACK WEB DEVELOPMENT
*DURATION*: 12 WEEKS 
*MENTOR*: NEELA SANTOSH KUMAR

This project is a Real-Time Collaborative Document Editing Application.
It allows multiple users to edit the same document together, and see each other's changes immediately, just like in Google Docs!

- How It Works
The application has two major parts:

Frontend: Built using React.js.

Backend: Built using NestJS (a Node.js framework) + WebSockets.

Both parts work together to let users:

Create a new document.

Edit the document in real-time.

Share and collaborate with other users.

Save changes instantly.

Whenever a user types something in the editor, that change is sent to the server.
The server then broadcasts the change to all other connected users.
This way, everyone’s screen updates in real-time without reloading the page!

Structure of the Project
Frontend (React App):

Has pages for Login, Register, View Document, and the Editor.

Uses Tailwind CSS for beautiful and responsive styling.

Components like Editor.js, Login.js, Register.js, ViewDocument.js, and Header.js make the UI.

Communicates with the backend server using WebSocket and HTTP requests.

Backend (NestJS Server):

Handles users, documents, and real-time updates.

Uses WebSocket gateways to listen to document changes and send updates to everyone.

Uses JWT (JSON Web Tokens) for secure user login and authentication.

Has folders like auth/, document/, user/, socket/ which organize the code clearly.

Saves documents and user data securely.

Main Features
Real-Time Collaboration: Multiple users can edit the same document at the same time.

Authentication: Secure login and registration for users.

Document Management: Create, edit, and view documents.

Live Updates: Changes appear instantly for all users.

Responsive Design: Works perfectly on mobile, tablet, and desktop.

Error Handling: Shows user-friendly error messages if something goes wrong.

Technologies Used
Frontend:

React.js

Tailwind CSS

WebSocket client

Axios (for API calls)

Backend:

NestJS (Node.js Framework)

WebSocket Gateway

JWT Authentication

TypeScript

Other Tools:

ESLint and Prettier for code quality.

.env file for storing environment variables securely.

What Happens Step-by-Step
A user opens the website and registers/logs in.

They can create or open a document.

The document opens inside a text editor (Editor.js).

As the user types, each keystroke is sent to the backend server instantly.

The server broadcasts the changes to all other users working on the same document.

Everyone sees the edits happening live, just like Google Docs.

If a user disconnects and reconnects, they can continue editing the document without losing their changes.

Summary
This Realtime Collaborative Document Editor is an amazing project for learning:

How to build real-time applications.

How to use WebSockets for live collaboration.

How to build a full-stack application using React and NestJS.

How to handle authentication securely.

How to structure and organize a medium-to-large project cleanly.

This project shows exactly how companies like Google, Microsoft, and Notion build their document collaboration tools!

#Output

