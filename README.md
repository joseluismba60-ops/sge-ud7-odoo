#  Implementación ERP Odoo 17 - PhoneLink Repair & Parts S.L.

Este repositorio contiene la documentación y configuración de un entorno ERP empresarial basado en **Odoo 17**, desplegado mediante **Docker** y documentado para la gestión integral del ciclo comercial.

##  Tecnologías y Arquitectura
* **ERP:** Odoo 17 (Community Edition)
* **Base de Datos:** PostgreSQL 15
* **Despliegue:** Docker Desktop & Docker Compose
* **Control de Versiones:** Git & GitHub

## 📂 Estructura de la Documentación

El proyecto se divide en las siguientes fases, documentadas en sus respectivas carpetas:

1. **[Instalación y Despliegue](./instalacion/instalacion-odoo.md):** Archivo `docker-compose.yml` y configuración del entorno de contenedores.
2. **[Perfil de la Empresa](./empresa/ficha-empresa.md):** Datos fiscales y configuración general de PhoneLink Repair & Parts S.L. en Sevilla.
3. **[Gestión de Identidad y Privilegios](./usuarios/usuarios-grupos-permisos.md):** Creación de usuarios, roles (Comercial, Ventas, Administración) y aplicación de grupos de acceso personalizados siguiendo el principio de mínimo privilegio.
4. **[Ciclo de Venta Completo](./venta/proceso-venta.md):** Demostración del flujo comercial (Presupuesto ➔ Pedido ➔ Albarán ➔ Factura ➔ Cobro) con segregación de funciones.

---
*Desarrollado como proyecto práctico de implantación de Sistemas de Gestión Empresarial.*