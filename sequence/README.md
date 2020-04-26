# Diagramas de secuencia

En sesiones anteriores hemos visto los diagramas de clases y diagramas de casos de uso.

Las sesiones siguientes las vamos a dedicar a entender y adquirir cierta destreza con los diagramas de secuencia. Estos diagramas hacen énfasis en la secuencia de los mensajes intercambiados por los objetos. Típicamente se usan para modelar los casos de uso del sistema y pueden usarse tanto en análisis como en diseño.

Veamos dónde se ubican los diagramas de secuencia con respecto a la tipología establecida en el marco del lenguaje de modelado UML.

## Tipos de diagramas

- Diagramas de estructura
  - Diagrama de clases
  - Diagrama de estructuras compuestas
  - Diagrama de componentes
  - Diagrama de despliegue
  - Diagrama de objetos
  - Diagrama de paquetes
- Diagramas de comportamiento
  - Diagrama de casos de uso
  - Diagramas de interacción
    - Diagrama de secuencia
    - Diagrama de comunicación o colaboración
    - Diagrama de visión global de la interacción
    - Diagrama de tiempo
  - Diagrama de actividad
  - Diagrama de maquina de estados

Hay estudios [1] que revelan que, de los 14 diagramas, los tres diagramas más usados son los de **clases**, **casos de uso** y de **secuencia**.

En en este [enlace de la herramienta de diseño Visual Paradigm](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/overview-of-the-14-uml-diagram-types/#uml-type-states) muestran el siguiente gráfico de estadísticas de uso basado en sus propios muestreos:

![Muestreo de uso de diagramas UML](https://cdn.visual-paradigm.com/guide/uml/learn-the-14-uml-diagram-types/02-popularity-of-different-uml-diagram-types.png)

Ahora bien, si se pregunta a un admnistrador de sistemas, nos dirá con mucha probabilidad que habría que incluir en esa lista los diagramas de **despliegue**. Una persona que trabaje en sistemas concurrentes puede usar mucho los diagramas de **máquina de estados** y alguien con orientación a procesos de negocio encuentra que el diagrama de **actividad** puede servir bien para sus objetivos.




## Material de estudio
En el aula virtual encontraréis una presentación que os servirá de punto de partida y os mostrará los elementos básicos de estos diagramas. A continuación os recomiendo que veáis estos vídeos del canal de youtube de la Universidad Politécnica de valencia, de donde podréis extraer a base de ejemplos, las características principales de los diagramas de secuencia.

* [¿Cómo construir un diagrama de secuencia? Ejemplo de recuperación de información](https://www.youtube.com/watch?v=Q1kH7XKxK5I)
* [¿Cómo construir un diagrama de secuencia? Ejemplo de creación de objetos](https://www.youtube.com/watch?v=jN8cn_5y_xE)

## Herramienta de diseño
Vamos a utilizar [PlantUML](https://plantuml.com/es/sequence-diagram) para elaborar los diagramas vía scripting y así poder documentrarlos con Markdown en GitHub. PlantUML es más completo y se ajusta más a los estándares de UML que [Mermaid](https://mermaid-js.github.io). Se pueden editar diagramas online desde este [editor online](https://www.planttext.com/). En [esta entrada de blog](https://blog.anoff.io/2018-07-31-diagrams-with-plantuml/) hay información sobre cómo trabajar con VSCode y cómo integrar con repositorios GitHub y GitLab.

## Ejemplos
Aquí tenéis unos ejemplos funcionales sobre cómo incrustar el diagrama en páginas GitHub.

### Caso de uso: Cerrar proyecto

![Cerrar proyecto](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/carlosgs-iesgoya/UML/master/sequence/cerrar-proyecto.puml)

### Caso de uso: Borrar tarea

![Borrar tarea](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/carlosgs-iesgoya/UML/master/sequence/borrar-tarea.puml)

### Caso de uso: Actualizar tarea

![Actualizar tarea](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/carlosgs-iesgoya/UML/master/sequence/actualizar-tarea.puml)

## Práctica

* [PCV06-20](PCV06-20/PCV06-20.md)

---
[1]: [Studying the Benefits of Using UML on Software Maintenance: an Evidence-Based Approach](https://ruidera.uclm.es/xmlui/bitstream/handle/10578/22080/TESIS%20Fernandez%20Saez.pdf?sequence=1). Ana M. Fernández Sáez. UCLM. Oct 2018.
