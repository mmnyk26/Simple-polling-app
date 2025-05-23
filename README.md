# Simple Polling App

A simple web application that allows users to create polls, vote, and view results.

## Features

- Create a poll with a question and multiple options
- Vote on a poll
- View live voting results
- Responsive UI 
- Backend: Java Spring Boot + MySQL
- Frontend: React.js + TailwindCSS
- REST API Integration

---

## Folder Structure

```
simple-polling-app/
│
├── backend/       # Spring Boot backend
│   └── src/
│       └── main/
│           └── java/
│           └── resources/
│               └── application.properties
│
├── frontend/      # React frontend with TailwindCSS
│   └── src/
│       └── App.jsx
│       └── index.js
│       └── index.css
│   └── package.json
│   └── tailwind.config.js
│   └── postcss.config.js
│
└── README.md
```

---

## Backend Setup (Spring Boot)

1. Install Java (JDK 17+) and MySQL.
2. Create a MySQL database named `polling_app`.
3. Update `backend/src/main/resources/application.properties` with your DB credentials.
4. Run the backend using an IDE like IntelliJ or via terminal:
    ```bash
    ./mvnw spring-boot:run
    ```

---

## Frontend Setup (React.js + TailwindCSS)

1. Open terminal and navigate to the `frontend` folder.
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm start
    ```
4. App runs on [http://localhost:3000](http://localhost:3000)

---

## Deployment

You can host the backend on services like Render, Railway, or Heroku, and frontend on Netlify or Vercel.

---

## Optional Enhancements

- Track who voted (add user or IP identification)
- Authentication with JWT
- Poll expiration and archiving
- Admin dashboard

---

## License

MIT License
