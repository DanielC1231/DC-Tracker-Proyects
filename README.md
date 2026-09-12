# 💼 DC Tracker Proyects

Aplicación web progresiva (PWA) para gestionar proyectos, controlar tiempos, adjuntar archivos, llevar tu libreta de gastos, hacer presupuestos rápidos y cobrar lo que mereces.

---

## 📱 Guía de Instalación (PWA) — iOS & Android

Esta es una **Aplicación Web Progresiva (PWA)**. Puedes instalarla directamente en la pantalla de inicio de tu dispositivo móvil sin pasar por App Store o Google Play.

### 🍏 iPhone (iOS)

> ⚠️ **Nota:** Apple solo permite instalar PWAs desde su navegador nativo, **Safari**. No funciona desde Chrome en iOS.

1. Abre **Safari** en tu iPhone.
2. Entra a: `https://danielc1231.github.io/DC-Tracker-Proyects/`
3. Toca el botón **Compartir** (icono de cuadrado con flecha hacia arriba).
4. Desplázate y selecciona **Agregar al inicio** (+).
5. (Opcional) Edita el nombre del icono.
6. Toca **Agregar** arriba a la derecha.

### 🤖 Android

> 💡 **Nota:** Recomendamos **Google Chrome**, aunque funciona en cualquier navegador basado en Chromium.

1. Abre **Google Chrome**.
2. Entra a: `https://danielc1231.github.io/DC-Tracker-Proyects/`
3. Aparecerá un aviso abajo: **Instalar aplicación** o **Agregar a la pantalla principal**. Tócalo.
4. Si no aparece:
   * Toca el menú de **tres puntos** arriba a la derecha.
   * Selecciona **Instalar app** o **Agregar a la pantalla principal**.
5. Confirma con **Instalar**.

---

## ✨ Funcionalidades

### 📁 Proyectos
- Crear proyectos con **nombre, cliente, tarifa por hora y descripción**.
- Ver todos tus proyectos en una lista con su resumen (cliente, ingreso, horas, adjuntos, notas).
- Seleccionar un proyecto para trabajar con él en todas las demás secciones.
- Editar y eliminar proyectos.

### ⏱️ Timer
- Cronómetro con **iniciar / pausar / registrar**.
- Cada sesión se guarda con **fecha, duración y nota**.
- Campo de **dinero extra** por contratiempos.

### ✏️ Manual
- Agregar tiempo manual (horas + minutos) a un proyecto.
- Útil cuando olvidaste iniciar el timer.
- Campo de **dinero extra**.

### 📎 Adjuntos
- Adjuntar **tickets, facturas, contratos, cotizaciones, fotos o cualquier archivo** (máx. 5 MB).
- Vista previa de imágenes.
- Ver, guardar como… y eliminar cada adjunto.
- Navegación con teclado (**↑ ↓ Enter Delete**).

### 📓 Libreta
- Registrar **materiales y gastos** con concepto y precio.
- Total acumulado de todos los gastos.
- Seleccionar, eliminar individual o todas las notas.

### 🔍 Buscar
- Buscador en tiempo real por **nombre del proyecto, cliente o descripción**.

### 💵 Presupuesto
- Herramienta rápida para armar un presupuesto y **responderle al cliente**.
- Datos opcionales: **cliente** y **trabajo**.
- Agregar **materiales** uno por uno (descripción + precio).
- Agregar **mano de obra / servicios** uno por uno (descripción + precio).
- Botón **📁 Cargar materiales desde un proyecto** para traer todas las notas de un proyecto existente.
- Resumen automático con:
  - 🛠️ Total materiales
  - 🔧 Total mano de obra
  - 💰 **TOTAL PRESUPUESTO**
- Genera una **respuesta lista para copiar** con el desglose.
- **No se incluye en el reporte ni en el backup.** Es solo una herramienta de consulta interna.

### 📊 Reportes
- **Resumen general**: proyectos, horas totales, total a cobrar, extras.
- **Desglose del proyecto seleccionado**: horas, notas, total.
- **Historial de sesiones** con fecha, duración, nota y extra.
- **Vista previa del reporte** con todo el detalle.

