# WM TECHNOLOGY - Plataforma de IA Futurista

Plataforma SaaS premium de inteligencia artificial con diseño futurista minimalista, autenticación segura, sistema de pagos integrado y dashboard administrativo.

## 🎯 Características Principales

### Autenticación
- ✅ Login/Registro seguro
- ✅ Recuperación de contraseña
- ✅ JWT authentication
- ✅ Perfil de usuario y panel de cuenta

### Diseño
- ✅ Encabezado profesional con logo y menú
- ✅ Hero Section impactante con imagen IA futurista
- ✅ Glassmorphism y neon glow effects
- ✅ Animaciones suaves con Framer Motion
- ✅ Responsive design (mobile-first)
- ✅ Modo oscuro/claro

### Servicios
- 🤖 Inteligencia Artificial
- 🔐 Ciberseguridad
- 💻 Desarrollo Web
- 🛠️ Soporte Técnico
- 🌐 Redes y Servidores
- 🔒 Protección de Datos

### Sistema de Pagos
- 💳 Stripe API (tarjetas de crédito/débito)
- 💰 PayPal
- 🏦 Métodos digitales
- 📋 Historial y facturación

### Dashboard Administrativo
- 📊 Estadísticas y KPIs
- 👥 Gestión de usuarios
- 💵 Gestión de pagos
- 📈 Reportes

## 🛠️ Tecnologías

### Frontend
- React 18 + Vite
- Tailwind CSS (diseño futurista)
- Framer Motion + GSAP (animaciones)
- React Router (navegación)
- Axios (HTTP client)

### Backend
- Node.js + Express
- MongoDB Atlas (base de datos)
- Mongoose (ODM)
- JWT (autenticación)
- bcryptjs (encriptación de contraseñas)
- Stripe y PayPal APIs

## 📁 Estructura del Proyecto

```
wm-technology/
├── frontend/                    # React App
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   ├── hooks/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── tailwind.config.js
│   ├── vite.config.js
│   └── package.json
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── package.json
└── README.md
```

## 🚀 Inicio Rápido

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
npm install
npm run dev
```

## 🔑 Variables de Entorno

### Frontend (.env)
```
VITE_API_URL=http://localhost:5000
VITE_STRIPE_KEY=pk_test_xxxxx
```

### Backend (.env)
```
PORT=5000
MONGODB_URI=mongodb+srv://user:password@cluster.mongodb.net/wm-technology
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET=sk_test_xxxxx
PAYPAL_CLIENT_ID=xxxxx
NODE_ENV=development
```

## 📋 Fases de Desarrollo

- **FASE 1**: ✅ Configuración base (React, Express, Tailwind, MongoDB)
- **FASE 2**: 🔄 Frontend - Componentes principales
- **FASE 3**: 🔄 Backend - APIs y modelos
- **FASE 4**: 🔄 Integraciones - Stripe, PayPal, Email
- **FASE 5**: 🔄 Dashboard Administrativo
- **FASE 6**: 🔄 Diseño y animaciones avanzadas
- **FASE 7**: 🔄 Optimización y Deployment

## 📝 Licencia

MIT