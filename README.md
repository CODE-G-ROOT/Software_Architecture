# Arquitectura de Software

Es el diseño de más alto nivel de la estructura de un sistema, el cual consiste en un conjunto de patrones y abstracciones que proporcionan un marco claro para la implementación de un sistema.

La arquitectura de software se refiere al diseño de alto nivel de un sistema de software. Es la representación abstracta y estructurada de cómo diferentes componentes de un software interactúan entre sí y cómo se organizan para lograr los objetivos del sistema. La arquitectura de software establece las bases y las directrices para la construcción del software, y es esencial para garantizar que el software sea eficiente, escalable, mantenible y cumpla con los requisitos funcionales y no funcionales.


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

Básicamente, la arquitectura de software es un conjunto de estructuras:

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
   1. Agilidad
   2. Confiabilidad
   3. Desplegabilidad
   4. Disponibilidad
   5. Escalabilidad 
   6. Facilidad de desarrolo
   7. Interoperabilidad
   8. Mantenibilidad
   9. Modificabilidad
   10. Portabilidad 
   11. Rendimiento
   12. Seguridad
   13. Testeabilidad
   14. Usabilidad
3. **Patrones de arquitectura y de Diseño** 
4. **Inregración y entrega continua**
5. **Experiencia como desarrollador** (idealmente fullstack)
6. **Habilidades Blandas, Soft skills, people skills**
   1. Liderazgo
   2. Comunicación
   3. Negociación
   4. Trabajo en equipo
   5. Pragmatismo
   6. Capacidad de abstracción


