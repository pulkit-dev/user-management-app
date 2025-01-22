# User Management App

## Overview
A simple web application where users can view, add, edit, and delete user details using the JSONPlaceholder API as a mock backend. The application is built with React and styled with basic CSS.

## Features
- **View Users**: Fetch and display a list of users from the JSONPlaceholder API.
- **Add Users**: Simulate adding a new user via the API.
- **Edit Users**: Update user details using a form.
- **Delete Users**: Remove a user by sending a delete request.
- **Error Handling**: Graceful handling of API errors with user notifications.
- **Responsive Design**: Optimized for desktop and mobile.

## Tech Stack
- **Frontend**: React
- **Backend**: JSONPlaceholder (mock API)
- **HTTP Client**: Axios

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/user-management-app.git
   cd user-management-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open the application in your browser at `http://localhost:3000`.

## Deployment
### GitHub Pages
1. Install `gh-pages`:
   ```bash
   npm install gh-pages --save-dev
   ```
2. Add the following to `package.json`:
   ```json
   "homepage": "https://<your-username>.github.io/user-management-app",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```
3. Deploy the app:
   ```bash
   npm run deploy
   ```
4. Access your app at: `https://<your-username>.github.io/user-management-app`

### Vercel (Alternative)
1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Deploy the app:
   ```bash
   vercel
   ```
3. Access your app at the generated Vercel URL.

### Netlify (Alternative)
1. Build the app:
   ```bash
   npm run build
   ```
2. Drag and drop the `build/` folder to the Netlify dashboard.
3. Access your app at the generated Netlify URL.

## Folder Structure
```
user-management-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── UserForm.js
│   │   └── UserList.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
├── package.json
└── README.md
```

## Challenges & Improvements
### Challenges
- Handling API errors and simulating backend operations with JSONPlaceholder.
- Designing a responsive and intuitive UI within limited time.

### Improvements
- Implement actual backend integration for persistent data storage.
- Add pagination or infinite scrolling for large datasets.
- Enhance the UI with a modern CSS framework like Tailwind or Material-UI.
- Write unit tests using Jest or React Testing Library.

## License
This project is open-source and available under the MIT License.

---
Developed by Pulkit Patodia.

