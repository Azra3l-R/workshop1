# TEND - Asistente de Salud Mental

## Autores
- **Ronaldo Andres Alvarado Doria** - 20251020122
- **Juliana Valentina Reyes Moreno** - 20251020109  
- **David Esteban Ramirez Gordillo** - 20242020110

## Introducción al Proyecto

El proyecto TEND surge como respuesta a la creciente necesidad de herramientas digitales accesibles y efectivas para el cuidado de la salud mental. En un contexto donde los problemas de salud mental afectan a una proporción significativa de la población, y considerando las barreras que existen para acceder a servicios profesionales tradicionales, TEND se propone como un puente entre el autocuidado y la atención profesional.

La aplicación está diseñada específicamente para acompañar a los usuarios en su día a día, permitiéndoles registrar sus estados emocionales, hábitos cotidianos y reflexiones personales de manera intuitiva y segura. Más allá de ser un simple tracker de emociones, TEND incorpora un sistema inteligente de recomendaciones basado en los patrones detectados, así como la posibilidad de conectar con profesionales de la salud mental certificados cuando el usuario lo considere necesario.

El desarrollo de TEND se enmarca dentro del curso de Programación Orientada a Objetos, donde no solo se busca aplicar los conceptos técnicos aprendidos, sino también abordar un problema real con sensibilidad y rigor profesional. La aproximación al proyecto ha sido multidisciplinaria, combinando principios de ingeniería de software con consideraciones de diseño centrado en el usuario y ética aplicada a la salud digital.

## Metodología de Desarrollo

El proceso de desarrollo de TEND siguió una metodología estructurada en cuatro fases principales, cada una con objetivos específicos y entregables claramente definidos. Esta aproximación secuencial permitió asegurar que cada aspecto del proyecto fuera abordado con la profundidad y detalle necesarios, construyendo progresivamente una solución robusta y bien fundamentada.

La primera fase consistió en el análisis exhaustivo de requerimientos, donde se identificaron y documentaron tanto las necesidades funcionales como las no funcionales del sistema. Para los requerimientos funcionales, se establecieron ocho categorías principales que abarcan todas las capacidades que la aplicación debe ofrecer, desde la gestión básica de usuarios hasta funcionalidades avanzadas como el sistema de recomendaciones y la conexión con profesionales. En cuanto a los requerimientos no funcionales, se dio especial importancia a aspectos críticos como la seguridad y privacidad de los datos sensibles, la usabilidad de la interfaz, y el rendimiento del sistema, estableciendo métricas concretas como un tiempo de respuesta inferior a dos segundos para las operaciones críticas.

La segunda fase se centró en el desarrollo de historias de usuario, donde se tradujeron los requerimientos identificados en narrativas concretas que representan las necesidades y expectativas de los diferentes tipos de usuarios que interactuarán con la aplicación. Se crearon seis historias principales que cubren escenarios como el registro inicial, el uso diario de las funcionalidades de tracking, y la interacción con el sistema de recomendaciones y profesionales. Cada historia incluyó criterios de aceptación específicos y medibles, asegurando que el desarrollo futuro pueda validarse objetivamente contra estos criterios.

En la tercera fase, se procedió al diseño de la interfaz de usuario mediante la creación de mockups detallados. Este proceso involucró la conceptualización del flujo de navegación, la disposición de los elementos en cada pantalla, y la definición del lenguaje visual de la aplicación. Se prestó especial atención a principios de diseño centrado en el usuario, buscando crear una experiencia intuitiva y accesible incluso para usuarios con poca familiaridad con aplicaciones de salud digital. Los mockups resultantes abarcan todas las pantallas principales, desde la autenticación hasta las vistas de análisis y recomendaciones.

La cuarta y última fase consistió en el diseño de la arquitectura orientada a objetos mediante la técnica de tarjetas CRC (Class-Responsibility-Collaborator). En esta fase se identificaron las clases principales del sistema, se definieron sus responsabilidades específicas, y se establecieron las colaboraciones entre ellas. Este ejercicio permitió trasladar los requerimientos funcionales a una estructura técnica coherente y escalable, sentando las bases para la implementación futura del sistema.

## Arquitectura del Sistema

La arquitectura de TEND fue diseñada siguiendo principios sólidos de ingeniería de software y patrones de diseño establecidos. El sistema adopta una arquitectura en capas que separa claramente las responsabilidades entre la presentación, la lógica de negocio y la persistencia de datos. Esta separación facilita el mantenimiento, la escalabilidad y la evolución futura de la aplicación.

En el núcleo del sistema se encuentran ocho clases principales que encapsulan la funcionalidad esencial de la aplicación. La clase Usuario gestiona toda la información relacionada con los perfiles de usuario, incluyendo la autenticación y las preferencias personales. La clase GestorEmociones se encarga del registro y seguimiento de los estados emocionales, implementando la lógica para la codificación por colores y el análisis temporal de los patrones emocionales. La clase DiarioPersonal administra las entradas del diario, garantizando la privacidad y seguridad de estos datos sensibles mediante mecanismos de encriptación y control de acceso.

El sistema de recomendaciones inteligentes está encapsulado en la clase MotorRecomendaciones, que analiza los datos históricos del usuario para generar sugerencias personalizadas de actividades y prácticas de autocuidado. La clase GestorEstadísticas procesa los datos recopilados para generar reportes y visualizaciones que ayudan al usuario a comprender su evolución temporal. La conexión con profesionales de la salud mental es gestionada por la clase ComunicacionProfesionales, que implementa los protocolos necesarios para garantizar intercambios seguros y éticos.

