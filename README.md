# Examen de Programacion 2

El examen fue realizado en la Universidad Comunera UCOM, el dia Lunes 16 de diciembre de 2024.

# Primera Etapa

Se realizo la Creacion del archivo UML para la visualizacion completa de los datos que requeria el examen,se creo dos clases las cuales son:

<ul>
<li> Coche</li>
<li> Vehiculo</li>
</ul>
las cual Coche que hereda las clases de Vehiculos.

# Segunda Etapa

En la segunda etapa fue el como llegar a lo que el examen pide, realizando el codigo en Jupyter notebook, Usando las herramientas de Python , decidi que la manera de abarcar este proyecto fue la realizacion de clases por la facil manipulacion de los componentes y funciones.
Mediante la creacion de clases , abarque un modelo estandar que contenia lo siguiente puntos:
<ul> 
<li>auto.marca = marca</li>
    <li>    auto.modelo = modelo </li>
        <li>auto.anho = anho </li>
       <li> auto.color = color </li>
</ul>

# Tercera Etapa
Tras la creacion del modelo del cual vamos a abarcar,empece a  crear las clases y las funciones como:
 class Vehiculo:
  def __init__(auto, marca, modelo, anho, color):
        auto.marca = marca
        auto.modelo = modelo
        auto.anho = anho
        auto.color = color
Esta clase hereda las clases de Vehiculo
class Coche(Vehiculo):
  def __init__(auto, marca, modelo, anho, color, numero_puertas, tipo_combustible):
  super().__init__(marca, modelo, anho, color)
  auto.numero_puertas = numero_puertas
  auto.tipo_combustible = tipo_combustible

# Cuarta Etapa visualizacion de los resultados

<img width="415" alt="Screenshot 2024-12-16 at 7 26 20 PM" src="https://github.com/user-attachments/assets/50ace7cf-02ce-4197-bf21-020a5c130428" />




