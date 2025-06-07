# AI Career Consultant

This repository contains two independent projects:

## 1. Resume Matcher (Flask App)

A full-featured web application for resume parsing, ATS scoring, and job matching.

### Features
- User and admin authentication
- Resume upload and parsing (PDF, DOCX, TXT)
- ATS scoring and job matching
- User analytics and profile management
- Admin dashboard for user management and analytics

### Tech Stack
- **Backend:** Flask, MySQL
- **Libraries:** docx2txt, PyPDF2, scikit-learn (TF-IDF, cosine similarity)
- **Frontend:** HTML templates, static assets (CSS, images)

### Setup
1. Install Python dependencies:
   ```
   pip install flask docx2txt PyPDF2 scikit-learn mysql-connector-python
   ```
2. Configure MySQL database (default: localhost, user: root, password: empty, database: resumematcher_db).
3. Run the Flask app:
   ```
   python resumematcher/main.py
   ```

### Project Structure
- `resumematcher/main.py`: Core Flask application logic
- `resumematcher/templates/`: HTML templates for the web interface
- `resumematcher/static/`: Static assets (CSS, images)
- `resumematcher/uploads/`: Directory for uploaded files (resumes, profile pictures)

---

## 2. Event Management (Node.js + React)

A simple event management application with a React frontend and Express backend.

### Features
- Create events
- Register for events
- Submit feedback for events

### Tech Stack
- **Backend:** Node.js, Express
- **Frontend:** React, Axios
- **Dependencies:** body-parser, cors

### Setup
1. Install Node.js dependencies:
   ```
   cd event-management
   npm install
   ```
2. Start the Express server:
   ```
   node server.js
   ```
3. Start the React app (if applicable):
   ```
   npm start
   ```

### Project Structure
- `event-management/server.js`: Express backend with in-memory data storage
- `event-management/src/App.js`: React frontend for event management
- `event-management/package.json`: Project dependencies and scripts

---

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details. 