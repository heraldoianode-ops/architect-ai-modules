# architect-ai-modules
## Biblioteca de Módulos Reutilizables / Reusable Module Library

ES: Repositorio central de funciones modulares compartidas entre todos los proyectos de la SaaS.
EN: Central repository of modular functions shared across all SaaS projects.

### ES — Categorías / EN — Categories

| Carpeta | ES | EN |
|---|---|---|
| `auth/` | Autenticación y autorización | Authentication and authorization |
| `email/` | Correo transaccional | Transactional email |
| `payments/` | Pagos y suscripciones | Payments and subscriptions |
| `database/` | Queries y migraciones | Queries and migrations |
| `api/` | Middlewares y validación | Middlewares and validation |
| `ui/` | Componentes reutilizables | Reusable components |
| `utils/` | Utilidades generales | General utilities |
| `devops/` | Scripts de deploy | Deploy scripts |
| `windows/` | Apps escritorio Windows | Windows desktop apps |

### ES — Usar un módulo / EN — Use a module

En Claude Code dentro de cualquier proyecto:
```
INSTALAR MÓDULO [MOD-id o nombre]
```

### ES — Publicar un módulo / EN — Publish a module

Cuando una función es suficientemente genérica:
```
PUBLICAR MÓDULO [nombre de la función]
```

Claude Code extrae, documenta y sube automáticamente.

### ES — Estructura de cada módulo / EN — Each module structure
```
categoria/
└── nombre-modulo/
    ├── index.js          ← función principal
    ├── README.md         ← documentación bilingüe
    └── tests/
        └── index.test.js
```

### meta.json
Cerebro del library. Registra todos los módulos, patrones entre proyectos y deudas universales.
Brain of the library. Registers all modules, cross-project patterns and universal debts.

---
*ARCHITECT-AI v2.2 — heraldoianode-ops*
