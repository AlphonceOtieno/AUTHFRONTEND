# Login & Register Page - React App

A simple and modern React application featuring login and register pages with form validation, error handling, and responsive design.

## Features

- ✅ **Login Page** - Email and password authentication with validation
- ✅ **Register Page** - New user registration with form validation
- ✅ **Form Validation** - Client-side validation for all input fields
- ✅ **Error Handling** - Display validation errors to users
- ✅ **Responsive Design** - Works on desktop, tablet, and mobile devices
- ✅ **Modern UI** - Beautiful gradient design with smooth animations
- ✅ **Navigation** - Easy navigation between login and register pages using React Router

## Project Structure

```
src/
├── components/
│   ├── Login.js          # Login component with form validation
│   └── Register.js       # Register component with form validation
├── styles/
│   └── AuthPage.css      # Shared styling for auth pages
├── App.js                # Main app with routing setup
├── App.css               # Global styles
└── index.js              # React entry point
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

1. **Navigate to the project**
   ```bash
   cd c:\Users\HP\frontend
   ```

2. **Install dependencies** (if not already installed)
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open in browser**
   - The app will automatically open at `http://localhost:3000`
   - You'll be redirected to the login page

## Usage

### Login Page
- Navigate to `/login`
- Enter a valid email and password (minimum 6 characters)
- Click "Login" button
- Form validates email format and password length
- Switch to Register page via the link

### Register Page
- Navigate to `/register`
- Enter first name, last name, email, and password
- Confirm your password
- Form validates all fields and checks password match
- Successfully registered users can login
- Switch to Login page via the link

## Form Validation Rules

### Login Form
- **Email**: Required, must be a valid email format
- **Password**: Required, minimum 6 characters

### Register Form
- **First Name**: Required
- **Last Name**: Required
- **Email**: Required, must be a valid email format
- **Password**: Required, minimum 6 characters
- **Confirm Password**: Required, must match password

## Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode on [http://localhost:3000](http://localhost:3000)

### `npm test`
Launches the test runner in interactive watch mode

### `npm run build`
Builds the app for production to the `build` folder

### `npm run eject`
Ejects from Create React App (cannot be undone)

## Technologies Used

- **React** - JavaScript library for building user interfaces
- **React Router** - Client-side routing library
- **CSS3** - Styling with animations and gradients
- **Modern JavaScript (ES6+)** - Arrow functions, destructuring, etc.

## Features to Implement

The current implementation includes UI and validation. To make it production-ready, you can add:

1. **Backend Integration**
   - Connect to an authentication API
   - Replace `setTimeout` with real API calls

2. **Authentication State**
   - Use Context API or Redux for global state
   - Store user session/token

3. **Protected Routes**
   - Create a PrivateRoute component
   - Redirect unauthenticated users

4. **Password Recovery**
   - Add "Forgot Password" functionality

5. **Email Verification**
   - Implement email verification after registration

6. **Social Login**
   - Add Google, Facebook, or GitHub login options

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is free to use and modify.

## Support

For issues or questions, feel free to modify the code and extend it based on your needs!
