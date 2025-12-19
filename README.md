#  Mulahzat – MERN Notes App

Mulahzat is a full-stack note-taking web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create, edit, delete, and search notes with a clean and responsive interface. Authenticated users can manage their notes securely and efficiently.

## Live Preview
**Frontend:** [Visit Mulahzat on localhost:5173](http://localhost:5173)  
*(Deployment link can be added here if hosted)*

## Project Structure
- **Frontend:** React.js (Vite), CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (via Mongoose)
- **Authentication:** JWT-based login/logout
- **UI Features:** Responsive design, modals, alerts, search bar

## Features
- **User Authentication** – Login/logout functionality with protected routes  
- **Create Notes** – Add title, description, and timestamp  
- **Edit Notes** – Update existing notes via modal interface  
- **Delete Notes** – Remove notes with confirmation  
- **Search Notes** – Real-time filtering by title or content  
- **Timestamped Entries** – Each note displays creation date and time  
- **Responsive UI** – Works across desktop and mobile devices  

## Technologies Used
| Layer       | Tech Stack                  |
|-------------|-----------------------------|
| Frontend    | React.js, Vite, CSS         |
| Backend     | Node.js, Express.js         |
| Database    | MongoDB, Mongoose           |
| Auth        | JWT, bcrypt                 |
| Tools       | Postman, VS Code            |

## Screenshots

- **Figure 1:** Notes Dashboard
  <img width="1873" height="935" alt="{DD011DE3-AC69-445E-AEEF-9BF2802AA87D}" src="https://github.com/user-attachments/assets/26dcfd5e-fe87-4d0c-b4f5-f608f1a4f302" />

- **Figure 2:** Add/Edit Note Modal
  <img width="1849" height="935" alt="{577FD492-0E37-469C-B84C-4ACA07F50E63}" src="https://github.com/user-attachments/assets/b839534d-e4f2-459d-9475-a80fd64cf66c" />
  <img width="1868" height="929" alt="{A1B6CCB9-0254-4EFD-9D4B-43E02160EAC9}" src="https://github.com/user-attachments/assets/767f270e-4081-42a4-a202-9f0448c8ce83" />

- **Figure 3:** Search Bar
<img width="1873" height="933" alt="{35B38274-9746-4D1E-90EA-2156A86D78DE}" src="https://github.com/user-attachments/assets/655547a7-1ae9-4db8-bd37-4243e1bc9723" />

- **Figure 4:** User Login Interface
  <img width="1905" height="936" alt="{C26A9F23-9FEE-4648-9DA5-54134D75A6A2}" src="https://github.com/user-attachments/assets/4191d70a-205e-4346-ad33-c4e766b094c0" />

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/NoorAisha25/Notes-App.git
cd Notes-App
```
### 2. Backend Setup
```bash
cd backend
npm install
npm start
```
### 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

## Folder Structure
```
Notes-App/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
└── README.md
```
## Future Enhancements
- Add user registration and password reset
- Enable note tagging and color coding
- Export notes to PDF or Markdown
