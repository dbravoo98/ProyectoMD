# Proyecto 1: Representacion y Propiedades de Grafos

## Informacion del Estudiante
* Nombre: David Bravo Ospina
* Codigo: 23771758
* Asignatura: Matematicas Discretas II
* Institucion: Universidad del Valle

---

## Justificacion de la Implementacion
Para este proyecto decidi utilizar una Lista de Adyacencia implementada mediante diccionarios nativos de Python. 

Escogi este metodo porque en Python los diccionarios permiten asociar de forma directa una clave (nodo origen) con otro diccionario (nodos destinos y sus respectivos pesos). Esto hace que buscar si dos vertices estan conectados sea muy facil y eficiente, evitando crear matrices gigantes llenas de ceros que consumen mucha memoria innecesaria si el grafo tiene pocas aristas.

Durante el desarrollo del proyecto me fue bastante bien. La inicializacion usando la herramienta UV facilito mantener el entorno ordenado. El mayor reto fue estructurar la logica de las verificaciones matematicas (como saber si hay ciclos o si es un bosque) utilizando unicamente las funciones recursivas de busqueda en profundidad (DFS) y aplicando las relaciones matematicas elementales vistas en la teoria del curso sin usar librerias de terceros.

---

## Tecnologias Utilizadas
* Lenguaje de programacion: Python 3.13+
* Entorno y Gestor: UV

---

## Funcionalidades Implementadas
* Creacion y almacenamiento de Grafos No Dirigidos.
* Creacion y almacenamiento de Grafos Dirigidos.
* Funcion de carga y lectura automatica desde archivos de texto estructurados por comas (source,target,weight).
* Verificacion de conectividad del grafo.
* Deteccion de ciclos mediante formulas de componentes conexas.
* Clasificacion del grafo para determinar si cumple las condiciones de ser un Arbol o un Bosque.

---

## Instrucciones de Ejecucion
Para ejecutar las pruebas del proyecto y comprobar los resultados impresos en la consola, abre la terminal en la carpeta raiz del proyecto y ejecuta el siguiente comando:

```bash
uv run main.py
```
