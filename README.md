## Patrones de diseño

Es la solución a un problema de diseño, el cual debe haber comprobado su efectividad resolviendo problemas similares en el pasado, también tiene que ser reutilizable, por lo que se deben poder usar para resolver problemas parecidos en contextos diferentes.

**¿Qué es un patrón?**: Básicamente es la solución a un problema.


#### Sistema de patrones P.O.S.A

Según el libro *PATTERN-ORIENTED SOFTWARE ARCHITECTURE* los patrones se dividen en 3: 

- Patrones de arquitectura
- Patrones de diseño
- Idiomas



Un patrón de diseño es el que describe una estrucutra recurrente para comunicar componentes (clases) , que resuelve un problema general de diseño en un contexto particular.



#### Diferencias con un patrón de arquitectura y un idioma

- Son patrones a mediana escala
- Son de más alto nivel que los idiomas
- Son independientes del lenguaje de programación
- No afectan la estructura general del software
- Sí pueden influir en el módulo o un subsistema



#### Tipos de patrones de diseño:

- **Pátrones de creación**: Abstraen el proceso de creación de objetos. Eso aplica muy bien cuando no sabes exactamente qué objeto crear cuando estás escribiendo el codigo.

  - **Singelton**: Resuelve el problema de tener un solo objeto de una sola clase ya sea por consistencia, rendimiento, etc.

  - **Factory Method**: Se encarga de poder crear objetos utilizando una jerarquía de clases

  - **Abstract Factory**: Versón avanzada del Factory Method

  - **Builder**: Permite la creación de un objeto complejo por medio de pasos

  - **Prototype**: Aplica para clonar objetos en vez de crear objetos nuevos

    

- **Pátrones de estructura** : Estos patrones se enfocan en cómo se organizan las clases y objetos para formar estructuras más grandes. Basicamente como conectar las clases, ¿como se organizan?, ¿quien hereda de quien?,  etc.

  Mantiene la estructura de los objetos flexible y eficiente

  - **Adapter**: Aplica para conexión de dos partes del sistema que no son compatibles

  - **Bridge**: Ayuda a conectar jerarquías de objetos

  - **Composite**: Permite modelar jerarquías de estructuras de tipo arbol

  - **Decorator**

  - **Facade**

  - **Flyweight**

  - **Proxy**

    

- **Pátrones de comportamiento**: Se especializan en algoritmos y la asignación de resposabilidades entre objetos. Apartir de estos algoritmos se pueda definir como se comunican los objetos entre sí.

  - **Chain of Resposibility**: 
  - **Comand**: Aplica cunado solo se quiere responsabilizar a un objeto para una tarea en concreto
  - **Interpreter**: 
  - **Iterator**
  - **Mediator**: Permite la comunicación entre objetos
  - **Memento**: Permite controlar el estado de un objeto
  - **Observer**
  - **State**
  - **Strategy**: Permite implementar familias de algoritmos para elegir entre un varios algoritmos
  - **Template Method**
  - **Visitor**



- Algunos otros patrones de diseño:
  - **Object Pool**: 
  - **Private Class Data**
  - **Null Object**
  - **Specification**
  - **Lazy Load**

