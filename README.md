# 🚗 Smart Parking UTEQ

Sistema web para la gestión inteligente del parqueadero de la Universidad Técnica Estatal de Quevedo (UTEQ). La plataforma permite visualizar, administrar y controlar el ingreso de vehículos, propietarios y puestos disponibles de forma centralizada y segura.

## ✨ Funcionalidades principales

- Gestión de vehículos registrados
- Control de propietarios y usuarios autorizados
- Visualización del estado del parqueadero en tiempo real
- Consulta de historial de acceso y salida
- Filtrado por placa, propietario o información relevante
- Interfaz responsiva y moderna basada en React + CoreUI
- Integración con Supabase para almacenamiento y seguridad de datos

## 🛠️ Tecnologías utilizadas

- React
- Vite
- CoreUI
- Supabase
- JavaScript
- CSS / SCSS

## 📁 Requisitos

Antes de iniciar, asegúrate de tener instalado:

- Node.js 18 o superior
- npm o yarn
- Cuenta de Supabase configurada

## ⚙️ Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/Emyzamt12/Smart-Parking-UTEQ.git
cd Smart-Parking-UTEQ
```

2. Instala las dependencias:

```bash
npm install
```

3. Ejecuta la aplicación en modo desarrollo:

```bash
npm run start
```

4. La aplicación estará disponible en:

```bash
http://localhost:5173
```

## 🔐 Variables de entorno

Crea un archivo `.env` en la raíz del proyecto y configura tus credenciales de Supabase:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🧩 Estructura del proyecto

```bash
src/
├── components/
├── hooks/
├── lib/
├── views/
├── App.jsx
├── routes.js
└── main.jsx
```

## 📌 Descripción del proyecto

Este proyecto busca optimizar la administración del parqueadero universitario mediante una herramienta digital que mejora la trazabilidad del acceso vehicular, facilita la organización de datos y reduce la carga operativa del personal encargado.

## 🤝 Autor

- Emy Zambrano

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
