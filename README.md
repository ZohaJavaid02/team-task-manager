# 🎯 Team Task Manager

A full-stack **Team Task Management Application** that helps teams organize projects, assign tasks, and track progress efficiently — all with a modern glassmorphism UI.

---

## 🚀 Features

* 🔐 **Authentication System**

  * User Signup & Login
  * Secure password hashing (bcrypt)
  * JWT-based authentication

* 👥 **Role-Based Access Control**

  * **Admin**: Create projects, add members, assign tasks
  * **Member**: View assigned tasks and update progress

* 📁 **Project Management**

  * Create and manage multiple projects
  * Add/remove team members

* ✅ **Task Management**

  * Create, assign, update, and delete tasks
  * Task statuses: `To Do`, `In Progress`, `Done`
  * Due dates & overdue tracking

* 📊 **Dashboard**

  * Total tasks
  * Completed / Pending / Overdue tasks

* 🎨 **Modern UI**

  * Dark gradient theme
  * Glassmorphism design
  * Responsive layout

---

## 🛠️ Tech Stack

| Layer    | Technology            |
| -------- | --------------------- |
| Frontend | HTML, CSS, JavaScript |
| Backend  | Node.js, Express.js   |
| Database | SQLite                |
| Auth     | JWT, bcrypt           |

---

## 📂 Project Structure

```
Team-Task-Manager/
│── public/          # Frontend (HTML, CSS, JS)
│── src/             # Backend (Express server)
│── data/            # SQLite database file
│── package.json
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/team-task-manager.git
cd team-task-manager
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Run the server

```bash
npm start
```

---

## 🗄️ Database (SQLite)

* The app uses a **local SQLite database**
* Database file is stored in:

  ```
  /data/team_task_manager.db
  ```

### 🔄 Reset Database (optional)

```bash
rm data/team_task_manager.db
npm run dev
```

---

## 🔐 Environment Variables (Optional)

You can configure:

```env
PORT=3000
JWT_SECRET=your_secret_key
CORS_ORIGIN=*
```

---

## 💡 Future Enhancements

* 📊 Advanced analytics & charts
* 📌 Drag-and-drop task board (Kanban)
* 🔔 Notifications system
* 🗂️ File attachments in tasks

---

## 👩‍💻 Author

**Zoha Javaid**
GitHub: https://github.com/ZohaJavaid02

---

## ⭐ Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---
