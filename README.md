# Lingo Tribe App

App per prenotazioni di lezioni di lingua.

## Struttura

- `backend/`: Applicazione Node.js/Express
- `frontend/`: Interfaccia web HTML/CSS/JavaScript

## Deployment

### Backend (Railway)
1. Connetti il repository a Railway
2. Configura le variabili d'ambiente:
   - DB_HOST=srv1799.hstgr.io
   - DB_USER=u937909507_lingotribeus
   - DB_PASSWORD=********
   - DB_DATABASE=u937909507_lingotribedb

### Frontend (Hostinger)
1. Carica i file nella cartella `frontend/` su Hostinger
2. Aggiorna l'URL dell'API in `app.js`

## Sviluppo Locale

### Backend
```bash
cd backend
npm install
npm start
