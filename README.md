# Arquitectura de Software

La arquitectura de software se refiere al diseño de alto nivel de un sistema de software. Es la representación abstracta y estructurada de cómo diferentes componentes de un software interactúan entre sí y cómo se organizan para lograr los objetivos del sistema. La arquitectura de software establece las bases y las directrices para la construcción del software, y es esencial para garantizar que el software sea eficiente, escalable, mantenible y cumpla con los requisitos funcionales y no funcionales.

> Es el diseño de más alto nivel de la estructura de un sistema, el cual consiste en un conjunto de patrones y abstracciones que proporcionan un marco claro para la implementación de un sistema.


### Aspectos clave de la arquitectura de software:

**1. Componentes:** Define los módulos o componentes principales del sistema y cómo se relacionan entre sí. Estos componentes pueden ser módulos de software, servicios, subsistemas, bases de datos, etc.

**2. Estructura:** Describe la organización y la relación entre componentes, incluyendo cómo se comunican y cómo fluye la información entre ellos.

**3. Comportamiento:** Define cómo se ejecuta el software, cómo responde a las entradas y cómo se comporta en diferentes situaciones.

**4. Escalabilidad:** Considera cómo el sistema puede crecer y adaptarse a medida que se requieran más recursos o se agreguen nuevas funcionalidades.

**5. Rendimiento:** Se preocupa por la eficiencia del sistema, incluyendo la velocidad de respuesta, la utilización de recursos y la capacidad de gestionar cargas de trabajo pesadas.

**6. Mantenibilidad:** Evalúa la facilidad con la que el software puede mantenerse a lo largo del tiempo, lo que implica la capacidad de realizar cambios y correcciones de manera eficiente.

**7. Seguridad:** Aborda las medidas de seguridad que se deben implementar para proteger el sistema contra amenazas y vulnerabilidades.

**8. Requisitos no funcionales:** Incluye aspectos como la usabilidad, la disponibilidad, la confiabilidad y otros requisitos que no están relacionados directamente con las funciones principales del software, pero son importantes para su calidad global.

La arquitectura de software puede representarse a través de diversos modelos y diagramas, como diagramas de flujo, diagramas de componentes, diagramas de despliegue, entre otros. El proceso de diseño de la arquitectura de software suele ser una etapa crucial en el desarrollo de proyectos de software, ya que sienta las bases para la implementación y el desarrollo subsiguiente. Una buena arquitectura de software contribuye a la eficiencia del desarrollo, la calidad del producto y la capacidad de mantener y evolucionar el software con el tiempo.

>  Básicamente, la arquitectura de software es un conjunto de estructuras:



**Estructura:** Cómo organizar las partes del sistema y cómo conectarlas; en esto aplican los patrones de arquitectura como eventos, capas, microservicios; te van a decir qué componentes necesitas y cómo se van a conectar entre ellos.

- **Razonar:** Facilita la idea de dialogar sobre el futuro del software a un alto nivel que facilita la comunicación entre ellos.

- **Decisiones de diseño:** Las decisiones de diseño (cómo van a ir conectados los microservicios o el diseño de la aplicación) deben ir documentadas para comprender y entender cómo llevar a cabo la app.

- **Atributos de calidad:** Existen muchos atributos de calidad que permiten definir qué es lo que va más allá de lo funcional y que permite que el sistema funcione bien.

  "*La arquitectura es acerca de las cosas importantes, no importa qué sean esas cosas".*  ~*Raf Johnson*




### ¿Qué hace un arquitecto de software?

Para ello tendremos en cuenta 11 actividades que relizan todos los arquitectos.

**1. Define y balancea los atributos de calidad:** Por atributos de calidad hacemos referencia a Escalabilidad, Elasticidad, Modificabilidad, Facilidad en el despliege del codigo, son parte fundamental del trabajo del arquitecto. Entonces, su tarea es encontrar esos atributos de calidad que sean relevantes y no solo definirlos, si no balancearlos, sin embargo para tener en cuenta; dentro de más atributos de calidad tenga un sistema, más difícil será de desarrollar y mantener, por ende; su tarea es saber escojer sobre cuales atributos implementar y cuales sacrificar en pro de tener un sistema más eficiente.

**2. Definir el problema desde un punto de vista de ingeniería:** El arquitecto debe de tomar los requerimientos (historias de usuario), atributos de calidad y restrictiones que haya en el diseño, planteando un sistema que resuelva el problema.

**3. Establecer los principios de diseño que guían las desiciones de tecnología de una empresa:**  El arquitecto debe de estar involucrado en cada desición que se lleve a cabo en el proyecto, como el uso de una librería, un patrón, etc. Este arquitecto debe de ser capaz de definir los lineamientos que le faciliten a su equipo de desarrollo ciertas capacidades de diseño y guiarlos como lider en el proceso de la toma de desiciones.

**4. Garantizar el cumplimiento de la arquitectura:** El arquitecto no solo crea o plantea la arquitectura incial y lineamientos del diseño, si no que también debe de involucrarse de alguna forma para garantizar que la arquitectura se cumpla; esto dado que en el proceso de desarrollo de un software, siempre hay pequeños desvios de la arquitectura.

