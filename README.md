# Fusion Shared Mode Basics

Este README resume los pasos iniciales para comenzar un proyecto de Fusion en **Shared Mode**.

## Descripción

Fusion Shared Mode es una de las topologías de red que ofrece Photon Fusion. En este modo, la autoridad de estado (`StateAuthority`) la tiene un “Cloud Room” en la nube, y los clientes envían entradas que luego son simuladas y confirmadas por dicho servidor centralizado. Shared Mode combina la simplicidad de desarrollo de Host Mode con la robustez de un servidor dedicado. :contentReference[oaicite:0]{index=0}

## Topologías de Fusion

Fusion soporta tres topologías principales:

- **Server Mode**: Un servidor dedicado con IP pública gestiona la simulación.  
- **Host Mode**: Un jugador actúa como host (servidor + cliente) y los demás se conectan a él.  
- **Shared Mode**: Una instancia en la nube (Photon Cloud) tiene la autoridad de estado y los clientes interactúan con ella. :contentReference[oaicite:1]{index=1}

> **Nota**: La elección de topología debe hacerse al inicio del desarrollo, pues afecta profundamente la arquitectura de tu código y el flujo de red.

## Tabla de Contenidos del Tutorial

El tutorial de Shared Mode está dividido en 6 secciones clave: :contentReference[oaicite:2]{index=2}

1. **Getting Started**  
   Configuración del proyecto y creación del AppId en Photon Dashboard.  
2. **Scene and Player**  
   Preparación de la escena de Unity y generación de un objeto jugador por cliente.  
3. **Movement & Camera**  
   Implementación de movimiento, salto y cámara asociada al jugador.  
4. **Network Properties**  
   Sincronización de datos del juego usando propiedades en red (`[Networked]`).  
5. **RPCs (Remote Procedure Calls)**  
   Uso de RPCs para invocar acciones en otros clientes o en la autoridad de estado.  
6. **Where to go Next**  
   Enlaces y recursos para profundizar en Fusion Shared Mode.

## Descarga

Puedes descargar la versión de ejemplo completa del tutorial:

| Versión | Fecha de lanzamiento | Enlace de descarga                                                      |
|---------|----------------------|-------------------------------------------------------------------------|
| 2.0.5   | 24 Feb 2025          | [Fusion Shared Basics 2.0.5 Build 779](https://dashboard.photonengine.com) |

---

> Este README forma parte de la documentación de tu aplicación basada en Photon Fusion Shared Mode. Para más detalles, consulta el tutorial completo en el sitio oficial de Photon Engine.
::contentReference[oaicite:3]{index=3}
