# LlanquihueTourApp

## Descripción

Aplicación desarrollada en Java para gestionar información de tours turísticos de la agencia Llanquihue Tour.

El sistema lee información desde un archivo de texto, crea objetos de tipo Tour, los almacena en una colección ArrayList y permite mostrar y filtrar información según criterios definidos.

## Estructura del Proyecto
```text
LlanquihueTourApp
│
├── src
│   ├── model
│   │   └── Tour.java
│   ├── data
│   │   └── GestorDatos.java
│   └── ui
│       └── Main.java
│
├── resources
│   └── tours.txt
│
└── README.md
````
## Funcionalidades

- Lectura de archivo tours.txt.
- Creación de objetos Tour.
- Almacenamiento en ArrayList.
- Recorrido de la colección.
- Filtrado de tours según cantidad de participantes.

## Ejecución

1. Abrir el proyecto en IntelliJ IDEA.
2. Verificar que el archivo tours.txt se encuentre en la carpeta resources.
3. Ejecutar la clase Main.java.
4. Visualizar los resultados en consola.

## Autor

Sebastián Estrada
