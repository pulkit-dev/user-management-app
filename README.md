# User Management Application

This project is a simple React-based web application where users can view, add, edit, and delete user details using the JSONPlaceholder API as a mock backend.

## Features

### User Interface
- Displays a list of users with details such as ID, First Name, Last Name, Email, and Department.
- Buttons for adding, editing, and deleting users.
- A form for inputting user details.

### Backend Interaction
- Interacts with JSONPlaceholder's `/users` endpoint to perform:
  - **GET**: Fetch user list.
  - **POST**: Add a new user.
  - **PUT**: Edit user details.
  - **DELETE**: Remove a user.

### Additional Features
- **Error Handling**: Displays messages if API requests fail.
- **Validation**: Ensures form inputs are properly filled.
- **Responsive Design**: Adapts to different screen sizes for better usability.

---

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/user-management-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd user-management-app
   ```

3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

4. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## Directory Structure

```
user-management-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── UserList.js
│   │   ├── UserForm.js
│   │   └── ErrorMessage.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
├── package.json
└── README.md
```

---

## Assumptions
- The JSONPlaceholder API is used only for demonstration and does not persist data.
- User details like "Department" are represented by the `company.name` field from the API.

---

## Challenges
- **Mock API Limitations**: JSONPlaceholder doesn't persist data, so changes are temporary.
- **Error Handling**: Managing edge cases like network failures required additional checks.

---

## Possible Improvements
- Implement pagination or infinite scrolling for the user list.
- Add unit tests using a library like Jest.
- Enhance the UI for better accessibility (e.g., keyboard navigation).
- Use a state management library like Redux for larger-scale applications.

---

## Dependencies
- React: For building the UI.
- Axios: For handling HTTP requests.

---

## Author
[Your Name](https://github.com/your-username)

Feel free to contribute or report issues!

