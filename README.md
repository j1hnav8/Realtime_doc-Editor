# Realtime_doc-Editor
REALTIME_DOCUMENT-EDITOR
>COMPANY NAME : CODTECH IT SOLUTIONS PVT.LTD
>INTERN NAME  : KOTYADA JAHNAVI
>INTERN ID    : CT04DF2117
>DOMAIN       : FULL STACK WEB DEVELOPMENT
>DURATION     : 4 WEEKS
>MENTOR       : NEELA SANTHOSH


##  OVERVIEW


**Technology Stack**: React.js, Node.js (NestJS), Socket.IO, MongoDB

###  Project Idea

This project is a **real-time collaborative document editor** similar to Google Docs. It allows multiple users to edit the same document simultaneously. All changes are automatically synchronized using WebSockets and saved in a MongoDB database.

###  Objective

* Build a real-time editing platform where users can collaborate on documents live.
* Use **Socket.IO** for instant updates between users.
* Store documents in **MongoDB** for persistence.
* Make the UI clean, responsive, and easy to use with **React and TailwindCSS**.

###  Key Components

| Component     | Description                                                                                           |
| ------------- | ----------------------------------------------------------------------------------------------------- |
| **Frontend**  | Built with React.js. Contains the UI for text editing and routing. Uses `react-quill` for the editor. |
| **Backend**   | Built with NestJS. Handles document fetching, creation, and real-time communication via WebSocket.    |
| **Database**  | MongoDB stores document content mapped by document IDs.                                               |
| **WebSocket** | Enables real-time text syncing using `socket.io`.                                                     |


###  Features

*  Real-time text synchronization across devices
*  JWT-based authentication (optional)
*  Auto-saving to MongoDB
*  Unique URL for each document (`/doc/:id`)
*  Modern UI using Tailwind CSS
*  Scalable architecture using NestJS modules

###  Workflow

1. User navigates to the homepage
2. A unique document ID is generated or entered
3. WebSocket connection is established
4. Document content loads from MongoDB (if exists)
5. All users editing the same document see live updates
6. Content is periodically saved in the database



###  Technologies Used

| Tech/Library     | Purpose                        |
| ---------------- | ------------------------------ |
| React.js         | Frontend UI                    |
| React-Quill      | Rich text editor               |
| React Router     | Routing between documents      |
| Tailwind CSS     | Styling                        |
| Node.js + NestJS | Backend server                 |
| Socket.IO        | Real-time communication        |
| MongoDB          | NoSQL database                 |
| JWT              | User authentication (optional) |

---

###  Folder Structure

```
project-root/
├── client/     ← React frontend
│   ├── src/
│   │   ├── App.jsx
│   │   ├── Editor.jsx
│   │   └── ...
├── server/     ← NestJS backend
│   ├── src/
│   │   ├── docs/
│   │   ├── auth/
│   │   └── ...


>> Use Cases

* School and college collaborative assignments
* Remote team note-taking
* Live coding interviews or document sharing


 >> Future Scope

* Add user cursors and live indicators
* Add comments, version history, and chat
* Export documents to PDF or Word
* Deploy to cloud (e.g., Render, Vercel)

#output:
![Image](https://github.com/user-attachments/assets/8675f6ed-117c-4074-98c5-16eaef5c041c)

![Image](https://github.com/user-attachments/assets/71386cb8-6879-4d79-9c76-6ceccafb3bfb)


