# 🛒 Ecommerce Name - Fullstack Project

Este es un proyecto de E-commerce moderno construido con **Next.js 15**, **Tailwind CSS** y **Supabase**. Diseñado para ser rápido, escalable y con una experiencia de usuario fluida.


---

## 🚀 Tecnologías Utilizadas

### Frontend
*   **Next.js 15** (App Router)
*   **TypeScript** para un tipado robusto.
*   **Tailwind CSS** para un diseño responsivo.
*   **Lucide React** (Iconos).

### Backend & Servicios
*   **Supabase** (PostgreSQL, Auth y Storage).
*   **Stripe** (Próximamente para pagos en modo test).

---

## 📦 Arquitectura del Proyecto

El proyecto está organizado de forma modular para facilitar su mantenimiento:

```text
ecommerce/
├── frontend/             # Aplicación Next.js
│   ├── app/              # Rutas y páginas
│   ├── components/       # UI Reutilizable (Atoms, Molecules)
│   ├── lib/              # Configuración de Supabase/Utils
│   └── hooks/            # Lógica de estado y efectos
└── (backend opcional)    # Lógica de servidor si aplica
