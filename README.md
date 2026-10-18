<h1 align="center">⚙️ Simulador de Examen - Ingeniería de Software (ISW)</h1>

<div align="center">
    <a href="https://agussantinelli.github.io/isw-parcial" target="_blank"> 
         <img src="https://img.shields.io/badge/Live-Page-blue?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live Page"/>
    </a>
    <a href="https://github.com/agussantinelli/isw-parcial" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/💻%20Repo%20Principal-isw--parcial-1e3a8a?style=for-the-badge&logo=github&logoColor=white" alt="Repo ISW Parcial"/>
    </a>
</div>

<p align="center">
    <a href="https://github.com/agussantinelli" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/👤%20Agustín%20Santinelli-agussantinelli-000000?style=for-the-badge&logo=github&logoColor=white" alt="Agus"/>
    </a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge"/>
    <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge"/>
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS Badge"/>
    <img src="https://img.shields.io/badge/CSS3-Media_Queries-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge"/>
    <img src="https://img.shields.io/badge/GitHub_Actions-CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions Badge"/>
    <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages Badge"/>
</p>
<hr>

<h2>🎯 Objetivo y Alcance</h2>

<p>
    <strong>Simulador de Examen Parcial ISW</strong> es una aplicación web interactiva de entrenamiento y autoevaluación diagnóstica, diseñada específicamente para preparar a los estudiantes en los conceptos teóricos y prácticos clave de la cátedra de <strong>Ingeniería de Software</strong> de la <strong>Universidad Tecnológica Nacional, Facultad Regional Rosario (UTN FRRO)</strong>.
</p>

<p>
    La plataforma integra un banco curado de <strong>95 preguntas reales</strong> extraídas de parciales y exámenes finales históricos (2012 - 2026), simulando con fidelidad absoluta las condiciones reales de evaluación. Cada enunciado reproduce las afirmaciones múltiples, casos de estudio organizacionales y cálculos de ingeniería sin pistas previas sobre la cantidad de opciones válidas.
</p>

<h3>📚 Ejes Temáticos Cubiertos</h3>

<ul>
    <li><strong>Eje 1: Arquitectura CMMI y Niveles de Madurez:</strong> Componentes requeridos (Metas SG/GG) vs. esperados (Prácticas SP/GP) vs. informativos, institucionalización de procesos, acumulación estricta de niveles por etapas, áreas base de Nivel 2 y 3 (PP, PMC, OPF, OPD, OT) y distinción entre Activos de Proceso y Productos de Trabajo.</li>
    <li><strong>Eje 2: Aseguramiento de la Calidad (PPQA / SQA) y Auditorías:</strong> Cierre de auditorías tras la resolución efectiva de no conformidades, mecanismos y políticas de escalamiento (PPQA SP 2.1), independencia jerárquica de SQA, checklists de auditoría de Casos de Uso y evaluación objetiva de directrices de proceso (PPQA SP 1.2).</li>
    <li><strong>Eje 3: Medición y Análisis (MA) y Método PSM:</strong> Procedimientos de recogida y almacenamiento (MA SP 1.3), métricas tácticas de proyecto vs. métricas estratégicas de proceso, fases del método PSM (Planificar, Ejecutar, Evaluar la medición) y cuantificación de atributos de calidad (Usabilidad, Mantenibilidad).</li>
    <li><strong>Eje 4: Ingeniería y Gestión de Requisitos (RD y REQM):</strong> Diagramas de Venn de necesidades del cliente vs. requerimientos especificados (análisis de sobre-ingeniería/gold-plating y validación de la intersección), involucramiento de usuarios operativos, gestión de requisitos ambiguos (usabilidad, entornos móviles), análisis de impacto ante normativas legales de privacidad y trazabilidad bidireccional (REQM SP 1.4 y 1.5).</li>
    <li><strong>Eje 5: Gestión de la Configuración (CM / SCM) y Versionado:</strong> Políticas de retención en repositorio y líneas base, rollback a releases estables (grafo SUN), nomenclaturas de versión <code>&lt;x&gt;.&lt;y&gt;</code> y cálculo de vida útil en años, releases mínimos según ciclos cascada e incremental, elementos bajo SCM por línea de tiempo histórica y consistencia entre definiciones y casos de prueba.</li>
    <li><strong>Eje 6: Planificación (PP), Estimación, EDT y Control (PMC):</strong> Unidades de medida (Planning Poker en PH, Delphi y PERT en Horas), Ley de Brooks sobre la duplicación de personal, regla clásica 40-20-40, descomposición jerárquica en EDT vs. cronograma Gantt, certeza del costo real al terminar la tarea, parámetros de avance objetivo (Earned Value), cálculos de esfuerzo con trabajo en paralelo y Pair Programming, cálculo de calendario con feriados y acciones correctivas viables en PMC.</li>
    <li><strong>Eje 7: Verificación (VER) vs. Validación (VAL) y Revisiones:</strong> Distinción conceptual de Boehm (¿producto correcto vs. correctamente?), diagramas de conjuntos S/P/Test, revisiones estáticas entre pares (VER SP 2.2), omisión de pruebas funcionales internas, psicología del testing de Myers (confianza de adecuación), entornos de validación operativa y frecuencia de pruebas de regresión.</li>
    <li><strong>Eje 8: Testing de Caja Negra (Particiones, Límites y Tablas de Decisión):</strong> Formulación rigurosa de particiones de equivalencia válidas e inválidas, detección de particiones incorrectas (Archivo Alumnos), análisis de valores límite (fronteras de 2 valores), resolución y consolidación de Tablas de Decisión complejas (La Farmacia X21, Sistema de Préstamos, Sitio de Compras, Turnos Médicos) y emparejamiento con diagramas de transición de estados.</li>
