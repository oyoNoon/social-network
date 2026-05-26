# SocialNetwork

A full-stack social networking application built with Node.js backend and React frontend.

## 📁 Project Structure

```
SOCIALNETWORK/
│
├── api/                          # Backend API Server
│   ├── controllers/              # API endpoint controllers
│   │   ├── auth.js              # Authentication logic
│   │   ├── post.js              # Post management
│   │   └── user.js              # User management
│   ├── routes/                  # API route definitions
│   ├── connect.js               # Database connection setup
│   ├── index.js                 # API entry point
│   ├── package.json             # API dependencies and scripts
│   ├── node_modules/            # API dependencies (auto-generated)
│   └── package-lock.json        # Dependency lock file
│
├── client/                       # Frontend React Application
│   ├── public/                  # Static public assets
│   │   ├── images/              # Image files
│   │   └── fonts/               # Font files
│   ├── src/                     # React source code
│   │   ├── assets/              # Static assets (images, icons)
│   │   ├── components/          # Reusable React components
│   │   │   ├── Posts.js
│   │   │   ├── Comments.js
│   │   │   ├── Navbar.js
│   │   │   └── ...
│   │   ├── context/             # React Context API
│   │   │   └── AuthContext.js
│   │   ├── pages/               # Page components
│   │   │   ├── Home.js
│   │   │   ├── Profile.js
│   │   │   ├── Login.js
│   │   │   └── ...
│   │   ├── App.js               # Main App component
│   │   ├── axios.js             # Axios API client configuration
│   │   └── style.scss           # Global styles
│   ├── package.json             # Client dependencies and scripts
│   ├── package-lock.json        # Dependency lock file
│   └── node_modules/            # Client dependencies (auto-generated)
│
├── .gitignore                   # Git ignore rules
├── .gitattributes               # Git attributes configuration
├── package-lock.json            # Root dependency lock file
└── README.md                    # Project documentation

```

## 🚀 Getting Started

### Backend Setup (api/)
```bash
cd api
npm install
npm start
```

### Frontend Setup (client/)
```bash
cd client
npm install
npm start
```

## 📚 Key Components

### Backend (`/api`)
- **Controllers**: Handle business logic for authentication, posts, and users
- **Routes**: Define API endpoints
- **Database**: Connected via `connect.js`

### Frontend (`/client`)
- **Components**: Reusable UI components (Posts, Comments, Navbar)
- **Context**: State management using React Context (AuthContext)
- **Pages**: Page-level components (Home, Profile, Login)
- **Styles**: Global SCSS styling

## 🛠️ Technologies

- **Backend**: Node.js, Express
- **Frontend**: React
- **API Communication**: Axios
- **Database**: MongoDB (assumed from structure)

## 📝 Notes

- `node_modules/` directories are auto-generated and should be ignored in Git (see `.gitignore`)
- Dependencies are managed via `package.json` files in both `/api` and `/client`
