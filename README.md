# AgroBitácora 🌿

**AgroBitácora** es una aplicación web desarrollada con [Astro](https://astro.build/) y [Tailwind CSS](https://tailwindcss.com/), orientada a agricultores que desean llevar un registro digital de sus tareas agrícolas.  
Actualmente se encuentra en fase inicial de desarrollo y evolución como herramienta de gestión sencilla, visual y ampliable.

---

## 🚜 ¿Qué permite hacer?

- Visualizar una lista de tareas agrícolas
- Indicar si una tarea está completada
- Organizar visualmente la información con diseño responsive
- Preparar futuras funciones como calendario, control de usuarios, y generación de PDF

---

## 🛠 Tecnologías utilizadas

- [Astro](https://astro.build/) – Framework web moderno y ultra rápido
- [Tailwind CSS](https://tailwindcss.com/) – Utilidades CSS para un diseño limpio y funcional
- JavaScript – Para mostrar dinámicamente los datos

---

## 📂 Estructura del proyecto

```
src/
├── components/        → futuros componentes reutilizables
├── layouts/           → layout base con fondo y estructura
├── pages/             → index.astro (página principal)
├── styles/            → Tailwind y estilos globales
└── data/              → Array simulado con tareas (tareas.js)
```

---

## 🚀 Cómo ejecutar localmente

```bash
git clone git@github.com:Bota93/AgroBitacora.git
cd AgroBitacora
npm install
npm run dev
```

Y abre en tu navegador:  
👉 `http://localhost:4321`

---

## 🧩 Próximos pasos

- [ ] Añadir funcionalidad para crear tareas desde formulario
- [ ] Guardar tareas en almacenamiento local o backend
- [ ] Vista de calendario semanal/mensual
- [ ] Control de usuarios y protección de datos
- [ ] Exportación en PDF de registros

---

## 📸 Captura de pantalla

![AgroBitácora UI](./public/screenshot.png)

*Diseño base con fondo dinámico y lista de tareas visibles.*

---

## 🧑‍🌾 Autor

**Adrián B.**  
Desarrollador web y estudiante DAM con interés en la tecnología rural y software útil para la vida real.

---

## 📄 Licencia

MIT – libre para aprender, modificar y colaborar.