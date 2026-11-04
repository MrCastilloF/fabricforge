# 🛡️ Fortinet Security Fabric — Dashboard Pitch Deck Ejecutivo

> Aplicación web interactiva de página única (SPA) para presentar **6 soluciones clave de Fortinet** en una exposición ejecutiva de **5 minutos** (~50 s por solución), con temporizador de pitch, fichas interactivas y exportación de contenido para pre-socialización.

**🌐 Demo en vivo:** https://mrcastillof.github.io/Soluciones_Fortinet_Presentacion/

---

## 📋 Índice

- [Descripción](#-descripción)
- [Soluciones incluidas](#-soluciones-incluidas)
- [Funcionalidades](#-funcionalidades)
- [Estructura de cada ficha](#-estructura-de-cada-ficha)
- [Modo de uso — Pitch de 5 minutos](#-modo-de-uso--pitch-de-5-minutos)
- [Exportación y pre-socialización](#-exportación-y-pre-socialización)
- [Diseño visual (UX/UI)](#-diseño-visual-uxui)
- [Tecnología y arquitectura](#-tecnología-y-arquitectura)
- [Despliegue](#-despliegue)
- [Uso local](#-uso-local)
- [Actualizar y republicar](#-actualizar-y-republicar)
- [Regla de información — cero alucinaciones](#-regla-de-información--cero-alucinaciones)
- [Estructura del repositorio](#-estructura-del-repositorio)
- [Licencia y fuentes](#-licencia-y-fuentes)

---

## 📖 Descripción

Este proyecto nace del compromiso **"Compromiso Presentacion.md"**: crear una SPA de alto impacto visual, moderna, elegante e intuitiva que sirva como **Dashboard / Pitch Deck interactivo** para una exposición ejecutiva de 5 minutos frente a clientes.

La propuesta se articula alrededor del **Fortinet Security Fabric** — la arquitectura que conecta los componentes de seguridad para **compartir visibilidad y coordinar la protección** — enfatizando la transición de **productos aislados** a una **plataforma integrada** que combina:

| Pilar | Soluciones |
|---|---|
| **Infraestructura** | FortiGate (NGFW), Secure SD-WAN, FortiSwitch, FortiAP |
| **Usuarios y aplicaciones** | FortiSASE, ZTNA, FortiEDR, FortiWeb, FortiAppSec Cloud, FortiMail |
| **Operación (SOC)** | FortiManager, FortiAnalyzer, FortiSIEM, FortiSOAR |

---

## 🧩 Soluciones incluidas

Se incluyen **6 fichas estratégicas** (las 4 definidas en el compromiso + 2 de alto valor y alta demanda comercial entre los clientes):

| # | Solución | Área | Ficha estrella |
|---|---|---|---|
| 1 | **FortiGate (NGFW) & Secure SD-WAN** | Seguridad perimetral y conectividad | ⭐ |
| 2 | **FortiSASE & ZTNA** | Acceso seguro y trabajo híbrido | |
| 3 | **FortiEDR** | Protección de endpoints | |
| 4 | **FortiManager & FortiAnalyzer** | Gestión y operaciones de seguridad (SOC) | |
| 5 | **FortiSwitch & FortiAP** | LAN y Wi-Fi | |
| 6 | **FortiWeb, FortiAppSec Cloud & FortiMail** | Aplicaciones y correo | |

> **⭐ Ficha estrella:** la solución de **Seguridad perimetral** (la más atractiva para clientes) se distingue con badge, borde y degradado rojo propio, y encabeza tanto el Pitch Mode (Minuto 1) como los documentos exportados.

---

## ⚡ Funcionalidades

### 🎴 Visualizador de fichas interactivas
- Tarjetas con **arquitectura Grid** responsive (`auto-fit / minmax`)
- Efectos **hover** con elevación y transiciones fluidas (`cubic-bezier`)
- **Iconografía técnica SVG** propia por solución (firewall, nube, escudo, consola, red, correo)
- **Microinteracciones**: chips de región con estado activo, pulsos y feedback visual

### ⏱️ Modo Temporizador de Exposición (Pitch Mode · 5 min)
- **Reloj regresivo** visible de 05:00 con alerta visual en el último minuto
- **Indicador dinámico** que resalta automáticamente la ficha correspondiente (~50 s por ficha con 6 soluciones):
  `Minuto 1 → Solución 1 · Minuto 2 → Solución 2 · …`
- **Controles**: ▶ Iniciar · ⏸ Pausar · ↺ Reiniciar
- **Barra de progreso** de la exposición completa

### 📤 Exportador de contenido (Pre-socialización)
- **"Copiar Resumen Ejecutivo"**: copia al portapapeles el texto plano formateado, listo para pegar en correo, Slack o WhatsApp (con fallback si el portapapeles del navegador está restringido)
- **"Descargar (.md)"**: genera y descarga `Soluciones_Fortinet_Resumen.md` con el contenido completo, tabla de ecosistema y cobertura COEM asignada

---

## 🗂 Estructura de cada ficha

Cada una de las 6 fichas presenta 4 respuestas visualmente divididas:

1. **¿Qué hace?** — Definición funcional precisa basada estrictamente en la fuente oficial.
2. **¿A quién se puede vender?** — Perfil objetivo: sucursales distribuidas, trabajo remoto, multicloud, centros de datos u operaciones SOC.
3. **¿Cuál es su diferenciador?** — Integración nativa bajo Fortinet Security Fabric, respuesta automatizada y reducción de la complejidad frente a silos aislados.
4. **¿En qué región/regiones de COEM posicionar?** — Selector interactivo de cobertura regional (Región Central · Andina · Norte · Sur) que el presentador asigna con un clic; las selecciones se incluyen en ambas exportaciones.

> **Nota de rigor:** el documento fuente no define cobertura oficial de COEM por región, por lo que las regiones **no se inventan**: se asignan manualmente y quedan reflejadas en el resumen copiado y en el Markdown descargado.

---

## 🎬 Modo de uso — Pitch de 5 minutos

1. Abre la presentación (enlace demo o `index.html` local).
2. Asigna las regiones COEM de cada ficha (chips verdes ✓).
3. Pulsa **▶ Iniciar** justo antes de hablar.
4. El reloj regresa de 05:00 y **resalta automáticamente** la ficha que toca en cada tramo de ~50 s.
5. Usa **⏸ Pausar** para pausas o preguntas y **↺ Reiniciar** para repetir la exposición.

---

## 📤 Exportación y pre-socialización

| Botón | Resultado |
|---|---|
| **Copiar Resumen Ejecutivo** | Texto plano en el portapapeles: idea central + las 6 fichas con sus 4 respuestas y cobertura COEM. Ideal para enviar **antes** de la presentación. |
| **Descargar (.md)** | Archivo `Soluciones_Fortinet_Resumen.md` con encabezados, tabla del ecosistema Fortinet, fichas completas y ⭐ marcado en la solución estrella. |

---

## 🎨 Diseño visual (UX/UI)

- **Estética:** Dark Mode premium
- **Acentos corporativos de alto contraste:**
  - 🔴 Rojo Fortinet `#EE2737` — identidad, ficha estrella y estado activo
  - 🔵 Cian neón `#00E5FF` — preguntas y acentos de interfaz
  - 🟢 Verde Esmeralda `#2CE5A5` — diferenciadores e indicadores de estado
- **Tipografía:** sistema San Francisco / Inter / Roboto (font-stack nativo, sin descargas)
- **Responsive:** 100% adaptable a desktop, laptops y tablets (grilla autoajustable y media queries)

---

## 🛠 Tecnología y arquitectura

| Aspecto | Decisión |
|---|---|
| Formato | **Single-file** — todo en un único `index.html` |
| Frontend | HTML5 + CSS3 (vanilla, sin framework) + JavaScript ES6 (sin dependencias) |
| Build tools | **Ninguno** — sin Node.js, Webpack ni compilación |
| Dependencias externas | Cero (funciona sin conexión tras cargarlo) |
| Apertura | Doble clic o cualquier servidor estático |
| Scripting de publicación | `publish.ps1` (local, **excluido del repo** vía `.gitignore`) |

---

## 🚀 Despliegue

### GitHub Pages (ya activo)
El repo está configurado con **GitHub Pages** servido desde la rama `master`:

```
https://mrcastillof.github.io/Soluciones_Fortinet_Presentacion/
```

Cualquier `git push` a `master` **reconstruye y republica** la web automáticamente (build típico: < 1 min).

### Otros hosting
Como es un archivo estático autocontenido, funciona igual en Netlify, Vercel, Cloudflare Pages o cualquier servidor web copiando `index.html`.

---

## 💻 Uso local

```bash
git clone https://github.com/MrCastilloF/Soluciones_Fortinet_Presentacion.git
cd Soluciones_Fortinet_Presentacion
# Doble clic en index.html, o:
start index.html
```

---

## 🔄 Actualizar y republicar

```bash
git add index.html
git commit -m "feat: descripción del cambio"
git push origin master
```

GitHub Pages republica solo; no hay pasos adicionales.

---

## 🚫 Regla de información — cero alucinaciones

> **NO se inventan ni agregan especificaciones fuera de la información oficial** de la arquitectura Fortinet Security Fabric y el documento de referencia `Soluciones Fortinet.docx`.

Todo el contenido de las fichas (definiciones, perfiles objetivo, diferenciadores) proviene textualmente de esa fuente. Los perfiles "¿A quién se puede vender?" se derivan de los escenarios mencionados en el propio documento (sucursales, trabajo remoto, multicloud, centros de datos, SOC), sin cifras ni características técnicas inventadas.

---

## 📁 Estructura del repositorio

```
Soluciones_Fortinet_Presentacion/
├── index.html                    # 🎯 SPA completa (single-file, autocontenido)
├── README.md                     # 📖 Este archivo
├── .gitignore                    # Excluye publish.ps1 y artefactos del sistema
├── Compromiso Presentacion.md    # 📋 Especificación del compromiso
└── Soluciones Fortinet.docx      # 📄 Documento fuente de referencia
```

---

## 📜 Licencia y fuentes

- **Fuente de contenido:** documento interno *“Soluciones Fortinet”* y arquitectura [Fortinet Security Fabric](https://www.fortinet.com/lat).
- **Marcas:** Fortinet, FortiGate, FortiSASE, ZTNA, FortiEDR, FortiManager, FortiAnalyzer, FortiSwitch, FortiAP, FortiWeb, FortiAppSec Cloud y FortiMail son marcas registradas de Fortinet, Inc. Este proyecto es material de presentación y no está afiliado ni respaldado por Fortinet.
- Los elementos visuales (iconos SVG, gradientes, tipografía) son originales de este proyecto.

---

<p align="center"><b>🛡️ Fortinet Security Fabric — De productos aislados a una arquitectura integrada</b></p>
