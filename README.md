# 📝 NoteForge - Smart Notes Manager

NoteForge is a **web-based Smart Notes Manager** built using **Java, Spring Boot, Maven, Thymeleaf, Spring Data JPA, and H2 Database**.  
It helps users create, manage, organize, and search notes through a clean and responsive web interface.

---

## 🚀 Features

- ➕ Add new notes
- 👀 View note details
- ✏️ Edit existing notes
- ❌ Delete notes
- 🔍 Search notes by title, category, or content
- ⭐ Mark notes as favorite
- 📂 Organize notes by category
- 🕒 Auto track created and updated timestamps
- 🌐 Responsive web-based dashboard

---

## 🛠 Tech Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Maven

### Frontend
- Thymeleaf
- HTML
- CSS
- Bootstrap 5

### Database
- H2 Database (In-Memory)

---

## 📂 Project Structure

```bash
NoteForge
│── pom.xml
│── src
│   ├── main
│   │   ├── java
│   │   │   └── noteforge
│   │   │       ├── NoteForgeApplication.java
│   │   │       ├── controller
│   │   │       │   └── NoteController.java
│   │   │       ├── entity
│   │   │       │   └── Note.java
│   │   │       ├── repository
│   │   │       │   └── NoteRepository.java
│   │   │       └── service
│   │   │           └── NoteService.java
│   │   └── resources
│   │       ├── templates
│   │       │   ├── index.html
│   │       │   ├── add-note.html
│   │       │   ├── edit-note.html
│   │       │   └── view-note.html
│   │       ├── static
│   │       │   └── css
│   │       │       └── style.css
│   │       └── application.properties
```
# 🏗 Architecture

The project follows MVC Architecture:

Controller Layer → Handles HTTP requests and routes

Service Layer → Contains business logic

Repository Layer → Handles database operations

Entity Layer → Defines the Note model

View Layer → Thymeleaf templates for UI

# 📌 Main Functionalities
1. Add Note

Users can create a note with:

Title

Category

Content

Favorite option

2. View Note

Users can open a detailed page for a specific note.

3. Edit Note

Existing notes can be updated anytime.

4. Delete Note

Users can remove notes permanently.

5. Search Notes

Users can search notes by:

Title

Category

Content

6. Favorite Notes

Important notes can be marked as favorites and filtered separately.

▶️ How to Run
1. Clone the repository
git clone <your-repo-link>
2. Navigate to project folder
cd NoteForge
3. Run the project
mvn spring-boot:run
4. Open in browser
http://localhost:8080
🗄 H2 Database Console

You can access the H2 console here:

http://localhost:8080/h2-console
Default Credentials:

JDBC URL: jdbc:h2:mem:noteforge

Username: sa

Password: (leave blank)

Note: The in-memory database URL may change during runtime if Spring Boot generates a random one.

📸 Screenshots

You can add screenshots here later:

Dashboard Page

Add Note Page

View Note Page

Edit Note Page

🌟 Why This Project?

This project is a good college-level Maven web application because it demonstrates:

Java + Spring Boot development

Maven project structure

MVC architecture

CRUD operations

Database integration

Search and filtering

Responsive frontend

Real-world use case

🔮 Future Enhancements

Possible future improvements:

🔐 User Login / Registration

🗃 Archive and Trash functionality

🌙 Dark Mode

🏷 Tags support

📄 Export notes as PDF / TXT / Markdown

🗄 MySQL or PostgreSQL integration

☁️ Cloud sync

🤖 AI-based note summarization

# 👨‍💻 Author
Sheikh Wasimuddin
