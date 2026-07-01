# Sistema Web de Gestión Operativa Integral para Logística y Distribución Nexus S.A. de C.V.

Proyecto académico desarrollado para la asignatura **Control de Versiones**, aplicando Git, GitHub y el modelo de trabajo **Git Flow** para la administración colaborativa del código fuente.

---

# Índice

- Descripción del Proyecto
- Objetivo General
- Objetivos Específicos
- Tecnologías Utilizadas
- Metodología de Trabajo
- Estructura del Proyecto
- Flujo de Trabajo (Git Flow)
- Organización del Repositorio
- Integrantes del Equipo
- Instalación
- Estado del Proyecto
- Buenas Prácticas Implementadas
- Licencia

---

# Descripción del Proyecto

El presente proyecto consiste en el desarrollo de un **Sistema Web de Gestión Operativa Integral** para la empresa ficticia **Logística y Distribución Nexus S.A. de C.V.**

El sistema tiene como finalidad optimizar la administración de proveedores, inventarios, pedidos y procesos logísticos mediante una plataforma web moderna, permitiendo mejorar la organización de la información, facilitar el trabajo colaborativo y mantener un adecuado control de las operaciones de la empresa.

Durante el desarrollo del proyecto se implementó un flujo de trabajo basado en **Git Flow**, permitiendo administrar correctamente las versiones del software y coordinar el trabajo de cada integrante del equipo.

---

# Objetivo General

Desarrollar un sistema web que facilite la administración de los procesos operativos de la empresa mediante tecnologías modernas de desarrollo y un sistema de control de versiones que garantice un trabajo colaborativo, organizado y seguro.

---

# Objetivos Específicos

- Administrar la información de proveedores.
- Gestionar productos e inventarios.
- Controlar pedidos y distribución.
- Implementar un repositorio utilizando GitHub.
- Aplicar el flujo de trabajo Git Flow.
- Organizar el desarrollo por módulos independientes.
- Mantener un historial de cambios mediante Git.

---

# 🛠 Tecnologías Utilizadas

| Tecnología | Uso |
|------------|------------------------------------------------|
| Vue.js | Desarrollo del Frontend |
| Nest.js | Desarrollo del Backend |
| MySQL | Base de Datos |
| Git | Control de Versiones |
| GitHub | Repositorio Remoto |
| Scrum | Gestión del Proyecto |

---

# Estructura del Proyecto

```text
Sistema-Gestion-Nexus
│
├── backend/
│   └── API REST desarrollada con Nest.js
│
├── database/
│   └── Scripts y modelos de la Base de Datos
│
├── docs/
│   └── Documentación técnica del proyecto
│
├── frontend/
│   └── Aplicación desarrollada con Vue.js
│
├── README.md
│
└── .gitignore
```

---

# Flujo de Trabajo (Git Flow)

Para el desarrollo del proyecto se implementó la estrategia **Git Flow**, permitiendo mantener un desarrollo organizado y colaborativo.

## Ramas utilizadas

| Rama | Descripción |
|------|-------------|
| **main** | Contiene la versión estable del sistema. |
| **develop** | Integra todas las funcionalidades desarrolladas. |
| **feature/frontend** | Desarrollo del módulo Frontend. |
| **feature/backend** | Desarrollo del módulo Backend. |
| **feature/database** | Desarrollo de la Base de Datos. |
| **feature/testing-docs** | Desarrollo de pruebas y documentación. |
| **release/1.0** | Preparación de la versión final. |
| **hotfix** | Corrección de errores críticos. |

### Flujo de trabajo

```text
main
 │
 ├───────────────┐
 │               │
 ▼               │
develop──────────┘
 │
 ├── feature/frontend
 │
 ├── feature/backend
 │
 ├── feature/database
 │
 ├── feature/testing-docs
 │
 ▼
release/1.0
 │
 ▼
main
 │
 ▼
hotfix
```

---

# Organización del Repositorio

Cada integrante desarrolla sus actividades dentro de una rama independiente (**feature**) para evitar conflictos entre los cambios realizados.

Posteriormente, las modificaciones son integradas a la rama **develop**, donde se realizan pruebas antes de ser incorporadas a la rama **main**, garantizando la estabilidad del proyecto.

---

# 👨‍💻 Integrantes del Equipo

| Integrante | Responsabilidad |
|------------|----------------|
| Fernanda Hernández | Scrum Master / Frontend |
| Alan Javier Caamal | Backend |
| Juan Daniel Almeida | Base de Datos |
| Eloisa Hernández | Pruebas y Documentación |

---

# Instalación

## Clonar el repositorio

```bash
git clone https://github.com/AlanCaamal/Sistema-Gestion-Nexus.git
```

## Entrar al proyecto

```bash
cd Sistema-Gestion-Nexus
```

## Instalar dependencias

Frontend

```bash

```

Backend

```bash

```

---

# 📊 Estado del Proyecto

**Versión:** 1.0

**Estado:**

En desarrollo

Actualmente el proyecto se encuentra en fase de implementación de módulos y documentación utilizando GitHub como plataforma para el control de versiones.

---

# Buenas Prácticas Implementadas
- Uso de Git como sistema de control de versiones.
- Repositorio remoto administrado mediante GitHub.
- Aplicación del modelo Git Flow.
- Organización modular del proyecto.
- Trabajo colaborativo por ramas.
- Documentación continua.
- Historial de cambios mediante commits.
- Separación entre desarrollo, pruebas y versión estable.

---

# Asignatura

**Control de Versiones**

Proyecto desarrollado con fines académicos.

---

# 📄 Licencia

Este proyecto fue elaborado exclusivamente para fines educativos como parte de las prácticas de la asignatura **Control de Versiones**.

---

# Equipo de Desarrollo

**Sistema Web de Gestión Operativa Integral para Logística y Distribución Nexus S.A. de C.V.**
