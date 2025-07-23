# QWEN 3 CODER es liberado... mejor que KIMI K2

Recientemente vi un video y lo encontré bastante informativo. Para entender mejor y compartir el contenido, utilicé **[Viddo](https://viddo.pro/)** para convertir el video en un artículo estructurado, que sirvió como referencia para este análisis.

**Video Original:** [Ver Video](> - Alibaba ha presentado el Quin 3 coder, un poderoso nuevo modelo de codificación de código abierto.
> - Cuenta con un masivo modelo de 480 mil millones de parámetros llamado Powerful1.
> - El Quin 3 coder se destaca en varios benchmarks y supera a sus competidores.
> - Una herramienta de línea de comandos para codificación genética, Quin Code, ya está disponible.
> - Nuevos métodos en aprendizaje por refuerzo mejoran el rendimiento en tareas de codificación del mundo real.

Alibaba acaba de lanzar la próxima gran novedad. **Quin 3 coder**. Justo cuando el mundo se estaba acostumbrando a **Kimi K2**, otro gran modelo de codificación de código abierto, Alibaba lanza el **Quin 3 coder**, que está disponible en múltiples tamaños.

Pero el grande, el **Powerful1**, es Quin 3 Coder 480B A35B instruct, lo que significa que este es un **modelo de 480 mil millones de parámetros**. Está construido con una mezcla de expertos, por lo que solo **35 mil millones de parámetros están activos durante cualquier llamada**. Instruct significa que es nuestro modo de asistente amigable y útil a diferencia del modelo base que se asemeja un poco más a un modelo de finalización de texto.

Nataly admite **256k de contexto** y se puede escalar hasta **1 millón**. Y como pueden ver aquí, los benchmarks ahora se ven excelentes. No siempre se puede confiar solo en los benchmarks, así que denle unos días mientras todos lo prueban y lo testean.

Pero **Kimi K2** fue extremadamente impresionante en todos los aspectos. El **Gwin 3 coder** supera fácilmente a Kimi K2. No solo eso, sino que también es comparable. Es competitivo con **Claud Sounded**. También supera a **OpenAI's GPT 4.1** y obtiene muy buenos resultados en **uso de navegador genético** así como en el uso de herramientas genéticas. Nuevamente, solo Cloud Sounded 4 lo supera en algunos casos.

El **equipo Gwin** promete que funciona sin problemas con las mejores herramientas de desarrollo de la comunidad y se puede utilizar en cualquier lugar del mundo digital. Codificación genética en el mundo y no están bromeando al respecto.

Junto con el modelo, están liberando una herramienta de línea de comandos para codificación genética llamada **Quin Code**. Se bifurca a partir del **código de Gemini de Google**. Como pueden ver aquí, está de código abierto bajo la **licencia Apache 2.0 de GitHub**. Se parece mucho al código claw y ha sido adaptado con prompts personalizados y protocolos de llamada de función para desatar completamente las capacidades del Quin 3 coder en tareas de codificación genética.

Básicamente **Quin code** es solo un **Gemini cli** adaptado. Ha sido modificado para usar los modelos Quwin. También puedes usar los **modelos Quin 3 coder** con **cloud code**. A mucha gente le gusta más el cloud code, así que puedes usar fácilmente los modelos Quin 3 Codder con Cloud code. Puedes usarlo con **K Clin**. Dejaré estos enlaces más abajo.

Uno de los grandes temas de discusión en este momento es el **aprendizaje por refuerzo**. Tomar estos modelos y llevarlos a un gimnasio RL para enseñarles cómo hacer diversas habilidades como codificación, matemáticas, etc. Como digo aquí, escalar el aprendizaje por refuerzo de código es difícil de resolver, fácil de verificar, como puedes ver aquí.

A medida que incrementan los pasos de entrenamiento mientras entrenan este modelo, va subiendo y subiendo en todas las diferentes áreas de rendimiento como generación de código, desarrollo de software, codificación competitiva, **seguimiento de instrucciones SQL**, etc. Toman una pequeña crítica al otro laboratorio frontier diciendo que a diferencia del enfoque prevaleciente en la generación de código a nivel competitivo en la comunidad, creemos que todas las tareas de código están naturalmente bien adaptadas para la ejecución impulsada por el aprendizaje por refuerzo a gran escala.

Esa es la razón por la que escalamos el entrenamiento de código RL en un conjunto más amplio de tareas de codificación del mundo real. Básicamente están diciendo que en lugar de intentar maximizar estos cuestionarios y pruebas, estas preguntas de estilo competitivo, en realidad están entrenando este modelo para hacer **trabajo real en el mundo real**.

Al escalar automáticamente y probar casos de diversas tareas de codificación, hemos creado instancias de entrenamiento de alta calidad y desbloqueado con éxito todo el potencial del aprendizaje por refuerzo. Esto no solo aumentó significativamente las tasas de éxito de ejecución de código, sino que también trajo mejoras en otras tareas.

Esto significa que este enfoque se generaliza. Hemos visto en otros artículos publicados que, por ejemplo, entrenarlo para que haga código mejora su capacidad para resolver problemas matemáticos, incluso si no se entrenó explícitamente para eso. Seguramente, parece que su enfoque se generaliza en muchas tareas diferentes. Esperemos que publiquen un artículo más adelante que detalle cómo abordan esto.

Pero aquí mencionan que su enfoque utiliza tareas difíciles de resolver y fáciles de verificar como un terreno fértil para el aprendizaje por refuerzo a gran escala.

Así que aquí hay un gráfico de su rendimiento en el **SUI bench Verified**; así que este es el tamaño del modelo. Los modelos a la derecha son más grandes, los modelos a la izquierda son más pequeños y cuanto más alto se va, mejor es la puntuación en el subench verified. SWbench son **500 problemas de GitHub de Python verificados por humanos en el mundo real** revisados por humanos y confirmados como solucionables.

Como pueden ver aquí, **Quin 3 coder** está por encima de la mayoría de los otros modelos que hemos visto, incluido **Kimmy K2**, **GPT 4.1**, incluso el **Gemini 2.5 Pro Preview**. Solo **Cloud Sont 4** lo supera ligeramente mientras es un modelo mucho más grande. Por ser un modelo de tamaño moderado, nada se le acerca en términos de rendimiento. **Kimmik K2** es mucho más grande pero no tan bueno.

Es importante destacar que, con **tareas de ingeniería de software del mundo real** como las de **SUI bench verified**, el Quin 3 coder debe participar en interacciones de múltiples turnos con el entorno que implican planificación, uso de herramientas, recibir retroalimentación y tomar decisiones. Así que esta no es una simple pregunta-respuesta. Esta es una tarea de largo horizonte que incluye planificación y retroalimentación.

¿Cuál fue su truco para que este modelo fuera tan bueno en esas tareas de largo horizonte? Aquí indican que en la fase posterior de entrenamiento del **Quint threeoder** introdujeron **Long Horizon rl**. Se refieren a ello como **Agent rl**. Esto fue para alentar al modelo a resolver esas tareas del mundo real a través de interacciones de múltiples turnos utilizando herramientas.

Esto es interesante. El principal desafío al hacer algo como este **Agent rl** radica en la escalabilidad del entorno. Para abordar esto, construyeron un **sistema escalable** capaz de ejecutar **20,000 entornos independientes en paralelo**. Hicieron esto utilizando **la infraestructura en la nube de Alibaba**.

Esto les permitió la escala necesaria para ejecutar esta masiva tubería de aprendizaje por refuerzo. Y esto es lo que permitió al **Coin 3 Coder** lograr el **estado del arte** entre los modelos de código abierto sin—y esto es importante señalar—sin escalamiento en tiempo de prueba. Este no es un modelo de razonamiento. A diferencia del **DeepSeq R1** o el **Gemini 2.5 Pro Preview**, este no es de razonamiento.

Algunas de las demostraciones que publicaron incluyen demolición de edificios y demostración. Aquí están usando **Quinn con Klein**, armaron una explosión de color interactiva. Se ve bastante genial.

Así que tendremos que probar algunas de estas cosas: **visualización de terreno en 3D de Google Earth**, una pequeña aplicación para probar tu velocidad de escritura, una pelota rebotando en rotación, un hipercubo, una simulación del sistema solar súper alucinante y un juego en dúo. Está disponible en cómo enfrentas y chateas con **Quen AI**.

Así que voy a hacer una ronda completa de pruebas en esto, pero por el momento, aquí están solo unas pocas pruebas rápidas que realicé. Una es hacer una simulación de un edificio de oficinas con escritorios y oficinas en su interior. Así que intenté hacer que tuviera algún tipo de **ventanas transparentes** en el exterior, pero no pudo hacer transparencia. Eran muy opacas o completamente no transparentes.

Pero logró crear, ya sabes, las habitaciones dentro con escritorios y computadoras y lo que sea que eso sea. Una luz parece una luz en cada habitación. Así que hasta ahora, desde el principio no está nada mal. Quiero decir, esto es bastante bueno para el primer intento.

También creé un pequeño **juego de vuelo de dron** donde puedes volar un dron alrededor de la ciudad. No me puedo quejar, está bastante bien. Quiero decir, las teclas son un poco raras, pero lo estoy disfrutando hasta ahora. Toma un poco acostumbrarse, pero una vez que logras controlar el acelerador, puedes volar alrededor y no está mal para hacerlo de una sola vez.

Tenemos un **clon de Minecraft**. ¿Dónde estaríamos sin un clon de Minecraft? Puedes colocar bloques y construir y moverte. No está nada mal, pude lograr esto bastante fácilmente.

Así que échale un vistazo, déjame saber qué piensas al respecto. Más pruebas y casos de uso vienen muy, muy pronto. Además, alguien hizo este pequeño hack para **clot code** y ahora, ¿por qué no tuvimos esto todo el tiempo?

A través de la lista de tareas. Creando la **lista de cosas por hacer**. Señor. Comenzando ajustes de código Python. Hazlo así, número uno. Trabajando a través de la lista de tareas. De hecho, eso podría resultar un poco molesto bastante rápido.

Y tengo que decir, no esperaba que la IA de código abierto fuera tan buena. Creo que esperábamos que estuviera, digamos, a lo sumo unos pocos años detrás de los laboratorios de frontera. Ahora, parece que están a unos meses. **Qué momento para estar vivo.**
**Artículo de referencia:** [Ver en Viddo](https://viddo.pro/zh/video-result/de3fa85b-5156-4186-a39d-60c839fb0371)