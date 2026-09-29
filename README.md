# Práctica: Árbol Binario AVL

Este repositorio contiene la implementación y resolución de las operaciones sobre un árbol AVL.

## Estructura Final del Árbol

```mermaid
graph TD
    classDef nodo fill:#87CEEB,stroke:#000,stroke-width:2px,color:#000,font-weight:bold;

    10((10)):::nodo --> 5((5)):::nodo
    10((10)):::nodo --> 17((17)):::nodo

    5((5)):::nodo -.-> NULL1[ ]
    style NULL1 fill:none,stroke:none;
    5((5)):::nodo --> 9((9)):::nodo

    17((17)):::nodo --> 16((16)):::nodo
    17((17)):::nodo --> 20((20)):::nodo

    20((20)):::nodo -.-> NULL2[ ]
    style NULL2 fill:none,stroke:none;
    20((20)):::nodo --> 90((90)):::nodo
```

## Recorridos Obtenidos
* **Preorden:** `[10, 5, 9, 17, 16, 20, 90]`
* **Enorden:** `[5, 9, 10, 16, 17, 20, 90]`
* **Postorden:** `[9, 5, 16, 90, 20, 17, 10]`
