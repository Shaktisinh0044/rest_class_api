# RESTful Posts App

A simple Node.js Express application for basic post CRUD operations with EJS templating and in-memory data storage.

---

## 🚀 Features

- Create, Read, Update, and Delete posts
- EJS templating for dynamic HTML
- Custom CSS styling
- Unique post IDs via UUID
- Method override for PATCH/DELETE requests

---

## 🛠 Installation

git clone https://github.com/yourusername/rest_class.git <br>
cd rest_class <br>
npm install <br>
node index.js <br>


Open `http://localhost:3000/posts` in your browser.

---

## 📚 Usage

| Route                | Method   | Description                 |
|----------------------|----------|-----------------------------|
| /posts               | GET      | List all posts              |
| /posts/new           | GET      | Form to create new post     |
| /posts               | POST     | Create post                 |
| /posts/:id           | GET      | Show post details           |
| /posts/:id/edit      | GET      | Form to edit post           |
| /posts/:id           | PATCH    | Update post                 |
| /posts/:id           | DELETE   | Delete post                 |

---

## 📁 File Structure

rest_class/ <br>
├── views/ <br>
│ ├── index.ejs <br>
│ ├── show.ejs <br>
│ ├── edit.ejs <br>
│ └── new.ejs <br>
├── public/ <br>
│ └── style.css <br>
├── index.js <br>
├── package.json <br>
├── package-lock.json <br>


---

## 🧩 Dependencies

- express
- ejs
- method-override
- uuid

---

## 🎨 Styling

Edit `public/style.css` to customize your layout and theme.

---

## 🔄 Customization

- Add a database for persistent storage if desired.
- Improve form validation and error handling as needed.

---


---

*Happy coding!*


