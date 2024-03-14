<h1 aling="center"> #Programa de Gestión de Vehículos </h1>

Este programa te permite gestionar una lista de vehículos, incluyendo:

- **Crear** vehículos de diferentes tipos (coche, camión, yate, moto).
- **Mostrar** la información de los vehículos, incluyendo el consumo de gasolina.
- **Calcular** el consumo de gasolina de cada vehículo.

##Inquietudes y decisiones

Al desarrollar este programa, se tuvieron en cuenta las siguientes inquietudes:

**_¿Cómo representar la diversidad de tipos de vehículos?_** Se decidió utilizar herencia para crear clases específicas para cada tipo de vehículo (coche, camión, yate, moto).
**_¿Cómo calcular el consumo de gasolina?_** Se desarrolló una fórmula que toma en cuenta la potencia del motor, el peso del motor y el tipo de chasis.
**_¿Cómo mostrar la información de los vehículos de forma clara y organizada?_** Se utilizó una función para mostrar la información de cada vehículo, incluyendo el consumo de gasolina.
Técnicas y arquitectura

##El programa está escrito en Python y utiliza las siguientes técnicas:

* _Programación orientada a objetos_: Se utilizan clases para representar los diferentes tipos de vehículos.
* _Hereditaria_: Se utiliza la herencia para crear clases específicas para cada tipo de vehículo.
* _Polimorfismo_: Se utiliza el polimorfismo para mostrar la información de los vehículos de forma clara y organizada.

##La arquitectura del programa es la siguiente:

**Módulo**\_main.py\_: Contiene la función principal del programa, que permite al usuario crear, mostrar y gestionar una lista de vehículos.
**Módulo** \_vehiculo.py\_: Define las clases Vehiculo, Motor, Coche, Camion, Yate y Moto.

**Funcionamiento del algoritmo**
El algoritmo principal del programa funciona de la siguiente manera:

1.Se crea una lista vacía para almacenar los vehículos.
2.Se presenta un menú al usuario con las opciones de crear un vehículo, mostrar los vehículos o salir del programa.
3.Si el usuario elige crear un vehículo, se le pide que introduzca la información del vehículo, como el tipo de vehículo, el modelo, el año, el chasis y la potencia del motor.
4.Se crea un nuevo objeto Vehiculo de la clase correspondiente al tipo de vehículo seleccionado.
5.Se añade el nuevo objeto Vehiculo a la lista.
6.Si el usuario elige mostrar los vehículos, se muestra la información de cada vehículo en la lista, incluyendo el consumo de gasolina. 
7.Si el usuario elige salir del programa, se termina el programa. 