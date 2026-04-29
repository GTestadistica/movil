# 📱 Proyecto Movil - VisorPro Stats Dashboard

Bienvenido al **Proyecto Movil**, la extensión móvil oficial del ecosistema **VisorPro**. Esta aplicación es una PWA (Progressive Web App) diseñada para transformar la información capturada en los distintos módulos administrativos en **estadísticas, métricas y gráficas accionables** para la toma de decisiones en tiempo real.

---

## 🏗️ El Ecosistema VisorPro
Esta aplicación centraliza y visualiza los datos provenientes de los siguientes sistemas de gestión:

### 1. Módulos de Visor Pro (Gestión Operativa)
El **Proyecto Movil** extrae y grafica métricas de los siguientes módulos:
*   **Visor Principal**: Estadísticas de venta promedio, días de inventario y estatus operativo por supervisor.
*   **Caja Chica**: Análisis de tendencias de gasto, comparativa de presupuesto vs. real y conceptos de consumo.
*   **Gestión RH / Horarios**: Métricas de cobertura de plantilla, cumplimiento de horarios y autorizaciones pendientes.
*   **Negocios y Pedidos**: Histórico semanal de pedidos, seguimiento de consumo de agua y efectividad de degustaciones.
*   **Auditorías**: Calendario de supervisiones y resultados técnicos detallados para evaluar el cumplimiento de estándares.

### 2. Módulo de Caducidades (Auxiliar Sucursales GTR 3)
Visualización de métricas críticas capturadas en el sistema de control de inventarios:
*   **Control de Lotes**: Monitoreo de productos próximos a vencer detectados en sucursal.
*   **Impacto Financiero**: Gráficas sobre el costo de existencias vs. costo de salida y valor total de merma proyectada.
*   **Estatus de Revisión**: Seguimiento del flujo de validación (Capturado, En Revisión, Observado, Aprobado).
*   **Cumplimiento Documental**: Verificación de carga de evidencias y PDFs firmados de cada folio.

---

## 🚀 Funcionalidades Clave del Dashboard Móvil

### 📊 Análisis Visual y Métricas
*   **Insights Globales**: Resumen ejecutivo de los indicadores más críticos de todas las sucursales.
*   **Gráficos Dinámicos**: Tendencias temporales y comparativas por unidad mediante **Recharts**.
*   **Alertas Críticas**: Notificaciones visuales inmediatas sobre caducidades urgentes o falta de cobertura de personal.

### 🔐 Seguridad y Acceso
*   **Acceso por Sucursal**: Login individual sincronizado con la base de datos de VisorPro.
*   **Autenticación Biométrica**: Acceso ultra-rápido y seguro mediante **Huella Digital o FaceID** (WebAuthn).
*   **Cifrado HTTPS**: Conexión protegida con Google Apps Script para el intercambio de datos.

### 📱 Experiencia Mobile-First
*   **PWA**: Instalación directa en la pantalla de inicio sin pasar por tiendas de aplicaciones.
*   **Soporte Offline**: Consulta de las últimas métricas descargadas incluso sin conexión a internet.
*   **Interfaz Premium**: Diseño moderno con Dark Mode y efectos de transparencia (Glassmorphism).

---

## 🛠️ Stack Tecnológico
*   **Frontend**: React 19 + Vite.
*   **Iconografía**: Lucide React.
*   **Visualización**: Recharts.
*   **Base de Datos Local**: IndexedDB (Caché de alto rendimiento).
*   **Backend**: Google Apps Script (GAS) / VisorPro Core Engine.

---

## 🔧 Configuración y Despliegue

### Compilación
```bash
npm run build
```

### Despliegue
Para actualizar la aplicación, ejecute el comando de despliegue o suba manualmente la carpeta `dist` a GitHub Pages. Consulte la [Guía de Despliegue Manual](./GUIA_DESPLIEGUE_MANUAL.md) para más detalles.

---
*VisorPro Ecosystem — Transformando Datos en Decisiones — 2026*