</ul>

<hr>

<h2>⚙️ Stack Tecnológico</h2>

<table>
  <thead>
    <tr>
      <th>Componente</th>
      <th>Tecnología</th>
      <th>Versión / Detalles</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Frontend Web</strong></td>
      <td>HTML5 Semántico + JavaScript Vanilla (ES6+)</td>
      <td>Arquitectura Single Page Application (SPA) 100% estática, ligera, rápida y sin frameworks pesados ni dependencias externas.</td>
    </tr>
    <tr>
      <td><strong>Estilos y Diseño</strong></td>
      <td>Tailwind CSS (CDN) + Vanilla CSS3</td>
      <td>Diseño moderno con microanimaciones, sistema tipográfico Inter y estilos visuales personalizados para examen.</td>
    </tr>
    <tr>
      <td><strong>Adaptabilidad</strong></td>
      <td>CSS Media Queries Avanzadas</td>
      <td>Breakpoints específicos para móviles pequeños, tablets, laptops, monitores anchos y hoja de estilos para impresión.</td>
    </tr>
    <tr>
      <td><strong>Algoritmo de Aleatorización</strong></td>
      <td>Fisher-Yates Shuffle + Web Crypto API</td>
      <td>Mezcla aleatoria criptográficamente segura de las 95 preguntas en cada sesión para evitar la memorización por posición.</td>
    </tr>
    <tr>
      <td><strong>Motor de Evaluación</strong></td>
      <td>Evaluación Estricta Multi-Opción</td>
      <td>Calificación <i>all-or-nothing</i> (+1 pt con 100% de aciertos sin fallos; 0 pts con casilla en amarillo para estudio).</td>
    </tr>
    <tr>
      <td><strong>Despliegue Continuo (CI/CD)</strong></td>
      <td>GitHub Actions + GitHub Pages</td>
      <td>Pipeline de integración continua automatizado que publica los cambios en vivo en cada push a la rama <code>main</code>.</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>🏗️ Arquitectura de la Solución</h2>

<p>La solución está estructurada bajo el patrón de <strong>Single Page Application (SPA) client-side</strong>, garantizando reactividad instantánea sin requerir backend ni conexión a base de datos externa:</p>

<ul>
    <li><strong>Capa de Presentación e Interacción:</strong>
        <ul>
            <li>Carga fluida de las 95 preguntas en simultáneo con scroll suave y vista libre.</li>
            <li>Inclusión de badges de eje temático por pregunta para contextualizar de inmediato el área de conocimiento.</li>
            <li>Filtrado dinámico doble: por estado de resolución (Todas, Pendientes, Correctas, Incorrectas) y por <strong>Eje Temático</strong> (dropdown interactivo).</li>
            <li>Casillas interactivas A, B, C, D, etc., con soporte nativo para selección múltiple o individual y botón explícito <strong>"Enviar respuesta"</strong>.</li>
            <li>Botón flotante (FAB) interactivo en dispositivos móviles para acceder rápidamente al mapa de preguntas.</li>
        </ul>
    </li>
    <li><strong>Capa de Lógica de Evaluación:</strong>
        <ul>
            <li>Validación instantánea al enviar: resalta en verde las opciones correctas marcadas, en amarillo discontinuo las que faltaron marcar y en rojo los errores.</li>
            <li><strong>Regla estricta:</strong> Solo suma 1 punto si se marcan exactamente todas las correctas sin fallos. Si hubo aciertos parciales, suma 0 puntos pero marca la casilla en <strong>amarillo</strong> en el mapa para guiar el estudio.</li>
            <li>Despliegue inmediato de la justificación técnica oficial elaborada para cada pregunta, citando prácticas CMMI y reglas de cálculo.</li>
        </ul>
    </li>
    <li><strong>Capa de Navegación y Mapa Visual (Sidebar):</strong>
        <ul>
            <li>Matriz visual interactiva de 95 casillas con sincronización bidireccional en tiempo real.</li>
            <li>Código de estados por color: <strong>Gris</strong> (Pendiente), <strong>Verde</strong> (Perfecta +1 pt), <strong>Amarillo</strong> (Parcial 0 pts) y <strong>Rojo</strong> (Incorrecta 0 pts).</li>
            <li>Barra de estadísticas en vivo (Respondidas, Perfectas, Parciales, Incorrectas, Progreso global).</li>
            <li>Navegación asistida con botón de salto directo a la <strong>"Siguiente pendiente"</strong>.</li>
            <li>Acción rápida de reordenamiento aleatorio (<strong>"🔀 Mezclar"</strong>), reinicio general y modal final con porcentaje y diagnóstico de aprobación.</li>
        </ul>
    </li>
