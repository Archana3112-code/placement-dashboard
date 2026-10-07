# Placement Desk – Student Placement Dashboard (React + Vite)
Run: `npm install && npm run dev` (Node 18+). Register a student first; accounts are stored in localStorage (mock auth).
Mock REST layer: `src/services/api.js` (swap for fetch calls using `VITE_API_URL`). State: `AuthContext`, `AppContext`.
Deploy: `npm run build`, then upload `dist/` to Netlify/Vercel (add an SPA rewrite to index.html).
