# EmployWise 👥

![React](https://img.shields.io/badge/React-19.0.0-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-6.1.0-646CFF?logo=vite)

EmployWise is a modern employee management single-page application built with React and Vite. It features a sleek iOS-inspired dark UI with beautiful animations and transitions.

![EmployWise Preview](https://i.imgur.com/YOUR_SCREENSHOT.png) <!-- Replace with your actual screenshot -->

## 🌟 Features

- **User Authentication** - Secure login system with token-based authentication
- **Employee Management** - View, edit and delete user profiles
- **Data Persistence** - Local storage for session management
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Dark Mode UI** - iOS-inspired dark theme for reduced eye strain
- **Pagination** - Efficient loading of employee data

## 🛠️ Technologies

- React 19.0.0
- React Router DOM 7.4.0
- Axios for API requests
- Custom CSS with iOS-inspired design
- Vite as build tool and dev server

## 🚀 Getting Started

### Prerequisites

- Node.js (v16+)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/employwise-app.git
   cd employwise-app
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Build for production
   ```bash
   npm run build
   # or
   yarn build
   ```

## 📱 Usage

### Login Credentials

The application uses [ReqRes](https://reqres.in/) as a fake API. Use the following credentials to log in:

- **Email**: eve.holt@reqres.in
- **Password**: cityslicka

### Key Functionality

1. **Authentication**: Log in using the provided credentials
2. **View Users**: Browse through the list of employees
3. **User Management**: Edit or delete user information
4. **Pagination**: Navigate between pages of employee data
5. **Responsive**: Test on different screen sizes for responsive behavior

## 🔌 API Information

This project uses [ReqRes](https://reqres.in/) - a hosted REST API that simulates real application scenarios with fake data.

API Endpoints used:
- `POST /api/login` - Authentication
- `GET /api/users?page={page}` - Fetch users with pagination
- `PUT /api/users/{id}` - Update user
- `DELETE /api/users/{id}` - Delete user

## 📂 Project Structure

```
employwise-app/
├── public/            # Static files
├── src/
│   ├── components/    # Reusable UI components
│   ├── pages/         # Page components
│   ├── services/      # API services
│   ├── App.jsx        # Main application component
│   ├── index.css      # Global styles
│   └── main.jsx       # Application entry point
├── index.html         # HTML template
└── vite.config.js     # Vite configuration
```

## 📝 License

[MIT](LICENSE)

## 🙏 Acknowledgements

- [ReqRes](https://reqres.in/) for providing the fake API
- [React](https://reactjs.org/) team for the amazing library
- [Vite](https://vitejs.dev/) for the blazing fast build tool
