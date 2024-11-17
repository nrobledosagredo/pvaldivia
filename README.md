# Pastelería Valdivia

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)

Proyecto creado como parte de un proceso de aprendizaje en el desarrollo de aplicaciones web. El proyecto abarca tanto el **backend** como el **frontend** con **Node.js** y **React**, utilizando **MongoDB** para la base de datos. Además, integra **Socket.IO** para mensajería en tiempo real.

## Descripción

Este proyecto simula una tienda en línea de pastelería, con funcionalidades como:

- Visualización de productos de pastelería.
- Creación y gestión de cuentas de usuario.
- Realización de pedidos en línea.
- Panel de administración para gestionar productos y pedidos.
- Soporte en tiempo real para clientes mediante un sistema de chat.

El proyecto está estructurado en **microservicios** usando **Express** en el backend y una **SPA** en el frontend con **React**.

## Características

- **Backend**:
  - API RESTful con **Express**.
  - Gestión de usuarios y productos.
  - Integración con **MongoDB** para la base de datos.
  - Implementación de **Socket.IO** para chat en tiempo real.
  - Configuración de pagos con **PayPal**.
  
- **Frontend**:
  - Diseño responsivo con **React**.
  - Pantalla de inicio, detalles de productos, carrito de compras y historial de pedidos.
  - Autenticación de usuarios (registro, inicio de sesión).
  - Sistema de notificaciones en tiempo real para usuarios y administradores.

- **DevOps**:
  - Pipeline de integración continua con **Jenkins**.
  - Implementación y despliegue automatizado del backend y frontend.