</ul>

<hr>

<h2>📂 Estructura del Proyecto</h2>

<pre><code>isw-parcial/
├── .github/
│   └── workflows/
│       └── deploy.yml       # Pipeline automatizado de CI/CD para GitHub Pages
├── index.html               # Aplicación principal SPA (Punto de entrada con 95 preguntas)
├── parciales_1              # Banco de preguntas y exámenes recopilados (Parte 1)
├── parciales_2              # Compendio maestro de parciales y finales históricos (Parte 2)
└── README.md                # Documentación técnica y académica del repositorio
</code></pre>

<hr>

<h2>🧩 Funcionalidades Principales</h2>

<ul>
    <li><strong>Resolución Libre y Simultánea</strong>
        <ul>
            <li>Posibilidad de responder cualquier pregunta en el orden deseado sin restricciones secuenciales ni bloqueos.</li>
        </ul>
    </li>
    <li><strong>Selección Multi-Opción Realista</strong>
        <ul>
            <li>Permite marcar una o más opciones en cualquier pregunta, sin pistas artificiales que revelen cuántas son correctas.</li>
        </ul>
    </li>
    <li><strong>Filtro Avanzado por Eje Temático</strong>
        <ul>
            <li>Permite estudiar temas puntuales (ej: concentrarse únicamente en Caja Negra o en Arquitectura CMMI).</li>
        </ul>
    </li>
    <li><strong>Mapa Interactivo de 95 Preguntas</strong>
        <ul>
            <li>Navegación instantánea a cualquier tarjeta mediante scroll suave y resaltado visual con efecto glow.</li>
        </ul>
    </li>
    <li><strong>Puntuación Rigurosa con Casillas de Estudio</strong>
        <ul>
            <li>Visualización clara en el mapa de las preguntas resueltas a la perfección (verde) frente a las incompletas (amarillo).</li>
        </ul>
    </li>
    <li><strong>Orden 100% Aleatorio</strong>
        <ul>
            <li>Mezcla matemática con Fisher-Yates al abrir la app o mediante el botón de reordenamiento rápido.</li>
        </ul>
    </li>
    <li><strong>Totalmente Responsive</strong>
        <ul>
            <li>Adaptado con múltiples media queries para teléfonos móviles, tablets y pantallas de escritorio.</li>
        </ul>
    </li>
</ul>

<hr>

<h2>🚀 Puesta en Marcha (Setup Local)</h2>

<h3>1. Requisitos Previos</h3>
<p>No se requieren compiladores ni gestores de paquetes. Solo necesitás cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).</p>

<h3>2. Ejecución Local</h3>

<ol>
    <li>Clonar el repositorio:
        <pre><code>git clone https://github.com/agussantinelli/isw-parcial.git</code></pre>
    </li>
    <li>Ingresar al directorio del proyecto:
        <pre><code>cd isw-parcial</code></pre>
    </li>
    <li>Abrir el simulador directamente en el navegador:
        <pre><code># En Windows
start index.html

# En macOS
open index.html

# En Linux
xdg-open index.html</code></pre>
    </li>
</ol>

<hr>

<h2>📚 Contexto Académico</h2>

<p>
    Este simulador fue desarrollado como herramienta de estudio intensivo y práctica interactiva para el examen parcial de la materia <strong>Ingeniería de Software</strong> de la carrera <strong>Ingeniería en Sistemas de Información</strong> en la <strong>Universidad Tecnológica Nacional, Facultad Regional Rosario (UTN FRRO)</strong>.
</p>

<hr />

<h2 align="left">⚖️ Licencia</h2>

<p align="left">
  Este proyecto se distribuye bajo los términos de la <b>Licencia MIT</b>. 
  Permite el uso, copia, modificación y distribución de forma libre y gratuita con fines educativos o personales.
</p>

<hr />

<h2 align="left">🤝 Contribución</h2>

<p align="left">
  Si encontrás alguna errata en las preguntas o querés proponer mejoras:
  <ul>
    <li>Hacé un fork del repositorio.</li>
    <li>Creá una nueva rama para tus cambios (<code>git checkout -b feature/nueva-pregunta</code>).</li>
    <li>Realizá tus commits con claridad.</li>
    <li>Enviá un Pull Request para su revisión.</li>
  </ul>
</p>

<p align="left">
  ¡Éxitos en el parcial de Ingeniería de Software! ⚙️💻
</p>

<hr />

<p><em>Simulador de Examen ISW – Consolidando el conocimiento de procesos, calidad y testing a través de la práctica interactiva.</em></p>