Se aplicaron varios patrones de diseño para optimizar la estructura del sistema. El patrón Modelo-Vista-Controlador (MVC) organiza la separación entre la interfaz de usuario y la lógica de negocio. El patrón Singleton se utiliza para clases de configuración que requieren una única instancia global. El patrón Observer facilita la implementación del sistema de notificaciones, permitiendo que diferentes componentes del sistema reaccionen a cambios en el estado del usuario.

El flujo de datos en TEND sigue un modelo coherente donde la información fluye desde las interfaces de usuario hacia los módulos de procesamiento, luego a los sistemas de almacenamiento, y finalmente de vuelta a la presentación en forma de insights y recomendaciones. Este flujo está diseñado para minimizar la latencia en las operaciones críticas mientras se mantiene la integridad y seguridad de los datos en todo momento.

## Resultados y Entregables

El proceso de desarrollo de TEND ha generado una serie de entregables comprehensivos que documentan cada aspecto del diseño del sistema. La documentación de requerimientos establece una base sólida para el desarrollo futuro, especificando no solo lo que el sistema debe hacer, sino también cómo debe hacerlo en términos de calidad, seguridad y experiencia de usuario. Este documento incluye consideraciones detalladas sobre el manejo ético de datos sensibles y las salvaguardas necesarias para proteger la privacidad de los usuarios.

Las historias de usuario desarrolladas representan un puente efectivo entre los requisitos técnicos y las necesidades humanas, asegurando que el sistema final esté genuinamente centrado en el usuario. Cada historia captura no solo la funcionalidad requerida, sino también el contexto emocional y práctico en el que se utilizará la aplicación. Los criterios de aceptación asociados proporcionan métricas claras para validar el éxito de la implementación futura.

Los mockups de interfaz de usuario constituyen una visualización tangible de cómo los usuarios interactuarán con TEND. Estos prototipos reflejan un equilibrio cuidadoso entre funcionalidad compleja y simplicidad de uso, empleando principios de diseño visual que promueven la calma y la claridad. La navegación fue diseñada para ser intuitiva, reduciendo la carga cognitiva especialmente importante en una aplicación destinada a momentos de vulnerabilidad emocional.

Las tarjetas CRC representan la traducción exitosa de los requisitos funcionales a una arquitectura técnica viable. La identificación de ocho clases principales con responsabilidades bien definidas y colaboraciones claras establece una base sólida para la implementación orientada a objetos. La arquitectura resultante demuestra cohesión dentro de cada clase y acoplamiento controlado entre ellas, principios esenciales para un sistema mantenible y escalable.

Además de estos entregables específicos, el proceso de desarrollo generó insights valiosos sobre el diseño de aplicaciones de salud mental. Se establecieron protocolos para el manejo ético de datos sensibles, se definieron límites claros entre el apoyo automatizado y la intervención profesional, y se desarrollaron guías para crear experiencias digitales que sean tanto técnicas robustas como emocionalmente sensitivas.

## Conclusiones y Trabajo Futuro

El proyecto TEND ha demostrado la viabilidad y el valor potencial de una aplicación móvil integral para el apoyo a la salud mental. A través de un proceso de diseño riguroso y centrado en el usuario, se ha desarrollado una propuesta técnica sólida que aborda tanto los aspectos funcionales como los éticos del manejo digital de la salud mental. La arquitectura orientada a objetos diseñada proporciona una base técnica robusta para una implementación futura, mientras que los principios de diseño establecidos aseguran que la aplicación resultante sea accesible, útil y segura para los usuarios.

Los principales logros del proyecto incluyen la integración exitosa de múltiples perspectivas -técnica, de diseño y ética- en una propuesta coherente. La aplicación resultante no es simplemente un conjunto de características técnicas, sino un sistema holistico diseñado para apoyar genuinamente el bienestar emocional de los usuarios. La atención cuidadosa a aspectos como la privacidad de los datos, la usabilidad de la interfaz, y los límites éticos del apoyo automatizado distingue a TEND de aplicaciones similares en el mercado.

El proceso de diseño también generó aprendizajes significativos sobre los desafíos particulares de desarrollar aplicaciones de salud mental. La necesidad de balancear la profundidad funcional con la simplicidad de uso, la importancia de establecer protocolos claros para situaciones de crisis, y la esencial consideración de la diversidad de experiencias emocionales fueron algunas de las insights más valiosas que emergieron durante el desarrollo del proyecto.

Para las próximas fases del proyecto, se recomienda priorizar la implementación del sistema de registro y seguimiento emocional, ya que constituye el núcleo de la propuesta de valor de TEND. Posteriormente, el desarrollo debería enfocarse en el sistema de recomendaciones inteligentes, seguido por los módulos de conexión con profesionales. Cada fase de implementación debería ir acompañada de pruebas de usabilidad con usuarios reales para refinar continuamente la experiencia.

A largo plazo, TEND tiene el potencial de evolucionar hacia una plataforma más comprehensiva que podría incluir características como comunidades de apoyo moderadas, contenido educativo sobre salud mental, y integraciones más profundas con sistemas de healthcare profesionales. Sin embargo, cualquier expansión futura debería mantenerse fiel a los principios fundamentales establecidos en este diseño inicial: ética robusta, seguridad inquebrantable, y centrado en la experiencia real del usuario.

En conclusión, TEND representa no solo un ejercicio académico exitoso en diseño orientado a objetos, sino también una contribución valuable al emergente campo de la salud mental digital. El enfoque cuidadoso y multidimensional adoptado en el diseño sienta las bases para una aplicación que genuinamente puede marcar una diferencia positiva en la vida de sus usuarios.

---

**Curso:** Programación Orientada a Objetos - 2025-III  
**Universidad:** Universidad Distrital Francisco Jose de Caldas  
**Fecha:** Septiembre 2025
