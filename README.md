# ⚠️ Important Notice
It was built as part of my **Full Stack Web Development Diploma at [Route Academy]** — a leading software training center in Egypt.
# Bookmarker

A clean and functional web-based **Bookmark Manager** built with **HTML**, **CSS**, **JavaScript**, and **Bootstrap**. Easily add, validate, display, visit, and delete bookmarks — all stored in the browser's local storage.

## 🚀 Features

* 📌 Add bookmarks with name and URL
* ✅ Input validation using RegEx
* 💾 Persist bookmarks using `localStorage`
* 👀 Visit saved bookmarks directly
* 🗑️ Delete bookmarks on demand
* 🧼 Form reset and visual feedback for user input
* 🎨 Styled with Bootstrap and custom CSS for a polished look

## 🧮 CRUD Operations

This project demonstrates basic **CRUD** operations:

* **Create**: Add a new bookmark with name and URL
* **Read**: Display all saved bookmarks in a table on page load
* **Update**: While there's no dedicated update feature, validation gives real-time feedback, and entries can be re-added
* **Delete**: Remove any bookmark from the list and from local storage

All operations are handled dynamically using JavaScript and persist through page refresh using the browser's `localStorage`.


## 🛠️ Technologies Used

* HTML5
* CSS3 (Custom and Bootstrap 5)
* JavaScript (Vanilla)
* Bootstrap Icons + FontAwesome
* Google Fonts

## 📂 Project Structure

```plaintext
index.html        # Main HTML file
css/
  └── home.css    # Custom styling
js/
  └── main.js     # All core bookmark logic
```

## 📋 Validation Rules

* **Site Name**: Minimum 3 characters
* **Site URL**: Must be a valid `http://` or `https://` URL
* Invalid inputs trigger a Bootstrap modal with helpful messages

## 🔧 Setup Instructions

1. Clone or download the repository
2. Open `index.html` in a browser
3. Start adding and managing your favorite sites

## 📦 Local Storage Format

Bookmarks are saved in `localStorage` as a JSON array:

```json
[
  {
    "name": "Google",
    "url": "https://www.google.com"
  },
  ...
]
```


## 📑 License

This project is for educational purposes only.
Feel free to explore, use parts of it, and reach out for collaboration or feedback!



---

