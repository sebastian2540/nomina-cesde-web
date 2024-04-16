# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# Dependencia de JSON Server
Ejercutar el comando en la carpeta back  npm i json-server, en el package.son de la carpeta back colocar el script 
"scripts": {
    "json": "json-server --port 5174 --watch database.json"
  }

# Servidor Base de datos
Ejecutar el comando en la carpeta back npm run json

# Servidor React
Ejercutar el comando en la carperta front npm run dev

# Dependencia Endpoint
Ejecutar el comando en la carpeta front npm i react-router-dom