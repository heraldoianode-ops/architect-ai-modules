# Templates — ARCHITECT-AI

## ES
Esqueletos estructurales canónicos. Al **CREAR un módulo o dominio nuevo** (regla R20), inspeccionar esta carpeta y replicar el esqueleto y los tipos **exactamente**. No modificar archivos núcleo del framework: extender por inyección de dependencias o composición.

- `DOM-TEMPLATE-ddd-domain.json` — Dominio DDD con capas `domain / application / infrastructure / interface`, conectores (Ports & Adapters), Secure Key Broker (cero acceso directo a entorno, R19) y skills 1:1 con casos de uso.

## EN
Canonical structural skeletons. When **CREATING a new module or domain** (rule R20), inspect this folder and replicate the skeleton and types **exactly**. Never modify core framework files: extend via dependency injection or composition.

- `DOM-TEMPLATE-ddd-domain.json` — DDD domain with `domain / application / infrastructure / interface` layers, connectors (Ports & Adapters), Secure Key Broker (zero direct env access, R19) and skills mapped 1:1 to use cases.
