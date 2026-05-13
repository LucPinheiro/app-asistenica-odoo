# Asistenica de Empleados: React + Odoo

Aplicación móvil de control de asistencia integrada con Odoo, desarrollada con **React Native + Expo**. Permite a los empleados registrar entradas y salidas de forma sencilla, incorporando verificación de ubicación y comunicación en tiempo real con el servidor Odoo mediante JSON-RPC.

### 🚀 Tecnologías utilizadas

- **React Native** + **Expo**
- **TypeScript**
- **Node.js & npm**
- **Odoo (JSON-RPC API)**
- **Android Studio / Xcode** (entorno móvil)
- **Expo CLI / EAS Build**

### ⚙️ Funcionalidades principales

- ✔️ Registro de asistencia (check-in / check-out)
- ✔️ Integración directa con Odoo  
- ✔️ Verificación de ubicación del usuario  
- ✔️ Configuración de entornos (dev / producción)  
- ✔️ Soporte multiplataforma (Android, iOS, Web)  
- ✔️ Ejecución mediante QR con Expo  

### 🔧 Configuración clave

- Conexión a Odoo mediante JSON-RPC  
- Configuración de base de datos y servidor  
- Variables de entorno por plataforma  
- Permisos de localización requeridos  

### 📦 Estructura relevante

- `odooApi.ts` → comunicación con Odoo  
- `config.tsx` → configuración del servidor  
- `useAttendanceMain.ts` → lógica principal  
- `useLocation.ts` → gestión de ubicación

