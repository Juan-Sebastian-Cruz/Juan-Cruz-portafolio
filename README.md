# Juan-Cruz-portafolio
Portafolio
# 👋 Juan Cruz - Portfolio de Automatización con IA

¡Bienvenido a mi espacio digital! Soy **Juan Cruz**, Ingeniero Civil Industrial y Especialista en Ciencia de Datos, apasionado por transformar procesos complejos en soluciones eficientes y escalables mediante la **Inteligencia Artificial** y la **Automatización**. Mi misión es construir sistemas inteligentes que no solo optimicen operaciones, sino que también enriquezcan la experiencia del usuario.

## 🚀 Sobre Mí

Con una sólida base en ingeniería y una especialización en ciencia de datos, combino el análisis estratégico con la implementación técnica para crear soluciones innovadoras. Mi enfoque se centra en el desarrollo de agentes de IA y flujos de trabajo automatizados que abordan desafíos reales en finanzas personales, productividad y gestión de datos.

*   **Título Profesional:** Ingeniero Civil Industrial / Especialista Ciencia de datos
*   **Contacto:**
    *   📧 Email: js.cruzcorrea@gmail.com
    *   📞 Teléfono: +56942826717
    *   🌐 [LinkedIn](https://www.linkedin.com/in/tu-perfil-linkedin) (¡Asegúrate de actualizar este enlace!)

### 🛠 Habilidades Técnicas

*   **Lenguajes de Programación:** Python, Java, JSON
*   **Plataformas de Automatización:** N8N
*   **Análisis y Visualización de Datos:** Excel, Visual Studio, Power BI
*   **Modelos de IA / NLP:** OpenAI, Claude, Google (Gemini)
*   **Bases de Datos:** PostgreSQL (Experiencia con `adamain_chat_histories` y `cronos_chat_histories`)
*   **Otros:** Google Sheets, Google Calendar, Telegram API

### 💡 Intereses

*   Inteligencia Artificial
*   Ciencia de Datos
*   Proyectos de Innovación
*   Investigación Científica
*   Automatización de Procesos (RPA)

## ✨ Mis Proyectos Destacados de Automatización con IA

He desarrollado dos agentes de IA, **Adamain** y **Cronos**, que ejemplifican mi capacidad para crear soluciones robustas y user-friendly utilizando `n8n` como columna vertebral de la automatización y diversas integraciones de Google y modelos de lenguaje avanzados.

---

# 💰 Adamain: Asistente de Finanzas Personales con IA

## ✨ Por Juan Cruz - Llevando el Control Financiero al Siguiente Nivel

**Adamain** es un asistente de finanzas personales basado en IA que he desarrollado para el usuario, enfocado en la precisión y la automatización inteligente de la gestión de datos financieros. Mi objetivo principal con Adamain es transformar la tarea a menudo tediosa del registro financiero en un proceso intuitivo y sin errores.

## 🎯 Propósito y Funcionalidad

Este agente de IA interactúa con un conjunto de herramientas de Google Sheets para gestionar los datos financieros del usuario. Su máxima prioridad es la **precisión de los datos** y el **respeto estricto por los formatos**, garantizando una base de datos impecable para cualquier análisis. Adamain es meticuloso, proactivo y amigable, siempre buscando la optimización financiera del usuario.

### 🌟 Características Principales

*   **Gestión de Ingresos:** Registra automáticamente los ingresos con detalles como fuente, monto, cuenta bancaria y fecha.
*   **Control de Egresos:** Añade gastos con detalle, monto, categoría, fecha y cuenta bancaria.
*   **Registro de Deudas:** Monitorea los pagos de deudas, registrando el monto, la fecha y el tipo de deuda.
*   **Consulta Inteligente:** Accede a un dashboard en Google Sheets para proporcionar resúmenes, análisis y métricas financieras actualizadas (movimientos semanales, ingresos/egresos mensuales, balance, presupuesto abarcado, deudas, gastos por categoría y cuenta).
*   **Normalización de Datos:** Transforma automáticamente entradas de usuario (ej. "10 lucas" a "10000", "gastos domésticos" a "Gastos Domésticos") para mantener la consistencia en el Google Sheets.
*   **Validación Estricta:** Asegura que las categorías, cuentas bancarias y fuentes de ingreso coincidan con listas predefinidas, ofreciendo añadir nuevas opciones si es necesario.

## 🛠 Arquitectura y Tecnologías

Adamain opera dentro de un sistema de automatización `n8n`, utilizando un modelo de lenguaje de IA para interpretar las solicitudes del usuario y orquestar las acciones.

*   **Plataforma de Automatización:** `n8n`
*   **Modelo de Lenguaje (LLM):** Google Gemini Chat Model
*   **Base de Datos Conversacional:** PostgreSQL (`adamain_chat_histories`) para mantener el contexto de la conversación.
*   **Almacenamiento de Datos:** Google Sheets (actuando como el "cerebro financiero" del usuario).
*   **Herramientas de Google Sheets:**
    *   `Consultar Finanzas`: Para leer datos crudos o acceder al dashboard de resumen.
    *   `Registro Ingresos`: Para añadir nuevas entradas en la hoja de Ingresos.
    *   `Registro Egresos`: Para añadir nuevas entradas en la hoja de Egresos.
    *   `Registro de deudas`: Para gestionar los pagos de las deudas.

## 📈 Impacto Profesional

Este proyecto demuestra mi habilidad para:

*   Diseñar y desplegar agentes de IA para tareas específicas.
*   Integrar múltiples servicios (LLMs, bases de datos, APIs de hojas de cálculo) en flujos de trabajo coherentes.
*   Implementar lógicas de normalización y validación de datos para garantizar la integridad.
*   Crear soluciones de automatización que mejoran significativamente la gestión personal o empresarial.

---

# ⏰ Cronos: Asistente de Productividad y Planificación Semanal con IA

## ✨ Por Juan Cruz - Tu Planificador Personal Inteligente

**Cronos** es un asistente de productividad y planificación personal de élite que he creado para ayudar a los usuarios a optimizar su tiempo y equilibrar sus múltiples responsabilidades. Dada mi propia experiencia como profesional multifacético, Cronos aborda la necesidad crítica de una estructura clara y organizada para mantener el foco y maximizar la productividad.

## 🎯 Propósito y Funcionalidad

La especialidad de Cronos es la gestión del tiempo y la optimización de calendarios. Opera dentro de un sistema `n8n` y tiene acceso a herramientas para interactuar con Google Calendar y Telegram. Su tono es proactivo, eficiente y servicial, y su objetivo principal es ayudar al usuario a estructurar su semana y gestionar eventos de manera fluida.

### 🌟 Características Principales

*   **Planificación Semanal Integral:**
    *   Recibe objetivos y restricciones del usuario.
    *   Diseña un calendario optimizado, priorizando tareas y distribuyendo el resto de forma equilibrada.
    *   Presenta una propuesta de calendario en formato de tabla de texto plano.
    *   Itera y modifica la propuesta basada en el feedback del usuario hasta obtener la aprobación explícita.
    *   **Puebla Google Calendar** automáticamente una vez aprobado el plan semanal.
*   **Gestión de Eventos sobre la Marcha:**
    *   Atiende solicitudes conversacionales (agendar, modificar, cancelar eventos individuales).
    *   **Verifica la disponibilidad** en Google Calendar antes de agendar o reprogramar.
    *   Maneja conflictos, informando al usuario y ofreciendo alternativas.
    *   Configura notificaciones predeterminadas (ej. 1 día antes).
*   **Interacción Multimodal:**
    *   Procesa comandos de texto a través de Telegram.
    *   **Transcribe grabaciones de voz** a texto para su procesamiento.
    *   **Analiza imágenes** de notas manuscritas (utilizando OpenAI "Escriba - analizador de imagenes") para extraer y estructurar la información para la planificación.

## 🛠 Arquitectura y Tecnologías

Cronos se beneficia de una robusta arquitectura de automatización que integra modelos de IA avanzados y servicios de Google.

*   **Plataforma de Automatización:** `n8n`
*   **Modelo de Lenguaje (LLM):** OpenAI Chat Model (GPT-4o-mini)
*   **Base de Datos Conversacional:** PostgreSQL (`cronos_chat_histories`) para mantener la memoria del chat.
*   **Integraciones Clave:**
    *   `Google Calendar`: Para todas las operaciones de calendario (Crear, Consultar, Actualizar, Eliminar eventos).
    *   `Telegram`: Como interfaz de usuario principal para la comunicación.
    *   `Google Gemini`: Para la transcripción de audio (Transcribe a recording).
    *   `OpenAI`: Como "Escriba - analizador de imagenes" para el OCR y estructuración de notas manuscritas.

## 📈 Impacto Profesional

Este proyecto subraya mi experiencia en:

*   Desarrollo de asistentes de IA para la productividad personal.
*   Orquestación de flujos de trabajo complejos con herramientas no-code/low-code como `n8n`.
*   Integración de capacidades multimodales (voz, texto, imagen) en soluciones de IA.
*   Diseño de interacciones conversacionales efectivas para la gestión de tareas.
*   Manejo de APIs de servicios externos (Google Calendar, Telegram, OpenAI).

---
---

## 📞 Conecta Conmigo

Estoy siempre abierto a nuevas colaboraciones, proyectos desafiantes y discusiones sobre cómo la IA y la automatización pueden seguir modelando nuestro futuro. ¡No dudes en contactarme!

---
