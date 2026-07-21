<div align="center">

# 🟣 Bolsiyo POS

### La Plataforma de Punto de Venta e Inventario Más Completa para tu Negocio

**Ultra rápido · Moderno · Multiplataforma · Inteligente**

---

*Empodera tu comercio con tecnología de última generación. Bolsiyo POS es la solución definitiva para comercios independientes, micronegocios, tiendas de barrio, restaurantes y puntos de recarga que necesitan control total de sus operaciones — sin complicaciones, sin mensualidades ocultas y sin curva de aprendizaje.*

</div>

<br>

## 🎯 ¿Por Qué Elegir Bolsiyo POS?

| Problema Común | Solución Bolsiyo |
|---|---|
| Sistemas POS lentos que consumen tu ancho de banda | ⚡ Aplicación nativa ultraligera con motor **Rust** |
| Perder ventas por no tener inventario actualizado | ☁️ Sincronización en tiempo real entre todos tus dispositivos |
| Miedo a perder datos o que otros vean tu información | 🔒 Seguridad a nivel de fila (RLS) con aislamiento total por negocio |
| Pagar cientos de miles por un sistema básico | 💰 Plan gratuito funcional + planes premium accesibles |
| No poder vender si no tienes computador a la mano | 📱 Disponible en **Windows** y **Android** con interfaz adaptativa |

<br>

---

## 🧩 Funcionalidades — Todo lo Que Tu Negocio Necesita

<br>

### 🛒 Punto de Venta (POS) — Vende Más Rápido que Nunca

El corazón de Bolsiyo. Una pantalla de venta diseñada para maximizar la velocidad de atención al cliente.

- **Búsqueda inteligente de productos** con filtro instantáneo por nombre, código de barras o categoría.
- **Lectura automática de códigos de barras** por peso (estándar GS1), ideal para fruterías, carnicerías y tiendas a granel que usan básculas con impresión de código.
- **Grilla visual de productos** con imágenes, precios y stock en tiempo real, organizada por categorías.
- **Carrito de compras dinámico** con ajuste de cantidades (+ / −), eliminación individual y resumen en tiempo real del total.
- **Múltiples métodos de pago**: Efectivo, Tarjeta de Crédito, Tarjeta de Débito, Nequi y Daviplata — todos configurados y listos para usar.
- **Descuentos y propina** aplicables al momento de la venta, con cálculo automático.
- **Venta a crédito (fiado)** con registro automático del cliente deudor, para que nunca pierdas el control de quién te debe.
- **Calculadora de devueltas integrada** con atajos de denominación colombiana ($1.000 / $2.000 / $5.000 / $10.000 / $20.000 / $50.000 / $100.000) y teclado numérico, para que calcules el cambio en menos de 2 segundos.
- **Suscripción en tiempo real a la base de datos**: si otro dispositivo modifica un producto o lo elimina, tu POS lo refleja al instante sin recargar la pantalla.

<br>

---

### 📦 Inventario Profesional — Control Absoluto de tus Productos

Gestiona todo tu catálogo de productos con herramientas profesionales que antes solo existían en sistemas costosos.

- **CRUD completo de productos**: crea, edita, elimina y consulta productos con nombre, precio de venta, precio de costo, código de barras, categoría, stock y descripción.
- **Imágenes de producto con compresión automática**: sube fotos desde tu teléfono o computador; Bolsiyo las comprime inteligentemente a JPEG de alta calidad sin exceder los 300 KB, garantizando rapidez sin sacrificar apariencia.
- **Almacenamiento de imágenes en la nube** vía Supabase Storage, con URL pública generada automáticamente para cada producto.
- **Importación masiva desde Excel y CSV**: carga cientos de productos de una sola vez con un archivo `.xlsx` o `.csv` — ideal para migraciones desde otros sistemas.
- **Product Studio (Estudio Fotográfico)**: un editor visual integrado con recorte interactivo y zoom para que cada imagen de tu catálogo luzca profesional antes de subirla.
- **Categorías personalizables**: organiza tu inventario con categorías que tú defines (Bebidas, Snacks, Lácteos, Panadería, Limpieza, etc.) y filtra al instante.
- **Selección múltiple y acciones en lote**: selecciona varios productos a la vez para eliminar, reclasificar o exportar.
- **Alertas de stock bajo**: visualiza de un vistazo qué productos están por agotarse.
- **Sincronización dual (local + nube)**: los productos se guardan localmente con Dexie/IndexedDB para funcionalidad offline Y se sincronizan a Supabase para acceso multi-dispositivo.

