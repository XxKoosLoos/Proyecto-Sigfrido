# Registro de cambios

Este archivo registra modificaciones posteriores a la auditoría técnica. Las fechas se expresan en UTC; no representan fechas originales de desarrollo.

## 2026-11-07

### Documentación del alcance actual

- **Motivo:** describir el estado verificable del prototipo y facilitar su evaluación profesional sin atribuir funcionalidades no implementadas.
- **Alcance real:** actualización exclusiva de `README.md` en el commit [`20eee0c`](https://github.com/XxKoosLoos/Proyecto-Sigfrido/commit/20eee0c56b862a047f0fc80c72df296ad9235629). Se documentaron estructura, dependencias declaradas, instrucciones propuestas de instalación y ejecución, limitaciones, atribución pendiente y fechas respaldadas por Git.
- **Validación:** se comprobó que el README publicado coincidía con el contenido preparado. No se ejecutó la aplicación ni se probaron las instrucciones de instalación.
- **Implementación:** esta actualización no modificó código, dependencias ni el entorno virtual, y conservó el historial original de Git.

### Creación de este registro

- **Motivo:** mantener trazabilidad de las modificaciones posteriores, conforme a la autorización del propietario.
- **Alcance real:** incorporación exclusiva de `CHANGELOG.md`, con la entrada documental anterior y este registro de creación. No se añadieron funcionalidades ni se reconstruyeron cambios históricos sin evidencia.

### Exclusiones de archivos locales — 2026-11-07 (UTC)

- **Motivo:** evitar incorporar nuevos entornos virtuales, cachés, configuraciones locales potencialmente sensibles y metadatos de editores.
- **Alcance:** incorporación de `.gitignore` en [`04e13e9`](https://github.com/XxKoosLoos/Proyecto-Sigfrido/commit/04e13e992f6317f2b436d34ed60996ceb2e5fac8) y actualización de este registro.
- **Validación:** el parche se comprobó en un repositorio temporal independiente: 11 rutas excluidas y cuatro rutas permitidas, incluidas fuentes y `.env.example`.
- **Límites:** los archivos ya versionados permanecen en Git; no se eliminaron entornos ni secretos históricos. No se modificaron código, dependencias ni historial original. Las plantillas `.env.example` requieren revisión de contenido antes de publicarse.
