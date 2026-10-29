# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | 29/10/2026 |
| Versión | v1 |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como usuario registrado, quiero poder buscar recetas utilizando una palabra o frase, filtrando por ingredientes deseados o por ingredientes excluidos y por texto, para encontrar recetas que se adapten a mis necesidades.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** [Capacidad]

Como usuario registrado, quiero poder buscar recetas utilizando una palabra clave o frase, para obtener recetas concretas.

**Fuentes:** UR-08; UC-21; FR-085; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que estoy en la pantalla de búsqueda, cuando ingreso una palabra clave o frase y ejecuto la busqueda, entonces el sistema debe mostrar un listado de todas las recetas coincidentes.
- **CA-02.** Dado que ingreso un termino de búsqueda, cuando la palabra clave o frase no coincida con ninguna receta registrada, entonces el sistema indicará que no hay resultados y mantendra los criterios de búsqueda.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-02

**Título:** [Capacidad]

Como usuario registrado, quiero poder filtrar por ingredientes, para obtener recetas que contengan dichos elementos.

**Fuentes:** UR-08; UC-21; FR-86; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que estoy en la pantalla de búsqueda, cuando filtro seleccionando ingredientes, entonces el sistema muestra un listado de todas las recetas que incluyan esos ingredientes.
- **CA-02.** Dado que ingreso los ingredientes que quiero filtrar, cuando no coincide esa combinación de ingredientes con ninguna receta validada, entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
