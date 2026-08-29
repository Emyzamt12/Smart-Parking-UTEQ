# 🚗 UTEQ Smart Parking — Web Dashboard

Sistema de gestión y monitoreo en tiempo real para el parqueadero inteligente de la **Universidad Técnica Estatal de Quevedo (UTEQ)**. La plataforma web permite supervisar la disponibilidad de puestos, administrar la información de vehículos y usuarios autorizados, así como consultar la bitácora de accesos integrada con políticas de seguridad dinámicas desde la base de datos.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** React, Vite, CoreUI Icons & Components.
* **Backend & Base de Datos:** Supabase (PostgreSQL), Row Level Security (RLS) y columnas dinámicas enmascaradas.
* **Mapeo y UI:** Leaflet, CSS3 responsive.

---

## 🚀 Características Principales

* **Control de Acceso y Autorizaciones:** Clasificación en tiempo real de vehículos y propietarios registrados.
* **Seguridad de Datos:** Integración con vistas/políticas RLS de Supabase para la protección de identidades (enmascaramiento dinámico de cédulas de identidad).
* **Gestión de Puestos:** Visualización del estado de ocupación de espacios dentro del campus.
* **Historial y Bitácora:** Registro de entradas, salidas y estancias del parqueadero.
* **Filtros e Interfaz Adaptativa:** Búsqueda avanzada por placa, propietario o puesto sin recargar la vista.

---

## 💻 Instalación y Configuración Local

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/Emyzamt12/Smart-Parking-UTEQ)
   cd Smarth_ParquederoUTEQ