**5. Mantenerse al día de las tendencias tecnológicas y de la industria:** El arquitecto debe de mantenerse al día de lo que marca tendecia a nivel tecnológico y conocer que cosas vienen y qué nuevos desarrollos se están dando. Como el arquitecto también es un componente importante en la parte del negocio, es muy importante que este tenga conocimiento sobre las tendencias en la industria del negocio donde trabaja.

**6. Conocer multimples teconologías, plataformas y ambientes:**  Este conocimiento es fundamental para que el arquitecto conozca muy bien la ruta y de su equipo para poder elegir la estrucruta que ha de implementar y decidir según su conocimiento.

**7. Analizar el entorno y proponer mejoras para que la arquitectura de su sistema se mantenga relevante:** Esto dado que el la tecnología va evolucionando con el tiempo, haciendo que a su ves el software antiguo quede obsoleto y los intereses de los usuarios estén o se mantengan en constante cambio.

**8. Administrar la deuda técnica:** La deuda técnica es la diferencia entre el estado actual del sistema y el estado ideal o que debería de tener. El aquitecto sabe cuando debe de sacrificar algo que debería de tener el software con tal de balancear otras cosas, pero que a su vez debe saber como disminir esa diferencia en la deuda técnica de los sistemas.

**9. Entiende y sabe moverse en el entorno político de la empresa:** Esto dado que el arquitecto es el encargado de tomar las desiociones que afectan directamente al equipo técnico de su empresa si no que también puede afectar muchos cargos en la empresa; dependiendo de como se manejen las desiciones puede cambiar la forma en la que una persona trabaja o pueden desaparecer personas o cargos dentro de la entidad por el impacto de estas decisiones. Entonces, el arquitecto, no solo toma decisiones técnicas a la lijera si no que también entiende el contexto de su posición y de la entidad donde trabaja, conociendo como realizar sus tareas para que tengan el impacto correcto en la organizacion.

**10. Mentoría:** Un arquitecto no solo es el encargado de la estructura del software si no que es el guía, lider y mentor, teniendo la capacidad de transmitir su conocimiento a los demás mienbros del equipo; este se preocupa por el conocimiento de los miembros de su equipo para que mejoren sus capacidades de diseño con el tiempo, dado que el diseño es un ejercisio colaborativo.

**11. Un arquitecto de software desarrolla:** El arquitecto se involucra de alguna forma en el desarrollo del codigo, de alguna forma en la que sea efectivo. Esto para que se exista un seguimiento del rumbo del software y entender las consecuencias de lo que se esté construyendo.


## Introducción a la arquitectura de software

 Para convertirte en un arquitecto de sorftware  tendremos en cuenta 3 aspectos importantes:

**Conociento**: Según **Mark Richards** el conocimiento se divide en 3 partes las cuales se representan en el siguiente gráfico:
![image-20231010091618594](./Assets/Screenshot%20from%202023-10-10%2009-16-12.png)

Como desarrollador es importante tener esa profundidad técnica (ampliar la punta de la piramide); si te desemeñas en algo, debes de tener un gran conocimiento en ello. 

Como arquitecto la situación es un poco distinta; para el arquitecto lo que más importa es la amplitud, ya no interesa tanto ser un experto en una sola herramienta, si no que conocer de muchas herramientas, abarcando así la capa de lo que sabes que no sabes.

Puntualmente se debe de conocer multiples plataformas, teconologías, ambientes y lenguajes, saliendote así de tu forma de confort probando algo distinto.

1. **Ampliar tu conocimiento**, conocer mulltiples plataformas, tecnológias ambientes y lenguajes

2. **Conocer los atributos de calidad**, también conocidos como requerimientos no funcionales o caracteríasticas de arquitectura, esto incluye lo siguiente:

   | Atributo de Calidad     | Descripción                                                  |
   | ----------------------- | ------------------------------------------------------------ |
   | Agilidad                | Adaptación rápida a cambios y requerimientos.                |
   | Confiabilidad           | Funcionamiento sin errores y protección de datos.            |
   | Desplegabilidad         | Facilidad de implementación y actualización.                 |
   | Disponibilidad          | Garantía de funcionamiento cuando se necesita.               |
   | Escalabilidad           | Capacidad para crecer sin degradación del rendimiento.       |
   | Facilidad de desarrollo | Simplificación del proceso de creación y mantenimiento.      |
   | Interoperabilidad       | Capacidad para interactuar con otros sistemas.               |
   | Mantenibilidad          | Facilita la modificación, reparación y mejora.               |
   | Modificabilidad         | Facilidad para realizar cambios sin afectar el sistema.      |
   | Portabilidad            | Ejecución en diferentes plataformas sin modificaciones.      |
   | Rendimiento             | Ofrecer alta velocidad y eficiencia.                         |
   | Seguridad               | Protección contra amenazas y seguridad de datos.             |
   | Testeabilidad           | Facilita la realización de pruebas y detección de problemas. |
   | Usabilidad              | Facilita la interacción efectiva y satisfactoria de los usuarios. |

   <br>

