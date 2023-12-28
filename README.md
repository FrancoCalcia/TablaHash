# Programa de Control de Stock con Tabla Hash
Este programa ofrece una solución eficiente para el control de stock de un supermercado mediante el uso de una Tabla Hash. La implementación se centra en la inserción, búsqueda y eliminación de productos, utilizando el método de resolución de colisiones por encadenamiento.

## Descripción General:
El objetivo principal de este programa es proporcionar una herramienta eficaz para gestionar el inventario de un supermercado, optimizando las operaciones de inserción y búsqueda de productos.

## Componentes Clave:
*Clase Clave:*
- Almacena la clave real a ser hasheada y encapsula el algoritmo de hash.
- Permite convertir el valor de la clave en un número entero.
- Determina si dos claves son iguales.

*Interfaz del TAD Diccionario:*
- Define las operaciones básicas del diccionario: insertar, buscar y eliminar.

*Clase ListaEnlazada:*
- Implementa una lista enlazada para resolver colisiones por encadenamiento.
- Permite agregar y eliminar elementos de la lista.

*Clase HashTable (Tabla Hash):*
- Utiliza una tabla de tamaño fijo con resolución de colisiones por encadenamiento.
- Proporciona métodos para insertar, buscar y eliminar elementos.
- Calcula el factor de carga y la longitud de la lista más larga.
