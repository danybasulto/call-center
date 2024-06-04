# Descripción del Proyecto

## Proyecto: Call Center

**Descripción:** Una empresa de fabricación de equipos de cómputo necesita un programa que le ayude a llevar un control de las llamadas que sus agentes han atendido durante el día. El programa deberá almacenar los nombres de los agentes con su respectivo horario, número de empleado, número de extensión, horas extras trabajadas, especialidad y la lista de usuarios atendidos durante su turno.

Las especialidades para los agentes pueden ser: **Servidores**, **De escritorio**, **Portátiles**, **Linux**, **Impresoras**, **Redes**.

La secretaria encargada podrá agregar o eliminar agentes como sea necesario, así como usuarios atendidos por cada agente.

**El programa deberá contar con las funcionalidades:**
* Mostrar toda la lista de agentes almacenados.
* Mostrar la lista de agentes filtrados por su especialidad.
* Agregar un agente.
* Encontrar y mostrar los datos de un agente (número de empleado, nombre, especialidad, número de extensión, horario, horas extras y lista de usuarios atendidos) a través del nombre del agente.
* Eliminar un agente a través de su nombre.
* Eliminar todos los agentes.
* Ordenar agentes por su nombre o por especialidad.
* Agregar un cliente a la lista de un agente, ordenado siempre por hora de atención.
* Eliminar un cliente de la lista de clientes atendidos por un agente.
* Eliminar todos los clientes de la lista de un agente.
* Modificar la duración de la llamada de un cliente.
* Guardar toda la lista de agentes y clientes atendidos en almacenamiento secundario.
* Leer toda la lista de agentes y clientes desde almacenamiento secundario.

**Características del programa:**
* El paradigma de programación debe ser orientado a objetos.
* El programa debe basarse en el uso de listas doblemente ligadas para los agentes, y listas simplemente ligadas para los usuarios atendidos por cada agente.
* El método de ordenamiento para los agentes debe ser recursivo.
* La lista de clientes debe ser un atributo de la clase Agente.
* Todos los TDA y sus funciones deben ser programadas por el alumno y contenerse en bibliotecas o colecciones bien definidas. Es decir que no habrán de utilizarse los TDA, o funciones TDA incluidas en el lenguaje de programación elegido.