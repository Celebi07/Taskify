# Taskify 
**A Task Reminder and Scheduling Application**

---

## Table of Contents  

1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Getting Started](#getting-started)  
5. [Backend Setup](#backend-setup)  
6. [Frontend Setup](#frontend-setup)  
7. [API Documentation](#api-documentation)  
8. [Contributing](#contributing)  
9. [License](#license)  

---

## Project Overview  

TaskSphere is a simple, yet powerful web application designed to manage daily, weekly, and monthly tasks with built-in reminders and scheduling. It provides a clean and intuitive interface for task creation, tracking progress, and timely notifications to ensure that nothing important is missed.  

Whether for personal productivity or small team collaboration, TaskSphere streamlines task management to enhance productivity.  

---

## Features  

- **Task Creation**: Create tasks with due dates, priorities, and detailed descriptions.  
- **Priority Levels**: Set custom priorities ranging from Low to Urgent.  
- **Task Dependencies**: Ensure tasks are dependent on others and visualize task relationships.  
- **Task Recurrence**: Schedule recurring tasks with custom intervals and flexible end dates.  
- **Offline Access**: Create and manage tasks offline, with automatic syncing when online.  
- **Notifications**: Real-time push notifications for reminders and updates.  
- **Attachment Management**: Attach files/documents to individual tasks for easy reference.  
- **Custom Tags**: Organize tasks using custom tags for easier filtering and categorization.  
- **Task Progress Tracking**: Monitor progress via progress bars and milestones.  
- **User Authentication**: Secure login and registration using JWT-based authentication.  

---

## Technologies Used  

- **Frontend**: React, Redux  
- **Backend**: Node.js, Express  
- **Database**: MongoDB  
- **Styling**: CSS, Material-UI  
- **Deployment**: Heroku, Vercel/Netlify  
- **Version Control**: Git, GitHub  

---

## Getting Started  

### Prerequisites  

- Node.js and npm installed on your machine.  
- Basic understanding of JavaScript and web development concepts.

### Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/username/TaskSphere.git  
   cd TaskSphere  
   ```

2. Install dependencies:  
   ```bash  
   npm install  
   ```

---

## Backend Setup  

### Database Setup  

1. **MongoDB Setup**:  
   - Start a local MongoDB instance or deploy a cloud database.  
   - Ensure MongoDB URI is added to `.env` for backend operations.

2. **Server Setup**:  
   - Navigate to the backend folder:  
     ```bash  
     cd backend  
     npm install  
     ```

3. **Run Backend**:  
   ```bash  
   node server.js  
   ```

---

## Frontend Setup  

### Running the Frontend  

1. Navigate to the frontend folder:  
   ```bash  
   cd frontend  
   npm install  
   ```

2. Run the application:  
   ```bash  
   npm start  
   ```

---

## API Documentation  

### Authentication  

- **Register**: `POST /api/register`  
- **Login**: `POST /api/login`  
- **Get User Tasks**: `GET /api/tasks`  
- **Create Task**: `POST /api/tasks`  
- **Update Task**: `PUT /api/tasks/:id`  
- **Delete Task**: `DELETE /api/tasks/:id`  

---

## Contributing  

Contributions to TaskSphere are welcome! Here’s how you can contribute:  

1. Fork the repository.  
2. Create a new branch:  
   ```bash  
   git checkout -b new-feature  
   ```  
3. Commit your changes:  
   ```bash  
   git commit -m "Add new feature"  
   ```  
4. Push to the branch:  
   ```bash  
   git push origin new-feature  
   ```  
5. Create a pull request.

---

## License  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