<br>

---

### 📊 Dashboard Inteligente — Métricas que Impulsan Decisiones

Un panel de control con gráficos interactivos que te muestra la salud financiera de tu negocio de un vistazo.

- **Ingresos totales, número de ventas, ticket promedio y total de productos** — todo resumido en tarjetas visuales con íconos.
- **Gráfico de barras de ventas diarias** (Recharts): observa la tendencia de ingresos por día en los últimos 7, 15 o 30 días.
- **Gráfico de pastel por categoría**: descubre qué tipo de productos generan más ingresos para tomar decisiones de compra inteligentes.
- **Top 5 productos más vendidos**: identifica tus estrella de ventas y asegúrate de que nunca falten en tu inventario.
- **Filtro por período configurable**: cambia entre 7, 15 o 30 días para analizar diferentes ventanas de tiempo.
- **Tarjetas interactivas**: haz clic en "Ingresos" para ir al historial de caja o en "Ventas" para ver el detalle de cada transacción.

<br>

---

### 💰 Caja Registradora — Apertura, Cierre y Cuadre Profesional

El sistema de caja más completo para que cada turno quede cuadrado al centavo.

- **Apertura de caja** con monto base configurable (en formato colombiano con separador de miles).
- **Monitoreo en tiempo real** de ventas, gastos y saldo esperado durante el turno activo.
- **Registro de gastos**: anota retiros o gastos operativos durante el turno con nota descriptiva.
- **Cierre de caja con cuadre por método de pago**: al cerrar, reporta lo que contaste en Efectivo, Nequi, Daviplata, Tarjeta y Otros. Bolsiyo calcula automáticamente la diferencia entre lo esperado y lo reportado.
- **Indicadores dinámicos**: solo muestra campos de cuadre para los métodos de pago que realmente se usaron durante el turno — sin distracciones.
- **Historial de turnos anteriores**: revisa los últimos 10 cierres de caja con total de ventas, gastos y diferencias, para auditar el desempeño de cada cajero.

<br>

---

### 🍽️ Modo Restaurante — Gestión de Mesas y Órdenes

Diseñado para restaurantes, cafeterías y establecimientos con servicio a la mesa.

- **Creación y gestión de mesas** con estados visuales: Disponible, Ocupada.
- **Agregar productos a la orden de cada mesa** desde el catálogo, con control de cantidad.
- **Cálculo automático de propina** configurable (% sobre el subtotal).
- **División de cuenta**: separa la cuenta de una mesa en partes iguales para grupos que desean pagar por separado.
- **Cierre de mesa con facturación automática**: al cerrar, se genera la venta, se descuenta del inventario y la mesa queda lista para el siguiente cliente.
- **Eliminación de mesas**: reorganiza tu espacio cuando lo necesites.

<br>

---

### 📋 Historial de Ventas — Trazabilidad Total

Cada venta queda registrada con nivel de detalle de auditoría.

- **Historial completo en la nube**: consulta todas tus ventas ordenadas por fecha, con número de factura, total, método de pago, cliente y estado.
- **Filtros avanzados**: busca por número de factura, nombre de cliente, método de pago (Efectivo, Nequi, Daviplata, Tarjeta) y estado (Completada, Pendiente, Anulada).
- **Vista de detalle por venta**: abre cualquier venta para ver los ítems vendidos, cantidades, precios unitarios, subtotales, propina, efectivo recibido y cambio devuelto.
- **Anulación de ventas**: revierte una transacción con un solo clic, actualizando el estado en la nube.
- **Fallback local**: si no hay conexión, el historial se carga desde la base de datos local (Dexie) con mapeo automático de formatos.

<br>

---

### 💳 Fiados / Deudas — Nunca Pierdas de Vista Quién te Debe

Un módulo dedicado al control de ventas a crédito.