### 📤 Exportar
- **📕 PDF (Todos)**: reporte completo con todos los proyectos.
- **📕 PDF (Proyecto Seleccionado)**: reporte individual del proyecto actual.
- **📊 CSV**: exporta la tabla de proyectos para Excel / Sheets.
- **💾 Backup JSON**: guarda todo el estado de la app para migrarlo o respaldarlo.
- **📂 Cargar Backup**: restaura desde un JSON.

---

## 🧮 Fórmulas

| Variable | Descripción |
|----------|-------------|
| **Horas trabajadas** | Suma de todas las sesiones registradas |
| **Tarifa por hora** | La configuras en cada proyecto |
| **Dinero extra** | Importes adicionales (gastos, imprevistos) |
| **Notas (materiales)** | Suma de todos los gastos de la libreta |
| **Total por proyecto** | `(Horas × Tarifa) + Extras + Notas` |

**Ejemplo:**
- Horas: `10 h × $20 = $200`
- Notas: `$100` (cable para barco)
- Extras: `$50`
- **Total: $350**

---

## 💱 Monedas

| Moneda | Símbolo | Código |
|--------|---------|--------|
| **Peso Mexicano** | $ | MXN |
| **Dólar Americano** | US$ | USD |

*La moneda se guarda automáticamente y persiste entre sesiones.*

---

## 📱 Compatibilidad

| Dispositivo | Navegadores |
|-------------|-------------|
| **PC (Windows / Linux)** | Chrome, Firefox, Edge, Opera |
| **Mac** | Chrome, Firefox, Safari |
| **Android** | Chrome, Firefox, Samsung Internet |
| **iPhone / iPad** | Safari, Chrome |

**¡Funciona en cualquier dispositivo con navegador moderno!**

---

## 🎯 ¿Para quién es?

- **Freelancers** — Controla tus proyectos y horas.
- **Autónomos** — Lleva el registro de clientes.
- **Pequeños equipos** — Organiza el trabajo.
- **Estudiantes** — Gestiona proyectos académicos.
- **Cualquier persona** que quiera organizar su tiempo y cobrar bien.

---

## 💾 Datos guardados

Todos los datos se guardan **automáticamente en tu navegador** (`localStorage`). **No necesitas cuenta ni registro.**

**Persistencia:**
- ✅ Proyectos, sesiones y adjuntos
- ✅ Notas y materiales
- ✅ Proyecto seleccionado
- ✅ Moneda preferida

> ⚠️ El **Presupuesto** NO se guarda (es temporal, solo mientras la app está abierta).

**Exporta un backup en JSON** para guardarlo en tu PC o restaurarlo cuando quieras.

---

## 🆓 Precio

**100% GRATIS** — Sin anuncios, sin registro, sin límites.

Si te gusta, puedes apoyarme con una donación. ¡Cualquier aporte es bienvenido! ❤️

---

## 📦 Versiones disponibles

| Versión | Descripción | Enlace |
|---------|-------------|--------|
| 🌐 **Web (PWA)** | Usable desde cualquier navegador, instalable en móvil | [GitHub Pages](https://danielc1231.github.io/DC-Tracker-Proyects/) |
| 💻 **EXE** | Versión para Windows (Python + Tkinter) | [itch.io](https://watecompany.itch.io/dc-tracker-proyects) |
| 📄 **HTML** | Archivo único para usar sin internet | [itch.io](https://watecompany.itch.io/dc-tracker-proyects) |

---

## 🛠️ Tecnologías utilizadas

- **HTML5** — Estructura y contenido
- **CSS3** — Estilos y diseño responsive
- **JavaScript** — Lógica y funcionalidad
- **localStorage** — Almacenamiento de datos
- **Python + Tkinter** — Versión EXE
- **ReportLab + Pillow** — Generación de PDFs (versión EXE)

---

## 📥 Instalación

### Opción 1: Usar la versión web (recomendada)
1. Visita [GitHub Pages](https://danielc1231.github.io/DC-Tracker-Proyects/)
2. ¡Empieza a usar la herramienta!

### Opción 2: Descargar y usar localmente
```bash
git clone https://github.com/danielc1231/DC-Tracker-Proyects.git
# Abrir el archivo index.html en el navegador
