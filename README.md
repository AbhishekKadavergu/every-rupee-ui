# React + TypeScript + Vite

# Every Rupee UI

Every Rupee UI is a modern, responsive React + TypeScript frontend for a personal finance manager. It helps users track income, expenses, and investments, manage budgets, view reports and interactive graphs, and receive notifications and daily reminders. The frontend is built with Vite and is Firebase-ready (planned backend: Firebase Auth, Firestore/Realtime DB, Cloud Functions).

**Key Features:**

- Track income and expenses with categories and tags.
- Manage investments and view portfolio summaries.
- Budgets with progress indicators and alerts.
- Interactive charts and reports for spending and income trends.
- Notifications and daily reminders for bills and goals.
- Firebase-ready: designed to integrate with Firebase Auth and Firestore.

**Tech Stack:**

- Frontend: React + TypeScript
- Bundler: Vite
- Styling: CSS (project files in `src/`)
- Planned backend: Firebase (Auth, Firestore/Realtime DB, Cloud Functions)

## Getting Started

Prerequisites:

- Node.js (LTS) and npm installed

Install and run locally:

```powershell
cd E:/REACT/every-rupee-ui
npm install
npm run dev
```

Build for production:

```powershell
npm run build
npm run preview
```

## Firebase Integration (Planned)

This project is designed to connect to Firebase for authentication and data persistence. Typical steps to wire Firebase:

1. Create a Firebase project and enable Auth + Firestore (or Realtime DB).
2. Add your Firebase config to environment variables or a `src/firebaseConfig.ts` file.
3. Implement Auth flows (signup/login) and Firestore collections for transactions, budgets, and reminders.

Environment example (do not commit secrets):

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
```

## Contributing

Contributions are welcome. Open issues for features or bugs, and submit pull requests. We'll update contribution guidelines as the project grows.

## License

This repository is currently unlicensed — add a license (for example, MIT) when ready.

---

More details and documentation will be added over time.