- **Panel de resumen**: total adeudado, número de clientes con deuda activa y cantidad de fiados pendientes.
- **Filtro por estado**: visualiza todos, solo pendientes o solo pagados.
- **Registro de abonos**: cada vez que un cliente paga una parte, registra el abono y Bolsiyo recalcula automáticamente el saldo restante.
- **Cierre automático de deuda**: cuando el saldo restante llega a $0, la deuda se marca como pagada.
- **Datos de contacto del cliente**: almacena el teléfono para facilitar el cobro.

<br>

---

### 🎛️ Variaciones y Paquetes — Ideal para Recargas y Servicios

Un sistema de variaciones de producto diseñado para negocios que venden paquetes de datos, recargas, planes de telefonía o cualquier servicio con múltiples opciones.

- **Atributos (operadores)**: crea categorías como Claro, Movistar, Tigo, Wom, Virgin con colores y emojis personalizados.
- **Opciones (planes/paquetes)**: dentro de cada operador, agrega los planes disponibles con nombre, descripción, precio de venta, precio de costo y stock.
- **Sincronización directa con la nube**: los atributos y opciones se guardan en Supabase con operaciones CRUD completas.
- **Panel dividido intuitivo**: selecciona un operador a la izquierda y administra sus paquetes a la derecha.

<br>

---

### 🤖 Scanner Inteligente con IA — Digitaliza Catálogos al Instante

Tecnología de visión artificial que transforma folletos físicos en datos digitales.

- **Escaneo con IA de visión**: toma una foto del folleto de paquetes de un operador de telefonía y la IA extrae automáticamente los nombres, precios y detalles de cada plan.
- **Detección de operador por color dominante**: la IA identifica si el folleto es de Claro (rojo), Movistar (verde), Tigo (azul) o Wom (morado) analizando los colores de la imagen.
- **Tabla de resultados editable**: revisa y ajusta los datos extraídos antes de importarlos a tu inventario.
- **Importación masiva en un clic**: una vez verificado, importa todos los paquetes detectados directamente a tu catálogo de variaciones.

<br>

---

### 🧾 Impresión de Tickets Térmicos — Facturación Física Profesional

Compatible con impresoras térmicas POS de 58mm, el estándar de la industria.

- **Ticket térmico formateado** con nombre del negocio, NIT, dirección, sucursal, número de factura, fecha, detalle de ítems, subtotal, IVA, propina, total, método de pago, efectivo recibido y cambio.
- **Generación de PDF profesional** para compartir digitalmente por WhatsApp o correo.
- **Impresión directa** desde la aplicación con el comando nativo de impresión del sistema operativo.
- **Compatible con formato monoespacio** optimizado para la resolución de impresoras térmicas.

<br>

---

### 📑 Facturación DIAN — Cumple con la Normativa Colombiana

Configuración completa para la facturación electrónica conforme a la DIAN.

- **Número de resolución, fecha de resolución y prefijo** de facturación.
- **Rango de numeración autorizada** (desde / hasta) con contador de número actual.
- **NIT y dirección del negocio** para encabezado de facturas.
- **Formato de factura con numeración DIAN** integrado en los tickets y PDFs.

<br>

---

### ⚙️ Configuración y Personalización — Tu App, a tu Medida

- **Gestión de categorías**: crea, edita y elimina categorías de productos con actualización en cascada automática.
- **Nombre del negocio personalizable**: cambia el nombre que aparece en tus tickets y facturas.
- **Multiusuario con roles**: crea usuarios adicionales con PIN de acceso y rol (cajero, admin), cada uno con permisos diferenciados.
- **Tema visual**: alterna entre modo claro ☀️ y modo oscuro 🌙 con un solo toque.
- **Estilo Liquid Glass**: activa el efecto visual premium de cristal traslúcido para una estética futurista.
- **Enlace directo a soporte vía WhatsApp**: contacta al equipo de Bolsiyo sin salir de la aplicación.

<br>

---

### 👑 Suscripción y Licenciamiento — Planes que Crecen Contigo

