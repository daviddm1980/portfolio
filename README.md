# STAF Boilerplate

Este **boilerplate** proporciona una estructura base para iniciar proyectos web modernos utilizando **HTML**, **SCSS** y **JavaScript**.  
Incluye una configuración optimizada para el desarrollo y la generación de versiones listas para producción.

---

## 🚀 Requisitos previos

Antes de comenzar, asegúrate de tener instalado lo siguiente:

- [Node.js](https://nodejs.org/) (la versión recomendada se indica en el archivo `.nvmrc`)
- [npm](https://www.npmjs.com/) (instalado automáticamente con Node.js)
- Opcionalmente, [nvm](https://github.com/nvm-sh/nvm) para gestionar versiones de Node.js

---

## 📦 Instalación

1. Clona este repositorio o descarga el proyecto en tu ordenador:

   ```bash
   git clone https://github.com/drosellopa/staf_bolierplate.git
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd staf_bolierplate
   ```

3. Instala las dependencias necesarias:

   ```bash
   npm install
   ```

---

## 🧑‍💻 Entorno de desarrollo

Para iniciar el entorno de desarrollo con recarga automática en el navegador, ejecuta:

```bash
npm start
```

Esto iniciará un servidor local y abrirá el proyecto en tu navegador.  
Cada vez que modifiques los archivos fuente (`src/`), los cambios se aplicarán automáticamente sin necesidad de recargar manualmente.

---

## 🏗️ Generar versión para producción

Cuando el proyecto esté listo para desplegarse, ejecuta:

```bash
npm run build
```

Este comando genera una versión optimizada del proyecto dentro de la carpeta `dist/`,  
lista para subir a un servidor o servicio de alojamiento web.

---

## 🗂️ Estructura del proyecto

```
src/
├── assets/
│   ├── fonts/          → Fuentes del proyecto
│   ├── images/         → Imágenes y recursos gráficos
│   ├── scripts/        → Archivos JavaScript
│   └── styles/         → Archivos SCSS organizados por secciones
│       ├── _variables.scss       → Variables globales de estilo
│       ├── _dependencies.scss    → Importaciones y librerías
│       ├── main.scss             → Archivo principal de estilos
│       └── layouts/              → Estilos específicos por páginas o secciones
├── views/              → Fragmentos HTML reutilizables (footer, header, etc.)
└── index.html          → Página principal del sitio
```

---

## ⚙️ Archivos de configuración

| Archivo | Descripción |
|----------|--------------|
| `.gitignore` | Define los archivos y carpetas que no deben incluirse en el control de versiones. |
| `.nvmrc` | Indica la versión recomendada de Node.js para el proyecto. |
| `.posthtmlrc` | Configuración para el procesamiento de HTML mediante PostHTML. |
| `package.json` | Contiene las dependencias y scripts del proyecto. |

---

## 🧰 Scripts disponibles

| Comando | Descripción |
|----------|--------------|
| `npm start` | Inicia el entorno de desarrollo con servidor local y recarga automática. |
| `npm run build` | Genera la versión final optimizada del proyecto para producción. |
| `npm run clean` | Elimina archivos temporales o compilados (si está configurado). |

---

## 🧾 Licencia

Este proyecto se distribuye bajo una licencia libre.  
Puedes modificarlo, adaptarlo y reutilizarlo en tus propios desarrollos sin restricciones.

---

## 🌐 Repositorio oficial

[https://github.com/drosellopa/staf_bolierplate](https://github.com/drosellopa/staf_bolierplate)
