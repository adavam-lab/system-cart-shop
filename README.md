# ADAVAM - E-Commerce & Admin Dashboard

Welcome to the ADAVAM project! This repository contains a full-stack e-commerce solution with multiple frontend interfaces and a robust backend API.

## 📸 Galería del Proyecto

<p align="center">
  <img src="img/slide.gif" alt="Galería del proyecto ADAVAM" width="900" />
</p>

---

## 🚀 Prerequisites

- Node.js
- npm or yarn
- PostgreSQL (Database)

## 🛠️ Getting Started

Since `node_modules` are gitignored, you will need to install the dependencies for the projects you are working on.

Navigate to the respective directory and install the dependencies:

```bash
# Example for the Admin frontend project
cd frontend-admin
npm install
npm run dev

# Example for the Client Flowbite project
cd frontend-flowbite
npm install
npm run dev

# Example for the backend API
cd api
npm install
npm run dev
```

## 🔐 Environment Variables

This project uses environment variables. Do not commit `.env` files. Instead, create a `.env.test` or `.env.example` file that contains the variable names without sensitive values. 

A `.env.test` has been created for your convenience in the corresponding folders. Make sure to copy it to `.env` and fill in the necessary values before running the application.

```bash
cp .env.test .env
```

---

## 🌍 Proyecto Open Source

ADAVAM es un proyecto **open source (código abierto)**. Esto significa que todo el código fuente (la API, el panel de administración y las tiendas para clientes) es público y cualquier persona puede verlo, usarlo, modificarlo y compartirlo, siempre que respete la licencia.

### ¿Qué significa que sea open source?

Un proyecto es open source cuando cumple dos condiciones:

1. **El código es accesible**: cualquiera puede leer cómo está construido el sistema, sin pedir permiso.
2. **Tiene una licencia abierta**: un documento legal que da permiso explícito para usar, copiar, modificar y distribuir el código. Sin licencia, un repositorio público *no* es open source: por ley, todos los derechos quedan reservados al autor.

Este proyecto usa la **licencia MIT** (ver el archivo [`LICENSE`](LICENSE)).

### ¿Por qué ADAVAM es open source?

- **Aprendizaje**: sirve como ejemplo real de un e-commerce full-stack (Node.js + Express, PostgreSQL/SQLite, React con Vite, Next.js con Flowbite y Tailwind). Estudiantes y desarrolladores pueden ver cómo se resuelven la autenticación con roles, el carrito de compras, las órdenes y la subida de imágenes.
- **Transparencia**: cualquiera puede revisar cómo se manejan los datos, la seguridad y la lógica de negocio. No hay "cajas negras".
- **Colaboración**: otras personas pueden reportar errores, proponer mejoras y enviar código. Más ojos sobre el código significan menos bugs y mejores ideas.
- **Reutilización**: en lugar de empezar desde cero, cualquiera puede tomar este sistema como base para su propia tienda y adaptarlo a sus necesidades.
- **Portafolio y comunidad**: mostrar el trabajo de forma abierta ayuda a que otros conozcan el proyecto y a construir comunidad alrededor de él.

### ¿Qué permite la licencia MIT?

| ✅ Puedes | 📌 Debes | ❌ Sin garantía |
|-----------|----------|-----------------|
| Usar el código con fines personales o comerciales | Mantener el aviso de copyright y el texto de la licencia en las copias del código | El software se entrega "tal cual", sin garantías |
| Modificarlo y adaptarlo | | El autor no es responsable por daños derivados de su uso |
| Distribuirlo y compartirlo | | |
| Usarlo dentro de proyectos privados o de código cerrado | | |

### 🤝 ¿Cómo contribuir?

1. Haz un **fork** del repositorio.
2. Crea una rama para tu cambio: `git checkout -b mi-mejora`
3. Haz tus cambios y un commit con un mensaje claro: `git commit -m "Agrega filtro por categoría"`
4. Sube tu rama: `git push origin mi-mejora`
5. Abre un **Pull Request** explicando qué cambiaste y por qué.

También puedes ayudar abriendo un **Issue** para reportar errores o sugerir nuevas funciones.

> ⚠️ **Importante:** nunca subas archivos `.env`, contraseñas, tokens ni datos reales de usuarios en tus contribuciones.

## 📄 Licencia

Distribuido bajo la licencia **MIT**. Consulta el archivo [`LICENSE`](LICENSE) para más información.
