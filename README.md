# Creación de un Proyecto React Vite

==========================================================================
## **1 - Ejecutamos por Consola para Limpiar la memoria caché en NPM**
```
npm cache clear --force
```
==========================================================================
## **2 - Instalarmos Vite para empezar a desarrollar el proyecto React**
```
npm create vite@latest -- --template 
```
==========================================================================
## **3 - Instalarmos las dependencias a usar en el proyecto React**
```
npm install
```
```
npm install react-router-dom
```
```
npm install @reduxjs/toolkit react-redux
```
```
npm install axios
```
```
npm install -D tailwindcss postcss autoprefixer
```
```
npx tailwindcss init -p
```
- Dentro de tailwind.config.js - dentro de content: []
```
"./index.html",
"./src/**/*.{js,ts,jsx,tsx}",
```
- en el Index.css = 
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
==========================================================================
## **4 - Para Ejecutar de manera Local**
```
npm run dev -- --host
```