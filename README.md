# Jira Clone Project

## 📝 Descripción

Este es un **clone de Jira**, diseñado para gestionar proyectos de forma eficiente con características como tareas dinámicas, tablas interactivas, funcionalidades drag-and-drop y visualización de datos. El objetivo principal es crear una herramienta poderosa y amigable para el manejo de equipos y proyectos utilizando tecnologías modernas y patrones arquitectónicos.

## 🚀 Tecnologías Utilizadas

### **1. Framework Principal y Soporte**
- **[Next.js](https://nextjs.org/)**: Framework principal para la aplicación, con soporte para:
  - Renderizado del lado del servidor (SSR).
  - Generación estática de páginas (SSG).
  - Optimización avanzada de rutas API e imágenes.
- **[React](https://reactjs.org/)**: Biblioteca para construir interfaces de usuario.
- **react-dom**: Renderiza componentes React en el DOM.

---

### **2. Gestión de Estado y Datos**
- **[@tanstack/react-query](https://tanstack.com/query/latest)**: Manejo eficiente de estados asíncronos.
- **[@tanstack/react-table](https://tanstack.com/table/latest)**: Creación de tablas avanzadas con paginación, filtrado y ordenación.

---

### **3. Interfaz de Usuario**
- **[@radix-ui/*](https://www.radix-ui.com/)**: Componentes accesibles y estilizados como menús y diálogos.
- **[lucide-react](https://lucide.dev/)**: Iconos SVG optimizados para React.
- **[tailwind-merge](https://github.com/dcastil/tailwind-merge)**: Combina y sobrescribe clases de TailwindCSS eficientemente.
- **[tailwindcss-animate](https://github.com/tailwindlabs/tailwindcss-animate)**: Animaciones predefinidas en TailwindCSS.
- **[clsx](https://github.com/lukeed/clsx)**: Manejo condicional de clases en React.

---

### **4. Validaciones y Formularios**
- **[zod](https://zod.dev/)**: Validación y manipulación de esquemas para formularios.
- **[@hookform/resolvers](https://react-hook-form.com/api/useform/resolver)**: Integración de zod con react-hook-form.
- **[react-hook-form](https://react-hook-form.com/)**: Manejo de formularios ligeros y eficientes.

---

### **5. Drag & Drop**
- **[@hello-pangea/dnd](https://hello-pangea.github.io/dnd/)**: Implementación de funcionalidades drag-and-drop para tableros interactivos.

---

### **6. Fechas y Calendarios**
- **[date-fns](https://date-fns.org/)**: Manejo eficiente de fechas.
- **[react-big-calendar](https://jquense.github.io/react-big-calendar/)**: Calendarios personalizables.
- **[react-day-picker](https://react-day-picker.js.org/)**: Selección interactiva de fechas.

---

### **7. Visualización de Datos**
- **[recharts](https://recharts.org/)**: Creación de gráficos y visualización de datos.

---

### **8. Backend y API**
- **[Hono](https://hono.dev/)**: Framework ligero para construir APIs rápidas.
- **[node-appwrite](https://appwrite.io/)**: SDK oficial para interactuar con Appwrite.

---

### **9. Notificaciones y Manejo Avanzado**
- **[sonner](https://sonner.dev/)**: Notificaciones personalizables.
- **[vaul](https://vaul.dev/)**: Manejo de animaciones en paneles y menús desplegables.

---

## 🛠️ Características del Proyecto
- **Tablero Kanban**: Maneja tareas con funcionalidades drag-and-drop.
- **Tablas Avanzadas**: Filtrado, ordenación y paginación interactiva.
- **Calendarios**: Visualización de tareas en fechas específicas.
- **Gráficos**: Estadísticas y reportes visuales.
- **Notificaciones**: Alertas en tiempo real para eventos importantes.
- **Validaciones Robustas**: Formularios validados con zod y react-hook-form.

---

## 🌐 Arquitectura del Proyecto
- **Frontend**: Construido con **Next.js** y **React**, utilizando componentes reutilizables y estilos modulares.
- **Backend**: API basada en **Hono**, interactuando con **Appwrite** para almacenamiento y autenticación.
- **Gestión de Estado**: Implementación de react-query para optimizar el manejo de datos remotos.
- **UI Dinámica**: Componentes accesibles con Radix UI y animaciones fluidas usando TailwindCSS.
