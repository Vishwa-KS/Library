# 📚 **Library Management System**

A Java-based desktop application designed to simplify library management tasks such as user registration, book issue/return, viewing book records, and tracking user history. Built using standard Java SE, with a Swing-style GUI frontend.

---

## **Features**

- **User Authentication & Registration**
  - `login_system.java`: Handles user login functionality.
  - `Register.java`: Implements new user registration.

- **Book Issue & Return**
  - `Issuebook.java`: Interface to issue books to users.
  - `Returnbook.java`: For processing book returns.

- **Book & User Records**
  - `Viewbook.java`: View available books and their details.
  - `Dashboard.java`: Central control panel with navigation to core features.

- **Utility Pages**
  - `Forgetpage.java`: Supports password recovery or forgotten credentials.
  - `history.java`: Displays book-issue/return history per user or book.

- **Category Management**
  - `Category.java`: For categorizing books (genre, section, etc.).

- **Media**
  - `lib vid_compressed.mp4`: Demo or walkthrough video of the application.

---

## **📦 Project Structure**

```
Library/
│
├── src/
│   ├── Category.java
│   ├── Dashboard.java
│   ├── Forgetpage.java
│   ├── Issuebook.java
│   ├── Register.java
│   ├── Returnbook.java
│   ├── Viewbook.java
│   ├── history.java
│   └── login_system.java
│
└── lib vid_compressed.mp4
```

---

## **🚀 Getting Started**

### Requirements
- Java SE 8 or later.
- (Optional) IDE such as IntelliJ IDEA or Eclipse.

### Setup
```bash
git clone https://github.com/veldark2005/Library.git
```
- Open the project in your IDE.
- Ensure all `.java` files are in the correct package (if applicable) and compile without errors.

### Run
- Execute `login_system.java` (or your main class) to launch the application GUI.

---

## **🛠️ Usage**

1. **Register** a new user via the registration form.
2. **Log in** using credentials.
3. Use the **Dashboard** to:
   - Issue a book.
   - Return a book.
   - View all books.
   - Check borrowing history.
4. Forgot your password? Use the **Forgot Password** page to recover it.
5. Organize books using the **Category** module.

---

## **🎥 Demo**

A walkthrough of the application is available in `lib vid_compressed.mp4`.

---

## **✅ To-Do / Future Improvements**

- Enhance the UI using JavaFX or a modern GUI framework.
- Integrate persistent storage (SQLite/MySQL).
- Add EC management (librarian vs. student admin roles).
- Implement robust error handling and input validation.
- Support book search and filtering.
- Export records (e.g. to CSV or PDF).

---

## **🤝 Contributing**

1. Fork the repo.
2. Create a dedicated feature/bugfix branch.
3. Make your changes and commit with descriptive messages.
4. Open a pull request — include screenshots or details of your modifications.

