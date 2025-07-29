# 📝 Smart Task Tracker

A full-stack web application that allows users to register, log in, and manage personal tasks. Users can add, view, update, and delete tasks with status tracking.

Built with Node.js, Express, MongoDB, and Handlebars — ideal for learning backend development and full-stack web apps.

---

## 🚀 Features

- ✅ User registration and login (with secure password hashing)
- ✅ Session-based authentication
- ✅ Task CRUD (Create, Read, Update, Delete)
- ✅ Status tracking: Pending, In Progress, Done
- ✅ Flash messages for login and errors
- ✅ Responsive UI with clean CSS layout

---

## 🛠️ Tech Stack

- **Frontend**: HTML, Handlebars, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (local or Atlas)
- **Auth**: bcrypt + express-session
- **Templating**: express-handlebars
- **Flash messages**: connect-flash

---

## 📂 Project Structure

smart-task-tracker/
├── app.js
├── config/
│ └── mongoConnection.js
├── data/
│ ├── users.js
│ └── tasks.js
├── routes/
│ ├── auth.js
│ └── index.js
├── views/
│ ├── layouts/
│ │ └── main.handlebars
│ ├── dashboard.handlebars
│ ├── login.handlebars
│ ├── register.handlebars
│ └── error.handlebars
├── public/css/
│ └── styles.css

---

## 🧪 How to Run Locally

### 1. Clone this repo

```bash
git clone https://github.com/amritmalhi99/smart-task-tracker.git
cd smart-task-tracker

npm install

mongod

npm start

Then open http://localhost:3000 in your browser.



🙋‍♀️ Author
Amrit Kaur
