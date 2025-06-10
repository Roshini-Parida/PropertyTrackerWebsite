Got it! Here's your updated **`README.md`** with credit to **Roshini Parida**:

---

```markdown
# 🏡 99prop – Real Estate Web Application

A modern real estate platform where users can sign up, log in, and browse filtered property listings — built with **HTML**, **Tailwind CSS**, **JavaScript**, and **Firebase** (Authentication + Realtime Database).

---

## 🚀 Features

- 🔐 **User Authentication** with Firebase (Signup/Login)
- 📦 **Store & Retrieve Property Listings** from Firebase Realtime Database
- 🔍 **Client-Side Filtering** based on location and price
- 💻 **Responsive UI** using Tailwind CSS
- ⚡ **Live Updates** for listings via Firebase listeners

---

## 🛠️ Tech Stack

| Frontend                       | Backend / DB                  |
|--------------------------------|-------------------------------|
| HTML, Tailwind CSS, JavaScript | Firebase Realtime Database    |
| Firebase Authentication        | 

---

## 🔧 Project Structure

```

📁 99prop/
├── index.html         # Homepage
├── login.html         # User login form
├── signup.html        # User signup form
├── buy.html           # Property listings page
├── script.js          # Firebase & JS logic
├── /assets/           # Images & styles
└── README.md

````

---

## 🧠 How It Works

### 🔐 Firebase Authentication
- Users can **sign up** and **log in** using email and password.
- Session is handled via `firebase.auth().onAuthStateChanged`.

### 🏘️ Property Listings
- Stored in Firebase Realtime Database under `properties/`
- Each listing includes title, price, location, type, and image URL.

### 📥 Real-Time Display
- Properties are dynamically fetched using:
  ```js
  firebase.database().ref("properties").on("value", ...)
````

* Displayed as Tailwind-styled cards.

### 🔍 Filtering

* Client-side filtering by location and price using JavaScript.

---

## 📸 Screenshots



---

## 📦 Firebase Config Snippet

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "your-app.firebaseapp.com",
  databaseURL: "https://your-app.firebaseio.com",
  projectId: "your-app-id",
  // ...
};
firebase.initializeApp(firebaseConfig);
```

---

## 💡 Future Enhancements

* 🔄 Switch to Firestore for advanced queries
* 📸 Add image uploads via Firebase Storage
* 🌐 Deploy using Firebase Hosting
* 🧾 Add user-specific listing management

---

## 📜 License

This project is open-source and free to use under the MIT License.

---

## 🙋‍♀️ Made by

**Roshini Parida**
Built with ❤️ using Firebase and Tailwind CSS

---
