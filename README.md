# 🏡 99prop – Real Estate Web App

Welcome to **99prop** — a simple, modern web app for browsing real estate listings. Users can sign up, log in, and explore properties based on location and price. It’s built using **HTML**, **Tailwind CSS**, **JavaScript**, and **Firebase** for backend services.

---

##  What It Can Do

-  User authentication (sign up & log in) with Firebase  
-  Save and fetch property listings from Firebase Realtime Database  
-  Filter listings by location and price on the frontend  
-  Clean, responsive UI built with Tailwind CSS  
-  Real-time updates when listings are added or changed  

---

##  Tech Used

| Frontend                        | Backend / Database           |
|--------------------------------|------------------------------|
| HTML, Tailwind CSS, JavaScript | Firebase Realtime Database   |
|                                | Firebase Authentication      |

---

##  Folder Structure

```

📁 99prop/
├── index.html         # Homepage
├── login.html         # Login screen
├── signup.html        # Signup screen
├── buy.html           # Page to view listings
├── script.js          # All JS logic + Firebase setup
├── /assets/           # Images, styles, etc.
└── README.md

````

---

##  How It Works

###  Auth
Users can create an account or log in using their email and password. Firebase handles session management behind the scenes.

###  Listings
Properties are stored in Firebase under a `properties/` node, with details like title, price, location, type, and image URL.

###  Real-Time Updates
New listings are displayed instantly using:
```js
firebase.database().ref("properties").on("value", ...)
````

They’re shown as cards styled with Tailwind.

###  Filters

Filtering is done entirely on the client side — users can narrow listings by location or price using basic JavaScript.

---

##  Screenshot

![Screenshot](https://github.com/user-attachments/assets/6c5285bb-a9ba-4f4b-94a1-697d51aa9b86)

---


##  What’s Next

Here are a few features I’d love to add in the future:

* Switch to **Firestore** for better querying
* Add **image uploads** with Firebase Storage
* Deploy the app via **Firebase Hosting**
* Let users **post and manage** their own listings

---

##  License

Open-source under the MIT License. Feel free to fork, clone, or build on top of it.

---

##  About Me

Created by **Roshini Parida**
Just building things and learning along the way 💻


---


