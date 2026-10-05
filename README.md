# Wedding Cards

Simple React/Vite frontend + Node/Express backend + JSON storage.

## Run
1. Install Node.js 20+.
2. Terminal 1: `cd backend && npm install && npm start`
3. Terminal 2: `cd frontend && npm install && npm run dev`
4. Open the Vite URL, normally http://localhost:5173/admin/login

Default login: admin / admin123
Change credentials in backend/.env before deployment.

Public card: http://localhost:5173/card/1001

Cards are saved in backend/data/cards.json. The pasted code is rendered in an iframe, so it should be treated as trusted admin content.
