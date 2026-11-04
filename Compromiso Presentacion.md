**Rol y Objetivo:**
Actúa como Desarrollador Frontend Principal y Diseñador UX/UI Senior. Tu objetivo es crear el código completo de una Aplicación Web Interactiva de página única (Single Page Application - SPA) de alto impacto visual, moderna, elegante e intuitiva. Esta aplicación servirá como un Dashboard / Pitch Deck interactivo para presentar 4 soluciones clave de Fortinet en una exposición ejecutiva de 5 minutos (1 minuto aproximado por solución).

**Requisitos Técnicos y de Despliegue:**
1. **Autocontenido y Single-File:** Genera TODO el código en un único archivo `index.html` autoejecutable que incluya estructura (HTML5), estilos (CSS3 inline o mediante CDN como Tailwind CSS) y lógica (JavaScript ES6 limpio sin dependencias complejas).
2. **Listo para GitHub Pages:** El archivo debe estar optimizado para desplegarse de manera pública e inmediata en el repositorio: `https://github.com/MrCastilloF/`.
3. **Sin Build Tools:** No uses Node.js, Webpack ni procesos de compilación. Debe abrirse directamente al hacer doble clic o al alojarse en GitHub Pages.

**Regla Estricta de Información (Cero Alucinaciones):**
NO inventes ni agregues especificaciones fuera de la información oficial de la arquitectura Fortinet Security Fabric y el documento de referencia.
- **Alcance del ecosistema Fortinet:** 
  • Seguridad Perimetral y Conectividad: FortiGate (NGFW), Secure SD-WAN (inspección de tráfico, conectividad integrada).
  • LAN y Wi-Fi: FortiSwitch y FortiAP (conectividad cableada e inalámbrica integrada).
  • Acceso Seguro y Trabajo Híbrido: FortiSASE y ZTNA (protección de usuarios remotos y acceso a aplicaciones según verificación).
  • Protección de Endpoints y Aplicaciones: FortiEDR, FortiWeb, FortiAppSec Cloud y FortiMail (prevención, detección/respuesta y protección de apps/correo).
  • Gestión y Operaciones (SOC): FortiManager, FortiAnalyzer, FortiSIEM y FortiSOAR (administración centralizada, visibilidad y automatización).
- **Enfoque conceptual:** Enfatizar la transición de productos aislados a una arquitectura plataforma integrada (Fortinet Security Fabric) que combina infraestructura, usuarios/aplicaciones y operación.

**Selección de Soluciones para la SPA:**
Selecciona e integra exactamente 4 fichas estratégicas bien estructuradas:
1. FortiGate (NGFW) & Secure SD-WAN
2. FortiSASE & ZTNA
3. FortiEDR
4. FortiManager & FortiAnalyzer (Operaciones / SOC)

**Estructura de Contenido por cada Ficha:**
Cada una de las 4 fichas debe presentar de forma visualmente clara y dividida las siguientes 4 respuestas:
1. ¿Qué hace?: Definición funcional precisa basada estrictamente en la fuente.
2. ¿A quién se puede vender?: Perfil objetivo (sucursales distribuidas, trabajo remoto, multicloud, centros de datos o requerimientos de operaciones SOC).
3. ¿Cuál es su diferenciador?: Integración nativa bajo Fortinet Security Fabric, respuesta automatizada y reducción de la complejidad operativa frente a silos aislados.
4. ¿En qué región/regiones de COEM (Controles Empresariales) posicionar?: Selector o indicador directo de la cobertura regional asignada dentro de COEM (ej. Región Central, Andina, Norte, Sur, etc.).

**Funcionalidades de Alto Impacto:**
- **Visualizador de Fichas Interactivas:** Tarjetas con arquitectura Grid, efectos hover, transiciones fluidas, iconografía técnica SVG y microinteracciones visuales.
- **Modo Temporizador de Exposición (Pitch Mode 5 min):** 
  • Reloj regresivo visible de 5 minutos.
  • Indicador dinámico que resalta automáticamente la ficha correspondiente a cada minuto (Minuto 1 -> Solución 1, Minuto 2 -> Solución 2, etc.).
  • Botones de control (Iniciar, Pausar, Reiniciar).
- **Exportador de Contenido (Pre-Socialización):**
  • Botón "Copiar Resumen Ejecutivo" para enviar el texto plano sin formato al portapapeles.
  • Botón "Descargar (.md)" para exportar un archivo Markdown autogenerado con el contenido completo listo para entregar antes de la presentación.

**Diseño Visual (UX/UI):**
- **Estética:** Dark Mode premium con acentos corporativos de alto contraste (Rojo Fortinet `#EE2737`, Azul Cian neón y Verde Esmeralda para indicadores de estado).
- **Tipografía:** Limpia, legible y moderna (San Francisco, Inter o Roboto).
- **Responsive Design:** 100% adaptable a pantallas desktop, laptops y tablets.