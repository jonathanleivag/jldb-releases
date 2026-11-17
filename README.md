# JLDB

Cliente de bases de datos para macOS con carpetas por entorno y protección de Producción.

Soporta **MySQL**, **MariaDB**, **PostgreSQL**, **MongoDB**, **ClickHouse** y **Redis**.

Este repositorio publica los instaladores (`.dmg`). El código fuente es privado.

## Instalación

```bash
brew tap jonathanleivag/tap
brew install --cask jldb
```

O en un solo paso:

```bash
brew install --cask jonathanleivag/tap/jldb
```

También puedes descargar el `.dmg` desde [Releases](https://github.com/jonathanleivag/jldb-releases/releases).

## Actualizar

```bash
brew update
brew upgrade --cask jldb
```

Versión actual: **[v0.2.15](https://github.com/jonathanleivag/jldb-releases/releases/tag/v0.2.15)**.

## Requisitos

- Mac con Apple Silicon (`arm64`)
- macOS 12 (Monterey) o posterior

## Gatekeeper

La app no está firmada con un Apple Developer ID.

- Si la instalas con Homebrew, el cask quita la marca de cuarentena automáticamente.
- Si descargas el `.dmg` a mano, macOS puede bloquearla la primera vez:  
  **Ajustes del Sistema → Privacidad y seguridad → Abrir igualmente**.

## Qué incluye

- Carpetas por entorno (QA, Producción, etc.) con protección de escrituras
- Confirmación y auditoría al escribir en conexiones protegidas
- Editor SQL / consultas con scripts guardados por conexión
- Árbol de tablas / colecciones / claves según el motor
- Desconectar una sesión o todas a la vez

## Enlaces

- [Releases](https://github.com/jonathanleivag/jldb-releases/releases)
- [Homebrew tap](https://github.com/jonathanleivag/homebrew-tap)
