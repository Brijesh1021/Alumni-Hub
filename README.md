# AlumniHub

AlumniHub is an improved version of the Alumni-Connect web application designed to strengthen alumni engagement. This platform enables users to connect with former classmates, view and share job opportunities, attend events, and much more.

> ⚠️ This project is based on the original [Alumni-Connect](https://github.com/SahilAli8808/Alumni-Connects) (MIT Licensed) with major feature enhancements and UI changes. Credit to the original authors for the base structure.

## 🔧 Major Changes & Additions (My Modifications)
- ⚙️ Integrated **Admin middleware** (`checkAdmin.js`) for role-based access control.
- 📄 Added **resume upload** functionality (file storage + database entry).
- 📧 Implemented **sendMail** backend route using NodeMailer.
- 💬 Improved **chat system** with Socket.IO (real-time messaging).
- 🔗 Added React routes to support new backend features (Resume, SendMail, Admin controls).
- 🎨 Redesigned and improved frontend components for better UI/UX.
- 🔐 Enhanced **auth flow** and protected certain routes with admin-only access.
- 📁 Cleaned up and restructured code for better maintainability.

---

## 🎯 Key Features

- 👥 Alumni Verification and Authentication
- 📅 Create & Manage Events (Admin)
- 💼 Post and View Jobs
- 📬 Send Targeted Emails
- 📂 Upload and View Resumes
- 📰 Publish Newsletters
- 🧹 Auto-Delete Expired Notices
- 📈 Analytics Dashboard
- 💬 Real-Time Chat Rooms (via Socket.IO)
- 🧑‍🏫 Faculty Management
- 🎯 Advanced Search & Filter (Name, Year, Department, etc.)
- 🎟️ Raise and Manage Support Tickets

---

## 🖼️ Screenshot

![Screenshot](https://github.com/Kumailrizvi786/Alumni-Connect/blob/main/Frontend/src/assets/img/screenshots.jpg)

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

### Installation

1. **Clone this repo**
   ```bash
   git clone https://github.com/Brijesh1021/AlumniHub.git
   cd AlumniHub

### Prerequisites
* [Node.js](https://nodejs.org/en/download/)
* [MongoDB](https://www.mongodb.com/download-center/community)
* [Git](https://git-scm.com/downloads)
### Installation
1. Clone the repo
```sh
git clone https://github.com/SahilAli8808/Alumni-Connect.git
```
or 
```sh
git clone https://github.com/Kumailrizvi786/Alumni-Connect.git
```
1.2 Change directory
```sh   
cd Alumni-Connect
```
1.3 create a .env file and add the following(can use .env.example as a reference)
```sh
PORT=3000
PORT= 8080
DB_NAME=
GMAIL =
GMAILPASS=
MONGODB_URI = mongodb+srv://<username>:<password>@cluster0.9mnlyjk.mongodb.net/?retryWrites=true&w=majority
CORS_ORIGIN =*
JWT_SECRET=
JWT_COOKIE_EXPIRES_IN = 30
JWT_EXPIRES_IN = 30m

```

2. Install NPM packages
```sh
npm install
```
3. Run the app
3.1 For Frontend
```sh
npm run dev
```

3.2 For Backend
```sh
npm start 
```

## Built With
* [Node.js](https://nodejs.org/en/download/)
* [Express.js](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/download-center/community)
* [Mongoose](https://mongoosejs.com/)

## Authors
* [**Sahil Ali**](https://www.linkedin.com/in/sahilali20/)
* [**Syed Kumail Rizvi**](https://www.linkedin.com/in/syed-kumail-rizvi/)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details




