Here’s a clean, ready-to-push **README.md** for a “Get Random User” project. You can copy and paste this directly into your repo:


# 🎲 Get Random User

A simple project that fetches and displays random user data using an external API. Great for learning API integration, async requests, and basic UI rendering.

## 🚀 Features

* Fetch random user data from an API
* Display user details (name, email, location, avatar, etc.)
* Refresh to get a new random user
* Clean and minimal UI
* Beginner-friendly code structure

## 🛠️ Tech Stack

* HTML / CSS / JavaScript 
* Fetch API / Axios
* Random User API

## 📦 Installation

1. Clone the repository:

bash
git clone https://github.com/shamsaawi143/get-random-user.git


2. Navigate into the project folder:

bash

cd get-random-user


3. Open `index.html` in your browser
   *(or run your dev server if using a framework)*

## 🔌 API Used

This project uses the free API:
👉 [https://randomuser.me/](https://randomuser.me/)

Example request:

bash
https://randomuser.me/api/


## 📸 Demo
📸 Preview
App Screenshot

![Note App Screenshot](RADOM_USER_GEN/assets/Screenshot.png)

## 🧠 How It Works

1. A request is sent to the Random User API
2. The response is parsed as JSON
3. User data is extracted and displayed on the page
4. Clicking a button fetches a new user

## 📁 Project Structure


get-random-user/
│── index.html
│── style.css
│── script.js
└── README.md

## ✨ Example Code

javascript
async function getRandomUser() {
  const res = await fetch("https://randomuser.me/api/");
  const data = await res.json();
  const user = data.results[0];

  console.log(user.name.first, user.email);
}

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

Author : Mohamed Ismail