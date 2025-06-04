# URL Shortener

A URL shortener application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to shorten long URLs, generate random short links, and create custom short URLs.

---

## Features

- Shorten long URLs to compact links.
- Create custom short URLs with user-defined aliases.
- Generate random short URLs.
- Redirect from short URLs to the original long URLs.
- React-based frontend interface.

---

## Project Structure

### Backend (`/BACKEND`)

```
BACKEND/
├── app.js
├── .env
├── package.json
├── package-lock.json
└── src/
    ├── config/
    ├── controller/
    ├── dao/
    ├── middleware/
    ├── models/
    ├── routes/
    ├── services/
    └── utils/
```

- **app.js**: Main entry point for the backend server.
- **.env**: Environment variables (not committed).
- **src/config/**: Configuration files (e.g., database connection).
- **src/controller/**: Route handler logic.
- **src/dao/**: Data access objects.
- **src/middleware/**: Express middlewares.
- **src/models/**: Mongoose models.
- **src/routes/**: API route definitions.
- **src/services/**: Business logic.
- **src/utils/**: Helper functions.

### Frontend (`/FRONTEND`)

```
FRONTEND/
├── src/
│   ├── api/
│   ├── components/
│   ├── pages/
│   ├── routing/
│   ├── store/
│   ├── utils/
│   ├── RootLayout.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── README.md
└── .gitignore
```

- **src/api/**: API utility functions.
- **src/components/**: Reusable React components.
- **src/pages/**: Page-level components.
- **src/routing/**: Routing configuration.
- **src/store/**: State management (if used).
- **src/utils/**: Utility functions.
- **RootLayout.jsx**: Main layout component.
- **index.css**: Global styles.
- **main.jsx**: Entry point for the frontend.

---

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or Atlas)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yash-vashist/UrlShortner.git
   cd UrlShortner
   ```

2. **Backend setup**
   ```bash
   cd BACKEND
   npm install
   # Configure .env with MongoDB URI and other settings
   npm start
   ```

3. **Frontend setup**
   ```bash
   cd ../FRONTEND
   npm install
   npm start
   ```

4. **Access the application**
   - Frontend: `http://localhost:5173`
   - Backend: `http://localhost:3000` (default)

License
This project is licensed under the MIT License.