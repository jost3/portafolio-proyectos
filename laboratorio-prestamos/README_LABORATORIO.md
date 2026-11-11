# 🔬 Sistema de Control de Préstamos e Inventario de Laboratorio

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![Orchid](https://img.shields.io/badge/Orchid-Admin-7B61FF)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-Chatbot-3776AB?logo=python&logoColor=white)

Sistema web para **gestionar el inventario y los préstamos de instrumentos de laboratorio** de un instituto. Proyecto final de la carrera de Ingeniería de Software con IA en **SENATI**.

Incluye **tres tipos de usuario** con permisos distintos y un **prototipo de chatbot en Python** para consultar y crear préstamos conversando.

---

## 🖼️ Capturas

<!-- Usa DATOS FICTICIOS en todas las capturas. -->

| Login | Panel del administrativo |
|---|---|
| ![Login](img/01-login.png) | ![Panel admin](img/02-panel-admin.png) |

| Inventario de instrumentos | Solicitud de préstamo (alumno) |
|---|---|
| ![Inventario](img/03-inventario.png) | ![Solicitud](img/04-solicitud.png) |

| Validación de préstamos (docente) | Reportes |
|---|---|
| ![Validación](img/05-validacion.png) | ![Reportes](img/06-reportes.png) |

| Chatbot en Python |
|---|
| ![Chatbot](img/07-chatbot.png) |

---

## 🎯 El problema

Los préstamos de instrumentos del laboratorio se controlaban de forma manual: era difícil saber qué había disponible, quién tenía cada equipo y quién lo debía devolver.

## ✅ La solución

Un sistema único donde el alumno **solicita**, el docente **valida** y el personal administrativo **controla el inventario y los reportes**.

## 👥 Roles y permisos

| Rol | Qué puede hacer |
|---|---|
| **Administrativo** | Gestiona el inventario, los usuarios y los permisos. Consulta reportes. |
| **Docente** | Revisa y valida (aprueba o rechaza) las solicitudes de préstamo. |
| **Alumno** | Consulta instrumentos disponibles y solicita préstamos. |

## ✨ Funcionalidades

- 📦 **Inventario** de instrumentos y equipos.
- 📝 **Solicitud y validación de préstamos** con flujo de aprobación.
- 🔐 **Sistema de roles y permisos** por tipo de usuario.
- 📊 **Reportes** de préstamos e inventario.
- 🤖 **Chatbot (prototipo)** en Python para consultar y crear préstamos de instrumentos.
- <!-- TODO: agrega lo que falte: devoluciones, estados (pendiente/aprobado/devuelto), exportar a Excel/PDF, alertas de retraso, etc. -->

## 🛠️ Tecnologías

| Capa | Tecnología |
|---|---|
| Backend | PHP, **Laravel** |
| Panel y permisos | **Laravel Orchid** |
| Frontend | JavaScript, Blade |
| Base de datos | <!-- TODO: MySQL / MariaDB --> |
| Chatbot | **Python** <!-- TODO: librerías: requests, FastAPI, etc. --> |
| Control de versiones | Git y GitHub |

## 🗂️ Estructura

```
├── app/               # Lógica de la aplicación (modelos, controladores, pantallas Orchid)
├── database/          # Migraciones y seeders
├── resources/         # Vistas y recursos
├── routes/            # Rutas
├── chatbot/           # Prototipo de chatbot en Python   <!-- TODO: ajusta el nombre real -->
└── img/          # Capturas para este README
```

## ⚙️ Instalación

**Requisitos:** PHP <!-- TODO: versión -->, Composer, MySQL, Node.js, Python 3 (solo para el chatbot).

```bash
# 1. Clonar el repositorio
git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPO.git
cd NOMBRE-DEL-REPO

# 2. Instalar dependencias
composer install
npm install && npm run build

# 3. Configurar el entorno
cp .env.example .env
php artisan key:generate
# Edita .env con los datos de tu base de datos

# 4. Crear tablas y datos de demostración
php artisan migrate --seed

# 5. Crear un usuario administrador (Orchid)
php artisan orchid:admin admin admin@example.com TuContraseña

# 6. Levantar el servidor
php artisan serve
```

### Chatbot (opcional)

```bash
cd chatbot
pip install -r requirements.txt
python main.py     # TODO: ajusta el comando real
```

## 🔑 Usuarios de demostración

<!-- TODO: si tu seeder crea usuarios de prueba, ponlos aquí -->

| Rol | Usuario | Contraseña |
|---|---|---|
| Administrativo | `admin@example.com` | `...` |
| Docente | `docente@example.com` | `...` |
| Alumno | `alumno@example.com` | `...` |

## 🚀 Posibles mejoras

- Llevar el chatbot de prototipo a un servicio integrado al sistema.
- Notificaciones por correo para aprobaciones y devoluciones.
- <!-- TODO: otras ideas -->

## 👤 Autor

**Josué Cotera Bravo** — Estudiante de Ingeniería de Software (UTP) · Técnico en Ingeniería de Software con IA (SENATI)

- 📧 josuecotb@gmail.com
- 💼 LinkedIn: <!-- TODO: tu enlace -->
- 🐙 GitHub: [@TU-USUARIO](https://github.com/TU-USUARIO)
