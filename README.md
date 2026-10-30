# Nexus 3.0 — Releases

Este repositorio solo contiene los instaladores y los metadatos de
actualizaciones de Nexus (Full, Lite y Técnicos). El código es privado.

## Cómo se actualiza la app

Nexus revisa este repo al abrir y cada 6 horas. Si hay una versión nueva,
la descarga en segundo plano y la instala **al cerrar**, con un backup previo
de la base. No se instala nada durante una venta.

| Edición | Instalador | Metadatos |
|---|---|---|
| Full | NexusFull-Setup-X.Y.Z.exe | ull.yml |
| Lite | NexusLite-Setup-X.Y.Z.exe | lite.yml |
| Técnicos | NexusTecnicos-Setup-X.Y.Z.exe | 	ech.yml |

## Instalación manual

Descargá el instalador de tu edición desde [Releases](../../releases/latest) y
ejecutalo. No cambies la carpeta que propone el instalador: ahí viven tus
datos y tu licencia.

## Verificar una actualización

Los feeds de respaldo están en updates/version-{full,lite,tech}.json.
Cada release incluye los tres instaladores, sus .blockmap y los .yml.