| Característica | Gratis | Bolsiyo Ultra | Bolsiyo Enterprise |
|---|:---:|:---:|:---:|
| Facturación | 50/mes | ♾️ Ilimitada | ♾️ Ilimitada |
| Inventario | Básico | Ilimitado | Ilimitado |
| Variaciones / Paquetes | — | ✅ | ✅ |
| Reportes y métricas | — | ✅ Mensuales | ✅ Con IA |
| Multi-dispositivo | — | ✅ | ✅ |
| Multi-sucursales | — | — | ✅ |
| API personalizada | — | — | ✅ |
| Usuarios ilimitados | — | — | ✅ |
| Auditoría de logs | — | — | ✅ |
| Soporte | Comunidad | Prioritario (24h) | 24/7 + SLA |

- **Prueba gratuita** disponible para explorar todas las funciones premium.
- **Activación por clave de licencia** directa — sin tiendas de aplicaciones intermediarias.
- **Reloj de expiración premium** en tiempo real que muestra cuánto tiempo queda de tu suscripción.
- **Múltiples métodos de pago**: Nequi, Daviplata, PayPal y Tarjeta de Crédito/Débito vía pasarela segura Wompi.

<br>

---

### 📱 Diseño Adaptativo Móvil — Experiencia Nativa en tu Celular

- Interfaz completamente optimizada que respeta el **Safe Area** (área segura) en dispositivos con notch, barra de navegación por gestos y pantallas curvas.
- **Navegación inferior tipo app nativa** en pantallas pequeñas, con acceso rápido a POS, Inventario, Caja, Dashboard y Configuración.
- Los elementos interactivos nunca se cortan ni se superponen con la interfaz del sistema operativo.

<br>

---

### ☁️ Sincronización en Tiempo Real — Vende Desde Cualquier Lugar

- Base de datos en la nube con **Supabase** que permite la actualización instantánea de inventario, cajas y reportes de ventas.
- **Suscripción a Postgres Realtime**: cualquier cambio en productos (INSERT, UPDATE, DELETE) se refleja automáticamente en todos los dispositivos conectados sin recargar.
- **Fallback local automático**: si pierdes conexión, Bolsiyo sigue funcionando con la base de datos local (Dexie/IndexedDB) y resincroniza cuando la conexión regresa.

<br>

---

### 🔒 Seguridad Empresarial — Tus Datos, Solo Tuyos

- **Row Level Security (RLS)** en Supabase: cada negocio opera en un entorno de datos completamente aislado. Las políticas de seguridad garantizan que cada usuario solo puede visualizar y modificar su propia información.
- **Autenticación segura con Supabase Auth**: registro e inicio de sesión con email y contraseña, con manejo de sesiones persistentes.
- **Verificación de licencia con doble capa**: sincronización local desde perfil en la nube + llamada RPC como backup para garantizar integridad.
- **Panel de administración protegido** accesible solo para usuarios con rol `admin`.

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
| **Sistemas compatibles** | Android 7.0 (Nougat / API 24) en adelante |
| **Arquitectura de procesador** | Optimizado para ARM de 64 bits (`aarch64-linux-android`) |
| **Formato de entrega** | Paquete de aplicación directa (`.apk`) |

<br>

---

## 🚀 Stack Tecnológico

| Capa | Tecnología |
|---|---|
| **Motor de rendimiento** | Rust + Tauri v2 |
| **Interfaz de usuario** | React 18 + Vite |
| **Diseño** | Tailwind CSS + Glassmorphism + Modo Oscuro |
| **Base de datos local** | Dexie.js (IndexedDB) |
| **Base de datos en la nube** | Supabase (PostgreSQL + Realtime + Storage + Auth) |
| **Gráficos** | Recharts |
| **Importación de datos** | SheetJS (XLSX) + PapaParse (CSV) |
| **Edición de imágenes** | React Easy Crop |
| **Visión Artificial** | IA de visión para escaneo de folletos |
| **Impresión** | HTML5 a PDF + Impresión térmica nativa (58mm) |
| **CI/CD** | GitHub Actions (compilación cruzada Windows + Android) |
| **Pasarela de pagos** | Wompi |

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

### 🚀 Empieza Ahora — Es Gratis

Descarga Bolsiyo POS, crea tu cuenta y comienza a vender en menos de 2 minutos.
Sin tarjeta de crédito. Sin compromisos. Sin letras pequeñas.

<br>

**Bolsiyo POS** — Control inteligente para tu negocio.

*¿Preguntas? Contáctanos por WhatsApp: +57 311 539 7930*

</div>
