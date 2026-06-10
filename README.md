# TandaApp

> Panel de administración web para la gestión de tandas (grupos de ahorro rotativo) en México.

---

## Descripción

TandaApp es un sistema web diseñado para que el organizador de una tanda pueda gestionar de forma digital a sus participantes, registrar pagos, controlar turnos y visualizar el estado financiero del grupo — eliminando el uso de cuadernos o WhatsApp y reduciendo errores.

---

## Objetivo

Desarrollar una aplicación web de administración (panel tipo POS) que permita al organizador de una tanda gestionar eficientemente a los participantes, registrar pagos, controlar turnos y visualizar el estado financiero del grupo.

---

## Tecnologías

| Capa | Tecnología |
|------|-----------|
| Runtime | Node.js |
| Framework backend | Express.js |
| Template engine | Pug |
| Estilos | Tailwind CSS |
| Base de datos | PostgreSQL (Supabase) |
| Control de versiones | Git / GitHub |
| Gestión de proyecto | Jira |
| Comunicación | Discord |

---

## Integrantes

| Nombre | Rol |
|--------|-----|
| Alejandro | Scrum Master / DB Admin |
| José | Backend Developer |
| Juan | Frontend Developer |
| Ángel | QA / Tester |
| Esmeralda | Analista / Documentador |

> IDGS 9°B — Universidad Tecnológica del Norte de Aguascalientes (UTNA)

---

## Estructura del Repositorio

```
TandaApp/
│
├── Documentacion/        # Contiene todos los documentos formales del proyecto:
│                         # plan de comunicación, manual de gestión, actas de reunión,
│                         # diagramas y cualquier entregable documental del equipo.
├── Codigo/               # Código fuente de la aplicación
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── views/
│   │   └── public/
│   └── package.json
├── Recursos/             # Capturas de pantalla, diagramas y archivos de apoyo
└── README.md
```

---

## Estrategia de Ramas

```
main
└── develop
    ├── feature/auth
    ├── feature/participantes
    ├── feature/turnos
    ├── feature/pagos
    ├── feature/dashboard
    └── feature/ui
```

- **main** — Rama de producción, solo recibe merges desde `develop`.
- **develop** — Rama de integración, base de trabajo del equipo.
- **feature/\*** — Una rama por funcionalidad, se fusionan a `develop` vía Pull Request.
