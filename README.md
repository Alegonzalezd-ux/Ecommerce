# 🛒 Ecommerce  - Fullstack Project

Este es un proyecto de E-commerce moderno

<p align="left">
  <img src="https://img.shields.io" alt="Next.js" />
  <img src="https://img.shields.io" alt="TypeScript" />
  <img src="https://img.shields.io" alt="Tailwind CSS" />
  <img src="https://img.shields.io" alt="Supabase" />
</p>



---

## 🖼️ Preview


---

## 🚀 Tecnologías Utilizadas

### Frontend & UI
- **Next.js 15 (App Router):** Renderizado híbrido para máxima velocidad.
- **TypeScript:** Tipado estricto para evitar errores en producción.
- **Tailwind CSS:** Diseño responsivo y moderno basado en utilidades.
- **Lucide React:** Set de iconos limpios y consistentes.

### Backend & Cloud
- **Supabase:** Base de datos relacional (PostgreSQL), Autenticación y Storage de imágenes.
- **Stripe:** (Próximamente) Pasarela de pagos segura en modo test.

---

## 📦 Arquitectura del Proyecto

El proyecto sigue una estructura modular y escalable (Screaming Architecture):

```text
ecommerce/
├── frontend/             # Aplicación Next.js (Interfaz de usuario)
│   ├── app/              # Rutas y páginas (App Router)
│   ├── components/       # Bloques UI (ui, common, product, cart)
│   ├── lib/              # Configuración (Supabase Client, Utils)
│   ├── hooks/            # Lógica de estado personalizada (Custom Hooks)
│   └── types/            # Interfaces de TypeScript
└── .gitignore            # Protección de credenciales y archivos locales