3. **Patrones de arquitectura y de Diseño** 

   | Patrón de Diseño                   | Descripción                                                  |
   | ---------------------------------- | ------------------------------------------------------------ |
   | Patrón Singleton                   | Garantiza una única instancia de una clase.                  |
   | Patrón Factory                     | Crea objetos sin especificar su clase concreta.              |
   | Patrón Builder                     | Construye objetos complejos paso a paso.                     |
   | Patrón Prototype                   | Clona objetos existentes para crear nuevos.                  |
   | Patrón Adapter                     | Permite que interfaces incompatibles trabajen juntas.        |
   | Patrón Decorator                   | Añade responsabilidades a objetos de forma dinámica.         |
   | Patrón Observer                    | Define una dependencia uno a muchos entre objetos.           |
   | Patrón Strategy                    | Permite seleccionar algoritmos en tiempo de ejecución.       |
   | Patrón Command                     | Encapsula una solicitud como un objeto.                      |
   | Patrón Template Method             | Define el esqueleto de un algoritmo, dejando algunos pasos a las subclases. |
   | Patrón State                       | Permite que un objeto altere su comportamiento cuando su estado cambia. |
   | Patrón Composite                   | Compone objetos en estructuras de árbol para representar jerarquías. |
   | Patrón Proxy                       | Proporciona un sustituto o representante de otro objeto.     |
   | Patrón Chain of Responsibility     | Encadena objetos para manejar una solicitud secuencialmente. |
   | Patrón MVC (Model-View-Controller) | Divide una aplicación en tres componentes: Modelo, Vista y Controlador. |

   <br>

4. **Inregración y entrega continua**: Tiempos reservados de pequeñas entregas (modulos/sprints) para llevar un control del desarrollo del aplicativo.

5. **Experiencia como desarrollador** (idealmente fullstack)

6. **Habilidades Blandas, Soft skills, people skills**

   | Tema                     | Descripción                                                  |
   | ------------------------ | ------------------------------------------------------------ |
   | Liderazgo                | Habilidad para guiar, motivar y dirigir un grupo o equipo hacia metas y objetivos comunes. Involucra la toma de decisiones y la gestión de personas. |
   | Comunicación             | Capacidad para transmitir ideas, pensamientos y mensajes de manera efectiva y comprensible. Implica escuchar, expresarse y adaptarse al público. |
   | Negociación              | Habilidad para llegar a acuerdos mutuamente beneficiosos al tratar con conflictos, intereses opuestos o diferencias de opinión. |
   | Trabajo en equipo        | Capacidad para colaborar y coordinar esfuerzos con otros para lograr metas comunes. Involucra la comunicación, la empatía y la resolución de conflictos. |
   | Pragmatismo              | Enfoque filosófico que prioriza la utilidad y la eficacia práctica en la toma de decisiones y la búsqueda de la verdad, en lugar de abstracciones teóricas. |
   | Capacidad de abstracción | Habilidad para simplificar información, identificar patrones y conceptos generales a partir de detalles y datos específicos. Facilita la comprensión y el pensamiento conceptual. |


<br>

## Habilidades blandas (Soft Skills)

Dado que el arquitecto es el líder de todo un equipo, su capacidad de comunicación debe ser superior para el entendimiento de todos en la entidad, comprender, adaptarse y liderar es fundamental para poder resolver los conflictos que se presenten en su trayectoria como líder.

> Estas son algunas de las habilidades más importantes que debes tener como arquitecto de software.

1. **Capacidad de negociación:** El arquitecto siempre ha de estar en un punto medio entre el manejo del negocio, los desarrolladores, los usuarios, etc. Además, siempre se ha de estar buscando llegar a un acuerdo con distintas partes, ya sea implementar una arquitectura que tome un poco de tiempo planear, la implementación de un atributo de calidad muy importante que para el usuario no lo es; en este caso, el arquitecto ha de intentar convencer. En otros casos, ocurrirá que se tendrá que adquirir deuda técnica para sacar adelante algo que sea más importante, por ende, se tendrá que razonar con el cliente dada la entrega.

2. **Amabilidad:** Ser alguien del que se habla bien cuando no está ahí.

   - Capacidad de poder tener buenas relaciones.
   - Conservar esas relaciones por encima de imponerse sobre una idea.
   - Ser una persona que no guarda rencores.

   > En general, una persona a la que las personas estiman.

3. **Liderazgo:** Capacidad de liderar, orientarlo al logro, ser un guía y mentor.

4. **Comunicación:** Dado que el arquitecto es el puente entre los desarrolladores y el mundo, es fundamental que esa persona tenga muy buenas habilidades comunicativas.

5. **Pragmatismo:** Capacidad de tomar decisiones que técnicamente no son las que quisieras, pero que vayan a favor del objetivo y la comodidad de tus desarrolladores.

6. **Visión:** Capacidad de ver el panorama completo, observar cómo está conectado el sistema y cómo influye en el negocio y en el mundo que lo rodea.

   > Tener una visión a 10.000 pies de altura.

7. **Innovación:** Capacidad de estar aprendiendo constantemente y aplicar lo aprendido sobre su arquitectura, realizando así que esta se mantenga relevante.

