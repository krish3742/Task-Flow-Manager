# Task Flow Manager Frontend

This is the **frontend** for **Task Flow Manager** — a visual task management tool that helps you **create**, **track**, and **visualize** tasks in a flowchart layout. Built with **React + Material-UI**, it offers a smooth, responsive interface powered by **React Flow** for interactive task mapping.

---

## Tech Stack

- **Framework**: React
- **UI Library**: Material-UI
- **Flowchart Visualization**: React Flow
- **API Communication**: Axios
- **State Management**: React State Hooks

---

## Installation

1. **Install dependencies**

   ```bash
   npm install
   ```

2. **Set environment variables**

   Create a `.env` file in the `frontend/` directory:

   ```env
   REACT_APP_BACKEND_URL=Your_Backend_API_URL
   ```

---

## Running the App

To start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

---

## Available Scripts

| Command         | Description                   |
| --------------- | ----------------------------- |
| `npm start`     | Start the development server  |
| `npm run build` | Build the app for production  |
| `npm test`      | Run tests                     |
| `npm run eject` | Eject the app from CRA config |

---

## Features

- **Task List View** – Display, add, edit, and delete tasks
- **Visual Flow View** – View tasks as nodes in a flowchart using React Flow
- **Responsive Design** – Optimized UI for all screen sizes with Material-UI
- **Snackbar Notifications** – Success/error alerts for user actions
- **Loading Indicator** – Smooth user experience with loading states

---

## Folder Structure

```
frontend/
├── public/
└── src/
    ├── components/
    │   ├── Loader.js       # Loading spinner
    │   ├── TaskFlow.js     # Flowchart representation of tasks
    │   └── TaskList.js     # Task list with add, edit, and delete features
    ├── services/
    │   └── ApiEndpoint.js  # API service functions
    └── App.js              # Main React component
```

---

## Future Enhancements

- **Role-Based Access Control**
- **Draggable Nodes**
- **Task Dependencies**
- **UI/UX Improvements**

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any queries, feel free to reach out:

- **Author**: Kshitij Agrawal
- **Email**: akshitij70@gmail.com
