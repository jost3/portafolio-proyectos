# 📱 QR_ASISTE — Sistema de control de asistencia por QR

![Estado](https://img.shields.io/badge/estado-en%20producci%C3%B3n-brightgreen)
![Laravel](https://img.shields.io/badge/Laravel-Orchid-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

Sistema web de **asistencia escolar mediante códigos QR**. Reemplaza el registro manual en papel: cada alumno tiene un QR y su asistencia se registra al escanearlo, quedando disponible al instante para la institución.

Lo desarrollé **desde cero** y está **desplegado y en uso real** en una institución educativa, donde sigo manteniéndolo y agregando funcionalidades.

> 🔒 **Sobre este repositorio:** el sistema está en producción con datos reales de una institución, por lo que el código fuente es privado. Este repositorio documenta el proyecto con capturas (con datos de demostración). Con gusto muestro el código en una entrevista.

---

## 🖼️ Capturas

<!-- Todas las capturas deben usar DATOS FICTICIOS (nombres, DNI, correos). -->

| Inicio de sesión | Panel principal |
|---|---|
| ![Login](img/01-login.png) | ![Panel](img/02-panel.png) |

| Registro de asistencia por QR | Gestión de usuarios |
|---|---|
| ![Escaneo QR](img/03-escaneo-qr.png) | ![Usuarios](img/04-usuarios.png) |

| Reporte de asistencia |
|---|
| ![Reporte](img/05-reporte.png) |

---

## 🎯 El problema

El control de asistencia en papel es lento, propenso a errores y difícil de consultar. Los docentes pierden tiempo al inicio de clase y la institución no tiene un historial fácil de revisar.

## ✅ La solución

Un sistema web donde:

- Cada alumno cuenta con un **código QR** único.
- La asistencia se **registra al escanear el código**, con fecha y hora.
- Administración y docentes **consultan la asistencia** desde un panel.

## ✨ Funcionalidades

- Registro de asistencia mediante escaneo de código QR.
- Gestión de usuarios (alta, edición y baja).
- Base de datos con historial de asistencia.
- Panel administrativo construido con **Laravel Orchid**.
- <!-- TODO: agrega aquí lo que sí tiene: roles, reportes/exportación a Excel, justificaciones, tardanzas, etc. -->

## 🛠️ Tecnologías

| Capa | Tecnología |
|---|---|
| Backend | PHP, **Laravel** |
| Panel administrativo | **Laravel Orchid** |
| Base de datos | <!-- TODO: MySQL / MariaDB --> |
| Frontend | <!-- TODO: Blade, JavaScript, librería de lectura de QR --> |
| Despliegue | Hosting con dominio propio, en producción |

## 🚀 Estado y próximos pasos

- ✅ En producción y en uso diario.
- 🔄 En evolución constante, con nuevas funcionalidades.
- <!-- TODO: opcional, 1-2 mejoras próximas (notificaciones a padres, app móvil, etc.) -->

## 👤 Autor

**Josué Cotera Bravo** — Estudiante de Ingeniería de Software (UTP) · Técnico en Ingeniería de Software con IA (SENATI)

- 📧 josuecotb@gmail.com
- 💼 LinkedIn: <!-- TODO: tu enlace -->
- 🐙 GitHub: [@TU-USUARIO](https://github.com/TU-USUARIO)
