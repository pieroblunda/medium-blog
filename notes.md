# Issues

## Can developer productivity be measured?

https://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/
https://www.indexcode.io/post/best-kpis-to-measure-performance-success-of-software-developers
https://medium.com/swlh/kpis-for-software-developers-how-should-you-measure-your-productivity-2bd062ad74d3
https://shit.management/perfect-team-size-for-agile-software-development/
https://twitter.com/elonmusk/status/1343608616960491521

- El dinero?
Muchos programadores creen que no ganan lo suficiente, y que podrian ser mas productivos con un aumento de salario. El dinero es la consecuencia de ser productivo y no es la causa. 

- Nivel de grupo
Aumentar la cantidad de personas en el equipo no es una solucion. Es anti intuitivo, pero existe un punto optimo para la cantidad de personas que pueden trabajar en un equipo sin crear cuellos de botella. Scrum define este numero entre 3 y 9. Si bien dentro de este rango se puede producir mas, tambien se debe gastar mas y esto no es mejorar la eficiencia.

---


## Planning a sprint in the right way

As scrum master and agile coach Robbin Schuurman writes:
“There are always too many features that would add value, therefore creating a lack of focus on the vision and goals. By focusing on the features too much, the roadmap will turn into an overloaded product backlog, instead of a high-level, strategic plan for the products' future development.”

Before a sprint gets underway, you need to know what you’re trying to accomplish and how you’re going to get there. The what is your Sprint goal: Simply put, what you want to have delivered by the end of the sprint. Sprint goals are a great “why” for your team—keeping them motivated.

Remember the classic sprint planning image. 





- Calcular una media del Sprint en base a puntos de Fibonacci
- Fifo (Hacer primero lo que llega primero)
- Bug first
- Velocidad
- Horas

- Goal
- Nice to have

Categorias:
- nuevo
- Mejora
- ux
- Debito tecnico
- Bug

Muchos project managers tienen como principal objetivo el no pasarse de las estimaciones y de esta manera dejar contento al cliente. Basan su éxito en el cumplimiento del diagrama de gantt. Entonces, al final del proyecto estaran todas las tareas hechas en el tiempo estipulado y todos estaran felices. En consecuencia generan una modalidad de trabajo basada en la estimación de cada actividad. Cuando la realidad no coincide con el gantt, los PM infieren qué hay un problema con las estimaciones.

Hay varios problemas con esto. En el caso de un proyecto llave en mano el cliente tiene que saber una fecha deadline antes de firmar el contrato, pero los programadores estiman la tarea despues. Empieza una historia como el huevo y la gallina. Ademas, los programadores deben cumplir una fecha impuesta por otros y no es un objetivo propio. Esto deja no deja espacio para cambios futuros y el modelo no se adapta a la realidad.

Otros PM eligen primero estimar tareas (quizas con puntos de Fibonacci), definir un objetivo de esfuerzo medido en puntos a realizar y planifican un sprint que incluye una cantidad de esfuerzo aceptable. De nuevo, hay algunos problemas con este metodo y encuentro la solucion muy alejada de la realidad. De esta manera se cumplen los objetivos aunque no se lleve valor al cliente. En consecuencia se transforma en un proyecto de software y no en un proyecto de negocios. El cliente no se siente satisfecho y no hay colaboracion entre el cliente y la parte tecnica. Por otro lado, es muy facil manipular el resultado: basta simplemente poner puntos mas altos para cada tarea. Es por esto que los puntos Fibonacci no son un KPI.

Entonces... como elijo las tareas a incluir en el sprint?

## Changing the paradigm

Que debemos hacer? Por que lo hacemos? Cada sprint tiene un objetivo definido por el Cliente o el Product Owner. Si el cliente esta satisfecho entonces el proyecto tiene exito. Por el contrario, cuando se presentan disconformidades de parte del cliente, debemos actuar en consecuencia para resolverlo. Con este enfoque es claro que el cliente tiene la respuesta. Con este nuevo punto de vista, el tiempo no es una variable de la ecuacion.

Entonces en primer lugar ponemos a

Tiempo-Precio-Calidad

Ferrari:
Tiempo  | Proveedor (2 anos a la entrega)
Precio  | Cliente
Calidad | Cliente

Toyota:
Tiempo  | Cliente
Precio  | Proveedor
Calidad | Cliente

Karting:
Tiempo  | Cliente
Precio  | Cliente
Calidad | Proveedor

No existen bienes escasos con estas taracteristicas. En esconomia se consideran superabundantes como el aire:
Tiempo  | Cliente
Precio  | Cliente
Calidad | Cliente

Agile:
Tiempo  | Proveedor
Precio  | Cliente
Calidad | Cliente

Tiempo (Cliente) - Precio (Cliente) - Calidad (Programador) <- Modelo tradicional
Tiempo (Programador) - Precio (Cliente) - Calidad (Cliente) <- Agile


Metodos para agregar tareas



Second, don’t forget to include bug fixes and reducing technical debt. As scrum master and Agile coach, Stefan Wolpers, explains:
The rule of thumb is that 25% of resources are allocated every sprint to fix bugs and refactor the code base. If the product owner ignores this practice, and the development team accepts this violation the scrum team will find itself in a downward spiral. Its future product delivery capability will decrease.

Stefan Wolpers
I have worked for 14-plus years as an Scrum Master, Product Owner, and agile coach. Professional Scrum Trainer (PST) with Scrum.org.
https://stefanw.medium.com

The rule of thumb is that 25% of resources are allocated every sprint to fix bugs and refactor the code base. If the product owner ignores this practice, and the development team accepts this violation the scrum team will find itself in a downward spiral. Its future product delivery capability will decrease. (by Stefan Wolpers)


Robbin Schuurman
"Siempre hay demasiadas características que agregarían valor, creando por lo tanto una falta de enfoque en la visión y los objetivos. Al centrarse demasiado en las funciones, la hoja de ruta se convertirá en una sobrecarga de productos pendientes, en lugar de un plan estratégico de alto nivel para el desarrollo futuro de los productos"
https://www.scrum.org/robbin-schuurman
https://medium.com/@robbinschuurman