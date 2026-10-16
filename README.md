# 👋 Hola, soy Santiago Barrera

**Análisis y Desarrollo de Software (ADSO) — SENA, ficha 3535013** 🇨🇴

Me enfoco en desarrollo backend y sistemas que resuelven problemas reales: telemetría,
APIs, bases de datos, procesamiento de documentos con OCR y despliegue en la nube.

## 🛠️ Tecnologías

`Python` · `Flask` · `Node.js` · `Express` · `PostgreSQL` · `SQLite` · `JavaScript` ·
`Socket.io` · `Kotlin` · `Docker` · `Tesseract OCR` · `Git/GitHub` · `Render` · `Neon`

## 🚀 Proyectos destacados

### [DocuNova — Organizador de documentos con OCR](https://github.com/Santiago-Gohan/DocuNova)

[![Demo](https://img.shields.io/badge/Demo-en%20vivo-brightgreen)](https://docunova-v7za.onrender.com)

**¿Por qué lo hice?** Ordenar a mano los documentos de muchos estudiantes (actas,
cédulas, certificados, EPS…) es lento y propenso a errores. DocuNova lo automatiza:
detecta a cada persona, clasifica cada archivo por tipo con **OCR local en español** y
crea una carpeta por estudiante.

- 🔎 Detecta **nombre, tipo y número de documento** (CC/TI/CE/RC/PP/NIT)
- 🗂️ Crea una carpeta por persona con sus documentos clasificados (001–007)
- 🔐 Todo se procesa localmente: los documentos no se envían a terceros
- 🌙 Interfaz web con tema oscuro, barra de progreso y tour guiado

**Tecnologías:** Python · Flask · PyMuPDF · Tesseract OCR · SQLite/PostgreSQL · Docker · Render

```text
SANTIAGO_BARRERA_BARBOSA_CC_1031649321/
  001_ACTA_DE_COMPROMISO.pdf
  002_DOCUMENTO_DE_IDENTIDAD.pdf
  003_CERTIFICADO_ACADEMICO.pdf
  004_CERTIFICADO_EPS.pdf
```

### [EcoDrive — Plataforma de telemetría vehicular OBD-II](https://github.com/Santiago-Gohan/Ecodrive)

**¿Por qué lo hice?** Un motor que se sobrecalienta sin que nadie lo note termina en una
reparación costosa o en un vehículo varado. EcoDrive vigila la salud de una flota en tiempo
real: captura temperatura del motor y RPM con un adaptador OBD-II económico y genera alertas
automáticas de mantenimiento predictivo.

- 📊 Panel admin con dashboard, historial y gestión de flota
- 📱 App del conductor (PWA + Web Bluetooth) con simulador ECU integrado
- 🔔 Alertas en tiempo real por WebSocket (ECT > 105 °C)
- 🌐 Desplegado con URL fija: backend en Render + PostgreSQL en Neon

### [BiblioÚnica — Sistema de gestión de biblioteca universitaria](https://github.com/Santiago-Gohan/Bibliounica-server.)

[![Demo](https://img.shields.io/badge/Demo-en%20vivo-brightgreen)](https://bibliounica.onrender.com)

**¿Por qué lo hice?** Llevar el control de una biblioteca en papel (préstamos, devoluciones
e inventario) es un caos. BiblioÚnica digitaliza todo el proceso con dos roles bien separados
y un panel de administración.

- 📚 Inventario de libros con control de disponibilidad
- 🔄 Registro de préstamos y devoluciones por estudiante
- 👥 Dos roles: **bibliotecario** (admin) y **estudiante**
- ✅ Desplegado con URL fija en Render (base de datos SQLite/PostgreSQL)

**Tecnologías:** Python · Django · Django REST · SQLite/PostgreSQL · Render

### El Imperio — Tienda de hogar (loza, herramientas y utilidades)

**¿Por qué lo hice?** Un negocio de Cimitarra necesitaba mostrar su catálogo de productos
para el hogar en internet. El Imperio es una tienda web con categorías, fichas de producto
y un canal de contacto directo con los clientes.

- 🛍️ Catálogo organizado por **categorías y productos**
- ✉️ Formulario de **mensajes/contacto** de clientes
- 🧩 Backend API con Django REST Framework + frontend propio
- 📈 Pensado para apoyar el plan de ventas del negocio

**Tecnologías:** Python · Django · Django REST · SQLite/PostgreSQL · Render

## 📫 Contacto

- GitHub: [@Santiago-Gohan](https://github.com/Santiago-Gohan)
- Email: nnking919@gmail.com

---

> El esfuerzo de hoy es la fuerza de tu mañana: sigue adelante, da lo mejor de ti en
> cada paso y no pierdas de vista la voluntad de Dios, que guía tu camino.

**Hecho en Colombia 💙 SENA ADSO**
