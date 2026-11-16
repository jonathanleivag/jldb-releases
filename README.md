# JLDB

Cliente de bases de datos para macOS con carpetas por entorno y protección de Producción.
Soporta MySQL/MariaDB, MongoDB, ClickHouse y Redis.

Este repositorio publica los instaladores. El código fuente es privado.

## Instalación

```bash
brew install --cask jonathanleivag/tap/jldb
```

También puedes descargar el `.dmg` desde [Releases](https://github.com/jonathanleivag/jldb-releases/releases).

## Requisitos

- Mac con Apple Silicon (arm64).
- macOS 12 o posterior.

La app no está firmada con un Apple Developer ID. Si la instalas con Homebrew, el cask quita la
marca de cuarentena por ti. Si descargas el `.dmg` a mano, macOS la bloqueará la primera vez:
ábrela desde Ajustes del Sistema > Privacidad y seguridad > "Abrir igualmente".
