# SOLID-Abierto-Cerrado
Ejemplo en C++ del Principio Abierto - Cerrado (OCP) de SOLID.

Este principio se implementa en este proyecto mediante la herencia entre las clase base Producto y sus derivadas.
En los archivos de la clase Producto, se define que esta va a ser la clase base en donde se administra las propiedades como nombre y precios
con los atributos, setters y getters.

Mientras que en los archivos de las clases derivadas (Digital y Fisico) se heredan de Producto y mas bien añaden sus propios atributos especificos.
