# 📚 Proyectos Web con PHP, JavaScript, HTML, CSS y Bootstrap

Este repositorio contiene **8 proyectos completos** para desarrollar con **PHP + JavaScript + HTML + CSS + Bootstrap**, diseñados con fines **educativos y prácticos**.  
Cada proyecto incluye descripción, objetivos, requerimientos técnicos, estructura y entregables esperados.

---

## 🧮 Proyecto 1: Sistema Integral de Control de Biblioteca

### 📘 Descripción
Sistema para administrar una biblioteca digital y física.  
Permite gestionar libros, autores, préstamos, devoluciones y usuarios con roles diferenciados.

### 🎯 Objetivos
- CRUD completo con relaciones entre entidades.
- Autenticación con sesiones o tokens JWT.
- Envío de correos recordatorios (PHP Mailer).
- Reportes PDF y panel con gráficas de uso.

### ⚙️ Requerimientos
- PHP 8.2, MySQL.
- Tablas: `usuarios`, `libros`, `autores`, `prestamos`.
- Roles: **Administrador**, **Bibliotecario**, **Lector**.
- Reporte mensual en PDF y dashboard con Chart.js.

## 📂 Estructura General

```plaintext
biblioteca/
├── api/
│   ├── libros.php
│   ├── usuarios.php
│   └── prestamos.php
├── config/
│   ├── database.php
│   └── mailer.php
├── controllers/
├── models/
├── public/
│   ├── index.php
│   ├── dashboard.php
│   ├── reportes.php
│   └── login.php
└── assets/
    ├── css/
    ├── js/
    ├── img/
    └── charts/
```

### 📦 Entregables
- Código fuente funcional.
- Script SQL.
- Reporte PDF y DER.
- Capturas o video del flujo completo.

---

## 🛒 Proyecto 2: Plataforma de Ventas en Línea (Mini eCommerce)

### 🛍️ Descripción
Tienda en línea con catálogo de productos, carrito, gestión de usuarios y panel administrativo.

### 🎯 Objetivos
- CRUD con subida de imágenes.
- Carrito con LocalStorage y validación en servidor.
- API REST interna.
- Panel de ventas con gráficas y filtros.

### ⚙️ Requerimientos
- PHP, MySQL, Bootstrap, JS.
- Tablas: `usuarios`, `productos`, `ordenes`, `detalles_orden`, `reseñas`.
- Roles: **Administrador**, **Cliente**.
- Reporte de ventas, reseñas y promedios.

## 📂 Estructura General

```plaintext
ecommerce/
├── api/
│   ├── productos.php
│   ├── ordenes.php
│   └── usuarios.php
├── admin/
│   ├── productos.php
│   ├── ventas.php
│   └── dashboard.php
├── public/
│   ├── index.php
│   ├── producto.php
│   ├── carrito.php
│   ├── checkout.php
│   └── login.php
├── config/
│   └── database.php
└── assets/
```

### 📦 Entregables
- Código funcional.
- Base de datos SQL.
- Diagrama DER.
- Video mostrando flujo de compra.

---

## 🎓 Proyecto 3: Sistema de Control Escolar

### 🧩 Descripción
Plataforma educativa para registrar alumnos, materias y calificaciones, con generación de reportes.

### 🎯 Objetivos
- Autenticación multirol (admin, docente, alumno).
- CRUD completo con relaciones.
- Reportes PDF y Dashboard con Chart.js.
- Mensajería interna entre usuarios.

### ⚙️ Requerimientos
- Tablas: `usuarios`, `materias`, `calificaciones`, `asistencias`.
- Roles: **Administrador**, **Docente**, **Alumno**.
- Reporte semestral PDF o Excel.

## 📂 Estructura General

```plaintext
control-escolar/
├── api/
│   ├── alumnos.php
│   ├── materias.php
│   ├── calificaciones.php
│   └── asistencias.php
├── public/
│   ├── login.php
│   ├── dashboard.php
│   ├── calificaciones.php
│   └── reportes.php
├── controllers/
├── models/
└── assets/
```

### 📦 Entregables
- Código funcional.
- Reportes PDF.
- Capturas por rol.
- DER y casos de uso.

---

## 🧾 Proyecto 4: Sistema de Control de Inventario Empresarial

### 📦 Descripción
Aplicación para registrar productos, proveedores y movimientos de inventario.  
Incluye reportes, alertas y exportación de datos.

### 🎯 Objetivos
- CRUD avanzado con relaciones.
- Importación CSV.
- Alertas automáticas por correo.
- Dashboard con métricas.

### ⚙️ Requerimientos
- Tablas: `productos`, `movimientos`, `proveedores`, `usuarios`, `categorias`.
- PHP Mailer, Chart.js.
- Reportes PDF y Excel.

## 📂 Estructura General

```plaintext
inventario/
├── api/
│   ├── productos.php
│   ├── movimientos.php
│   └── proveedores.php
├── public/
│   ├── index.php
│   ├── productos.php
│   ├── movimientos.php
│   ├── proveedores.php
│   └── login.php
├── controllers/
├── models/
└── assets/
```

