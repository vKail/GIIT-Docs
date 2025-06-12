# Proyecto GITT - Sistema de Gestión de Inventario

## ¿Qué es GITT?

GITT (Gestor de Inventarios de Talleres Tecnológicos) es un sistema integral de gestión de inventario desarrollado para los Talleres Tecnológicos de la Facultad de Ingeniería en Sistemas, Electrónica e Industrial (FISEI) de la Universidad Técnica de Ambato.

El sistema permite registrar, visualizar, controlar y gestionar equipos, herramientas y materiales de los talleres mediante el uso de códigos de barras, facilitando la administración de recursos y el control de préstamos a estudiantes y docentes.

### Características Principales

- ✅ Registro de productos mediante códigos de barras
- 📊 Visualización completa del inventario con filtros avanzados
- 🏷️ Categorización por departamentos (Tecnología, Muebles, Electrónica, etc.)
- 📋 Sistema de préstamos para estudiantes y docentes
- 🔔 Notificaciones automáticas de recordatorios de devolución
- 👥 Control de acceso diferenciado por roles de usuario
- 📱 Interfaz responsiva adaptable a diferentes dispositivos

---

## Repositorio Backend - API RESTful

### Descripción

El backend de GITT es una API RESTful desarrollada con NestJS que implementa una arquitectura robusta y escalable para la gestión del inventario. Proporciona todos los servicios necesarios para la autenticación, autorización y manipulación de datos.

### Características Técnicas

- 🔐 **Autenticación JWT** con Passport para seguridad robusta
- 📈 **CRUD Completo** para todas las entidades del sistema:
  - Usuarios y roles
  - Productos e inventario
  - Categorías y departamentos
  - Préstamos y devoluciones
- 📧 **Sistema de Notificaciones**:
  - Recordatorios programados (Cron Jobs)
  - Alertas de vencimiento de préstamos
- 🛠️ **Herramientas de Desarrollo**:
  - Pre-commits con Husky
  - Auto-formateo con Prettier
  - Linting con ESLint

### Stack Tecnológico

| Categoría | Tecnología |
|-----------|------------|
| **Backend** | NestJS, Node.js 22.15, Bun |
| **Base de Datos** | PostgreSQL 17, Drizzle ORM |
| **Autenticación** | Passport-JWT |
| **DevOps** | Docker, Git |
| **Calidad de Código** | Husky, Prettier, ESLint |
| **Testing** | Postman |

### Estructura del Proyecto

```
src/
├── auth/          # Autenticación JWT
├── mail/          # Sistema de notificaciones
├── cron/          # Tareas programadas
├── common/        # Utilidades compartidas
└── prisma/        # Esquema DB y migraciones
```

### Requisitos del Sistema

- Node.js 22.15+
- Bun (opcional para desarrollo)
- PostgreSQL 17
- Docker (para desarrollo containerizado)

### **Link del Repositorio**
🔗 [https://github.com/pjimenez2510/gitt-api](https://github.com/pjimenez2510/gitt-api)

---

## Repositorio Frontend - Interfaz de Usuario

### Descripción

El frontend de GITT es una aplicación web moderna desarrollada con Next.js que implementa **Arquitectura Limpia** en el desarrollo frontend. Se enfoca especialmente en la validación y control de la implementación de autenticación y autorización, garantizando una experiencia de usuario segura y eficiente.

### Características Principales

- 🏗️ **Arquitectura Limpia**: Implementación de principios de Clean Architecture para un código mantenible y escalable
- 🔐 **Autenticación y Autorización**: Sistema robusto de control de acceso con validación en el frontend
- 📱 **Interfaz Responsiva**: Adaptable a computadoras, tablets y smartphones
- ⚡ **Rendimiento Optimizado**: Construido con Next.js para máxima velocidad
- 🎨 **UI/UX Intuitiva**: Diseño pensado para usuarios con conocimientos técnicos limitados

### Funcionalidades Implementadas

- **Gestión de Inventario**: Visualización completa con filtros avanzados
- **Registro de Productos**: Interfaz para escaneo de códigos de barras
- **Sistema de Préstamos**: Gestión completa de préstamos y devoluciones
- **Panel de Administración**: Control total para administradores del sistema
- **Notificaciones**: Sistema integrado de alertas y recordatorios

### Stack Tecnológico

- **Framework**: Next.js
- **Lenguaje**: TypeScript/JavaScript
- **Gestor de Paquetes**: npm
- **Node.js**: Versión 20.18.0

### Requisitos del Sistema

- Node.js (versión 20.18.0)
- npm (incluido con Node.js)

### **Link del Repositorio**
🔗 [https://github.com/vKail/inventory-management-frontend](https://github.com/vKail/inventory-management-frontend)

---

## Conclusión

El Proyecto GITT representa una solución integral y moderna para la gestión de inventarios en entornos académicos. La implementación se caracteriza por:

### Logros Principales

✅ **Backend Robusto**: API RESTful completa con autenticación JWT, sistema de notificaciones automatizadas y arquitectura escalable usando NestJS y PostgreSQL.

✅ **Frontend con Arquitectura Limpia**: Implementación de principios de Clean Architecture en el desarrollo frontend, asegurando código mantenible y escalable.

✅ **Seguridad Integral**: Sistema completo de autenticación y autorización implementado tanto en backend como frontend, con validación y control de acceso diferenciado.

✅ **Experiencia de Usuario Optimizada**: Interfaz responsiva e intuitiva que facilita la gestión del inventario para todos los tipos de usuarios.

✅ **Automatización**: Sistema de notificaciones automáticas y recordatorios programados que mejoran la eficiencia operativa.

### Impacto

El sistema GITT moderniza completamente la gestión de recursos en los Talleres Tecnológicos de FISEI, proporcionando:

- **Eficiencia Operativa**: Reducción significativa del tiempo de gestión de inventarios
- **Control Mejorado**: Seguimiento preciso de equipos y préstamos
- **Experiencia Digital**: Transición de procesos manuales a digitales
- **Escalabilidad**: Arquitectura preparada para crecimiento futuro

El proyecto demuestra la aplicación exitosa de tecnologías modernas y mejores prácticas de desarrollo, resultando en una solución que cumple con todos los requerimientos funcionales y no funcionales establecidos para la gestión eficiente del inventario académico.
