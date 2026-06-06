<div align="center">
  <h1>🎓 PHP Student Registry</h1>
  <p><em>Sistema de Registro Académico en PHP Vanilla — Gestión de Estudiantes, Notas y Expedientes</em></p>

  [![PHP](https://img.shields.io/badge/PHP-7.4%2B-blue.svg)]()
  [![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)]()
  [![Status](https://img.shields.io/badge/Status-Completado-success.svg)]()
</div>

---

## 🎯 Contexto

Aplicación de gestión académica construida en PHP nativo (sin frameworks) y MySQL, diseñada para funcionar en servidores simples como XAMPP o Laragon. Permite llevar el registro completo de estudiantes, materias, calificaciones y constancias académicas.

Este proyecto fue un precursor directo del **SGE - Sistema de Gestión Escolar** (Servicio Comunitario), y sirvió como prueba de concepto para validar flujos de inscripción, gestión de notas y generación de reportes antes de migrarlo a una arquitectura Electron + React.

---

## ✨ Funcionalidades

| Módulo | Descripción |
|---|---|
| 👤 **Registro de Estudiantes** | Alta, baja y edición de alumnos con datos personales completos |
| 📚 **Gestión de Materias** | CRUD de asignaturas por período académico |
| 📊 **Calificaciones** | Registro de notas por materia, lapso y estudiante |
| 🖨️ **Constancias** | Generación de documentos académicos imprimibles |
| 🔐 **Autenticación** | Login con roles (Admin / Docente) y control de acceso por sección |

---

## 🛠️ Stack Tecnológico

| Capa | Tecnología |
|---|---|
| **Backend** | PHP 7.4+ nativo (sin frameworks como Laravel o Symfony) |
| **Frontend** | HTML5 + CSS3 + Bootstrap para responsividad |
| **Base de Datos** | MySQL / MariaDB con consultas PDO parametrizadas |
| **Servidor** | Apache via XAMPP / Laragon |

**¿Por qué PHP nativo?**
Velocidad de despliegue y facilidad de mantenimiento por personal sin experiencia en Node.js o frameworks modernos. En instituciones con recursos de IT limitados, "funciona con XAMPP y un tutorial de YouTube" es una ventaja real.

---

## 🚀 Instalación

```bash
# 1. Descargar y colocar en la carpeta del servidor
#    Ejemplo: C:\xampp\htdocs\php-student-registry\

# 2. Crear la base de datos
#    phpMyAdmin → Nueva BD: 'student_registry_db'
#    Importar: database.sql

# 3. Configurar conexión
#    Editar: config/db.php con tus credenciales
```

---

## 🔗 Relación con el Proyecto Mayor

Este sistema fue la **primera versión funcional** de lo que eventualmente evolucionó en el **SGE - Sistema de Gestión Escolar** para el *Preescolar María Moñitos* como proyecto de Servicio Comunitario Universitario:

| Versión | Stack | Estado |
|---|---|---|
| **v1 — PHP Registry** | PHP + MySQL | ✅ Completado (este repo) |
| **v2 — SGE Desktop** | Electron + React + SQLite | ✅ En producción |
| **v3 — SGE Web** | Next.js + Supabase | ✅ Activo (Vercel) |

---

> Desarrollado por **Gustavo Matheus** · *Full Stack Developer*