### 📦 Entregables
- Código funcional.
- Reportes PDF y Excel.
- Capturas del flujo.
- Documento técnico y DER.

---

## 🏨 Proyecto 5: Sistema de Reservaciones de Hotel Avanzado

### 🏩 Descripción
Sistema web para reservar habitaciones, administrar usuarios y visualizar estadísticas de ocupación.

### 🎯 Objetivos
- CRUD con validación de fechas.
- Tarifas dinámicas (temporada alta/baja).
- Reporte de ocupación PDF.
- Integración con mapas (LeafletJS o Google Maps).

### ⚙️ Requerimientos
- Tablas: `usuarios`, `habitaciones`, `reservas`, `tarifas`, `pagos`.
- Roles: **Administrador**, **Recepcionista**, **Cliente**.
- Envío de correos y dashboard gráfico.

## 📂 Estructura General

```plaintext
hotel/
├── api/
│   ├── habitaciones.php
│   ├── reservas.php
│   ├── pagos.php
│   └── usuarios.php
├── public/
│   ├── index.php
│   ├── reservas.php
│   ├── habitaciones.php
│   ├── login.php
│   └── dashboard.php
├── controllers/
├── models/
└── assets/
```

### 📦 Entregables
- Proyecto funcional.
- Base de datos SQL.
- Reporte PDF.
- Documento técnico y flujo de reserva.

---

## 🗂️ Proyecto 6: Gestor de Tareas Colaborativo (Kanban)

### 📋 Descripción
Aplicación tipo Trello con tableros, tareas, prioridades y estados arrastrables (Drag & Drop).

### 🎯 Objetivos
- CRUD jerárquico (proyectos → tareas).
- Actualización dinámica con AJAX.
- Filtros y estadísticas personales.
- Interfaz estilo Kanban con Bootstrap.

### ⚙️ Requerimientos
- Tablas: `usuarios`, `proyectos`, `tareas`.
- Roles: **Administrador**, **Usuario**.
- Gráficos de productividad.


## 📂 Estructura General

```plaintext
gestor-tareas/
├── api/
│   ├── proyectos.php
│   ├── tareas.php
│   └── usuarios.php
├── controllers/
├── models/
├── public/
│   ├── index.php
│   ├── tablero.php
│   ├── tareas.php
│   └── login.php
└── assets/
    ├── js/
    ├── css/
    └── img/
```

### 📦 Entregables
- Sistema funcional con tableros Kanban.
- Datos de ejemplo.
- Dashboard de métricas.
- DER y casos de uso.

---

## 🏥 Proyecto 7: Sistema de Citas Médicas en Línea

### 💉 Descripción
Sistema para agendar y administrar citas médicas, con control de usuarios, médicos y pacientes.

### 🎯 Objetivos
- CRUD con validación de horarios.
- Calendario dinámico con FullCalendar.js.
- Roles diferenciados y notificaciones.
- Reporte PDF de citas.

### ⚙️ Requerimientos
- Tablas: `usuarios`, `medicos`, `pacientes`, `citas`.
- Roles: **Administrador**, **Médico**, **Paciente**.
- Correo de confirmación.


## 📂 Estructura General

```plaintext
citas-medicas/
├── api/
│   ├── citas.php
│   ├── medicos.php
│   ├── pacientes.php
│   └── usuarios.php
├── controllers/
├── models/
├── public/
│   ├── index.php
│   ├── dashboard.php
│   ├── agenda.php
│   └── login.php
└── assets/
    ├── js/
    ├── css/
    └── img/
```

### 📦 Entregables
- Sistema operativo completo.
- Agenda dinámica.
- Reportes PDF.
- Documento técnico y DER.

---

## 🎓 Proyecto 8: Plataforma de Cursos y Evaluaciones (E-Learning)

### 🧠 Descripción
Plataforma educativa donde profesores crean cursos y evaluaciones, y alumnos realizan exámenes y obtienen certificados.

### 🎯 Objetivos
- Autenticación multirol (Admin, Profesor, Alumno).
- CRUD de cursos, exámenes y resultados.
- Subida de archivos y evaluaciones dinámicas.
- Generación de certificados PDF.
- Panel de progreso con estadísticas.

### ⚙️ Requerimientos
- Tablas: `usuarios`, `cursos`, `inscripciones`, `evaluaciones`, `preguntas`, `resultados`.
- Dashboard gráfico con Chart.js.
- Certificados automáticos en PDF.

## 📂 Estructura General

```plaintext
elearning/
├── api/
│   ├── cursos.php
│   ├── evaluaciones.php
│   ├── usuarios.php
│   └── resultados.php
├── controllers/
├── models/
├── public/
│   ├── index.php
│   ├── cursos.php
│   ├── evaluacion.php
│   ├── dashboard.php
│   └── login.php
└── assets/
    ├── js/
    ├── css/
    └── img/
```


