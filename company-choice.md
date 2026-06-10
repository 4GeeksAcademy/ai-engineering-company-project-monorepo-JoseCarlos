# Your company context

**Replace this file** with the CONTEXT for your assigned company:

- **Brasaland** — `CONTEXT-brasaland-briefing.md` (grilled food restaurant chain, Colombia + Florida)
- **TrackFlow** — `CONTEXT-trackflow-briefing.md` (last-mile delivery and warehouse, Mexico + Spain)
- **Nexova** — `CONTEXT-nexova-briefing.md` (HR consulting and talent acquisition, Chile + Argentina)

Your instructor or milestone materials will point you to the correct CONTEXT file. Copy its contents here so that all project work and AI assistance use the same domain data, field names, and constraints.

---

_Until you add your context, keep this placeholder so the repo structure is clear._

# Mi elección: Trackflow

La empresa que he elegido es Trackflow. Tras una lectura y análisis de qué problemas hay que solventar en Trackflow, he llegado a la conclusión de que es la empresa que más va con mis habilidades y gustos. 
- Me gusta mucho el diseño de sistemas, y me gustaría aprender y aplicar el diseño de sistemas a esta empresa. La relación que existe entre los departamentos (el control de stock y entrada de pedidos, que de esos pedidos algunos sean devoluciones y tengan un protocolo diferente, que estos y otros procesos necesiten ser monitorizados, que la monitorización necesite ser documentada a la hora de extrapolar la información que no da del proceso, etc) y las herramientas que hay que usar para mejorar la eficiencia y funcionamiento me interesan a nivel de poder comprender cómo estructurar todos las habilidades que adquiera en el curso. 
- También me gusta mucho la idea del diseño de APIs que estén conectadas y apliquen soluciones a diferentes departamentos de la empresa.
- El sector de la logística es uno de los que más está implementando la IA para optimizar los procesos, por lo que la aplicación de lo que aprenda tendrá alta utilidad en el mercado.

Los dos departamentos que más me llaman la atención son el de operaciones de almacén, por la posibilidad de crear APIs para controlar la entrada de pedidos, la consulta y control del stock y la mejora de comunicación y conciencia interna de los procesos, y el departamento de tecnología, departamento que al final tiene que monitorizar todas las operaciones que se hacen en la empresa y que tiene problemas relacionados con la integración de todas las habilidades que voy a aprender.
## Mi idea de agente de IA

Un ejemplo de implementación podría ser el seguimiento interno de un paquete desde que se genera un pedido o entra una devolución. En este seguimiento podemos implementar una relación entre la generación del pedido y el stock, para saber si tenemos el producto en almacén, un análisis en tiempo real de qué empresa va a entregarlo en función de la disponibilidad de transportistas que hay en activo, para que demore lo menos posible, y un seguimiento de "vida del pedido" que corresponde al intervalo entre que se crea el pedido y se entrega, para saber posibles retrasos, o priorizar unos pedidos u otros en función del plan que tenga contratado la empresa que suministra ese producto, y de esta manera prestar un servicio más exacto a los modelos que la empresa está vendiendo. De esta manera también podemos controlar y cuantificar la satisfaccíon del cliente ante nuestro servicio, reduciendo retrasos y gestiones no adecuadas. Todo esto se puede implementar creado un objeto "pedido" en el que los diferentes atributos de este vayan cambiando y dándo la información que necesitemos.