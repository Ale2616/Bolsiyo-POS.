<div align="center">

# 🟣 Bolsiyo POS

### Sistema de Punto de Venta e Inventario Inteligente

**Ultra rápido · Moderno · Multiplataforma**

---

*Diseñado para comercios independientes y micronegocios que necesitan control total de sus ventas, inventario y flujo de caja sin complicaciones.*

</div>

<br>

## 📋 Descripción

**Bolsiyo POS** es un sistema de punto de venta (POS) de nueva generación construido con tecnologías de alto rendimiento. Combina la velocidad nativa de **Rust** con una interfaz moderna y fluida para ofrecer una experiencia profesional en el manejo de ventas, productos, variaciones de inventario, caja registradora y reportes — todo sincronizado en tiempo real entre tus dispositivos.

A diferencia de los sistemas POS tradicionales basados en navegador, Bolsiyo se instala como una aplicación nativa en tu equipo, lo que garantiza tiempos de arranque instantáneos, consumo mínimo de recursos y funcionamiento confiable.

<br>

---

## 🖥️ Compatibilidad Técnica

### Versión para Windows

| Especificación | Detalle |
|---|---|
| **Sistemas compatibles** | Windows 10 y Windows 11 (Ediciones Home, Pro y Enterprise) |
| **Arquitectura** | Nativo para sistemas de 64 bits (`x86_64`) |
| **Requisito del sistema** | Microsoft Edge WebView2 Runtime (incluido por defecto en Windows 10/11) |
| **Formato de entrega** | Instalador ejecutable ligero (`.exe`) |

### Versión para Android

| Especificación | Detalle |
|---|---|
| **Sistemas compatibles** | Android 7.0 (Nougat / API 24) en adelante, hasta las versiones más recientes de Android |
| **Arquitectura de procesador** | Optimizado para dispositivos modernos con procesadores ARM de 64 bits (`aarch64-linux-android`) |
| **Formato de entrega** | Paquete de aplicación directa (`.apk`) sin depender de intermediarios |

<br>

---

## ✨ Características de Alto Valor

### 📱 Diseño Adaptativo Móvil Inteligente

Interfaz completamente optimizada que respeta el **Safe Area** (área segura) en dispositivos móviles. Los elementos interactivos nunca se cortan ni se superponen con la navegación por gestos, las barras del sistema o las pantallas con notch, garantizando una experiencia visual impecable en cualquier dispositivo.

### ⚡ Sincronización en Tiempo Real

Base de datos en la nube con **Supabase** que permite la actualización instantánea de inventario, cajas y reportes de ventas. Múltiples dispositivos pueden operar simultáneamente con datos siempre consistentes y actualizados al segundo.

### 🔒 Seguridad a Nivel de Fila (RLS)

Cada comercio opera en un entorno de datos completamente aislado. Las políticas de **Row Level Security** garantizan que cada negocio solo puede visualizar y modificar su propia información, protegiendo la integridad y privacidad de los datos mediante reglas de seguridad avanzadas aplicadas directamente en la base de datos.

### 🚀 Consumo Mínimo de Recursos

Gracias al motor de **Rust** y al framework **Tauri**, la aplicación arranca de forma instantánea y consume una fracción de la memoria RAM en comparación con sistemas POS tradicionales basados en Electron o tecnologías web pesadas. El resultado es una aplicación ligera que no compromete el rendimiento de tu equipo.

<br>

---

## ☁️ Infraestructura de Despliegue

Bolsiyo POS cuenta con un sistema de **compilación cruzada automatizado en la nube** mediante **GitHub Actions**. Cada lanzamiento verificado se empaqueta y distribuye de forma segura y reproducible:

- Las versiones para **Windows** se compilan en entornos `windows-latest` con el toolchain nativo de MSVC.
- Las versiones para **Android** se compilan en entornos `ubuntu-latest` con el Android NDK configurado específicamente para la arquitectura ARM64.
- Los artefactos resultantes se publican automáticamente como releases verificados, listos para su descarga e instalación inmediata.

<br>

---

<div align="center">

**Bolsiyo POS** — Control inteligente para tu negocio.

</div>
