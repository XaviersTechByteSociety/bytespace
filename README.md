# Club Management Web App

## Project Overview
A powerful and intuitive Club Management Web App designed to streamline member registration, event planning, budget tracking, file sharing, announcements, and more – all in one place. Whether you're an admin managing users, a treasurer handling expenses, or a member engaging with events, this platform ensures a seamless club experience.

## Features
### User Management
- Secure Member Registration & Login (Firebase Auth/JWT)
- Role-Based Dashboards (Admin, Treasurer, Member)
- Profile Editing (Bio & Profile Photo)
- Admins can add/delete users & manage roles

### Event Management
- Create, Edit, & Delete Events
- Calendar Integration
- Upload event images & announcements
- Mark & View Attendance

### Budget Tracking
- Admin & Treasurer Access Only
- Add & Manage Expenses
- View Budget History

### File & Announcement Sharing
- Upload & Download Files
- Post Announcements visible to all members

### Notifications & Emails
- Automatic event reminders & updates
- Member notifications for new announcements

### Optional Global Chat
- Real-time chat for all logged-in users

## Project Structure
```
club-management-app/
│── backend/                     # Node.js backend (if not using Firebase)
│   ├── models/                  # Database schemas
│   ├── routes/                  # API routes (Auth, Events, Budget, etc.)
│   ├── controllers/             # Business logic for routes
│   ├── middleware/              # Role-based access control
│
│── frontend/                    # React (Next.js) frontend
│   ├── components/              # Reusable UI components
│   ├── pages/                   # Dashboard, Events, Budget, etc.
│   ├── context/                 # Global state management
│   ├── styles/                  # Tailwind CSS for styling
│
│── database/                    # Database setup
│── docs/                        # Documentation
│── .env                         # Environment variables
│── README.md                    # This file
```

## Tech Stack
- Frontend: React.js (Next.js), Tailwind CSS
- Backend: Node.js (Express.js) / Firebase Functions
- Database: Firebase Firestore / PostgreSQL
- Authentication: Firebase Auth / JWT
- File Storage: Firebase Storage / AWS S3
- Real-time Features: Firebase Realtime DB / Socket.io

## Installation & Setup
### Clone the Repository
```sh
git clone https://github.com/XaviersTechByteSociety/xts-mgm.git
cd xts-mgm
```

### Install Dependencies
#### Backend:
```sh
cd backend
npm install
```
#### Frontend:
```sh
cd frontend
npm install
```

### Setup Environment Variables
Create a `.env` file in both `backend/` and `frontend/` directories with necessary keys.

### Run the App
#### Backend:
```sh
npm run dev
```
#### Frontend:
```sh
npm run dev
```

## Contribution Guidelines
Contributors will be directly added to the repository, so forking is not required. If you have been added as a contributor, follow these steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/XaviersTechByteSociety/xts-mgm.git
   ```
2. Create a new branch for your feature or fix:
   ```sh
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```sh
   git commit -m "Added feature X"
   ```
4. Push to the repository:
   ```sh
   git push origin feature-branch
   ```
5. Open a Pull Request for review and merging.

## Contact & Support
If you have any questions or want to contribute, feel free to reach out via email or open an issue on GitHub.


