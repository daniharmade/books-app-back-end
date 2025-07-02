
# 📚 Books App - Back End

This is the back-end of a simple books application built with a RESTful API. It provides CRUD operations and supports archiving and unarchiving of books.

## ✨ Features
- Add new books
- View all books
- View book details
- Update book information
- Delete books
- Archive and unarchive books

## 🛠️ Technologies Used
- Node.js
- Express.js
- (Optional) JSON file / database

## 🔧 API Endpoints

| Method | Endpoint              | Description                    |
|--------|-----------------------|--------------------------------|
| GET    | `/books`              | Get all books                  |
| GET    | `/books/:id`          | Get book details               |
| POST   | `/books`              | Add a new book                 |
| PUT    | `/books/:id`          | Update book information        |
| DELETE | `/books/:id`          | Delete a book                  |
| GET    | `/books/archived`     | Get archived books             |
| PATCH  | `/books/:id/archive`  | Archive or unarchive a book    |

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/books-app-back-end.git
   cd books-app-back-end
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   npm start
   ```

The server will run on `http://localhost:3000` by default.

## 📂 Project Structure (optional)

```
books-app-back-end/
├── routes/
│   └── books.js
├── controllers/
│   └── booksController.js
├── models/
│   └── booksModel.js
├── data/
│   └── books.json
├── app.js
└── package.json
```

---

📌 *Note*: This project was created as part of learning backend development and data management practices.
