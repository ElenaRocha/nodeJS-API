# Apollonia Dental Practice – Employee Management

Sistema de gestión interno para una clínica dental, desarrollado como proyecto de aprendizaje con **Node.js**.  
El objetivo es construir la base de una aplicación de gestión de empleados, pensada para escalar en el futuro hacia un sistema completo de gestión de personal y clientes.

## 🦷 Contexto del proyecto

Apollonia Dental Practice necesita una aplicación capaz de gestionar los empleados de la clínica y organizarlos por departamentos.  
En esta primera fase, el foco está en poder **crear y consultar empleados y departamentos**, sentando las bases para futuras funcionalidades más complejas.

Este proyecto forma parte de un curso práctico y está desarrollado fuera de la plataforma del mismo, utilizando un entorno local y contenedores Docker.

## 🛠 Stack Tecnológico

- Node.js & Express
- MongoDB & Mongoose
- Docker & Docker Compose

## ✅ Requerimientos actuales

- Crear registros de empleados con:
  - Nombre
  - Apellido
  - Departamento
- Listar los departamentos disponibles en la clínica.

## 🚀 Requerimientos futuros

- Crear registros de clientes.
- Asignar clientes a cada empleado.
- Gestionar información económica:
  - Pagos por cliente.
  - Ganancias por empleado.
- Registro de formaciones, especializaciones y proyectos.

## 📦 Instalación y puesta en marcha

Estas instrucciones permiten ejecutar el proyecto en un entorno local.  
El repositorio **no incluye** `node_modules` ni instalaciones de Node.js o MongoDB para mantenerlo ligero.

### 1. Requisitos previos

Asegúrate de tener instalado en tu sistema:

- Git
- Docker
- Docker Compose

> No es necesario instalar Node.js ni MongoDB localmente si se utiliza Docker.

### 2. Clonar el repositorio

```bash
git https://github.com/ElenaRocha/nodeJS-API.git
cd nodeJS-API
