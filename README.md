# OUISM - Tu ciudad en tiempo real

Plataforma para reportar incidentes urbanos en Santa Marta.

## Tecnologías
- Frontend: Vue.js
- Backend: Python + Flask
- Base de datos: MySQL

## Instalación

### Backend
```bash
cd backend
pip install flask flask-cors mysql-connector-python python-dotenv
```
Crea un archivo `.env` en la carpeta `backend`:
```
DB_HOST=127.0.0.1
DB_USER=root
DB_PASS=
DB_NAME=ciudad_db
```
```bash
python app.py
```

### Frontend
```bash
cd OUSI.SM
npm install
npm run serve
```

## Base de datos
Crea la base de datos `ciudad_db` en MySQL con las tablas `usuarios` e `incidentes`.
