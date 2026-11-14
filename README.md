# The Marlow — Full-Stack Hotel & Food Management Web Application

## Folder Structure
```
the-marlow-fullstack/
├── frontend/
│   ├── index.html       # Complete multi-view UI ordered in logical workflow
│   ├── css/styles.css   # Warm stone & deep forest green theme
│   └── js/app.js        # Interactive kitchen queue, menu toggles & barcode expiry tracker
├── backend/
│   ├── server.js        # Node.js + Express REST API (Auth, Orders, Menu, Inventory)
│   ├── config/db.js     # MySQL connection pool
│   └── package.json     # Backend dependencies
└── database/
    └── schema.sql       # Relational database tables & seed data
```

## Quick Start
1. **Frontend Only (Instant Preview):** Open `frontend/index.html` directly in any browser.
2. **Full-Stack Setup:**
   - Import `database/schema.sql` into MySQL.
   - Navigate to `backend/`, run `npm install`, and start with `npm start`.
   - Open `http://localhost:5000` in your browser.
