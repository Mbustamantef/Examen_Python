# Examen de Programacion 2

El examen del Ing.Yan Bajac fue realizado por Matias Bustamante en la Universidad Comunera UCOM el dia 16 de diciembre a las 18:30.

# Primera Etapa

Se realizo la Creacion del archivo UML para la visualizacion completa de los datos que requeria el examen,se creo dos clases las cuales son:
<ul>
<li> Coche</li>
<li> Vehiculo</li>
</ul> 

<img width="422" alt="Uml" src="https://github.com/user-attachments/assets/3c53bce9-8514-4486-a945-147f16fdd81c" />



La cual Coche que hereda las clases de Vehiculos.

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
 class Vehiculo: <br>
  def __init__(auto, marca, modelo, anho, color):<br>
        auto.marca = marca<br>
        auto.modelo = modelo<br>
        auto.anho = anho<br>
        auto.color = color<br>
Esta clase hereda las clases de Vehiculo
class Coche(Vehiculo):<br>
  def __init__(auto, marca, modelo, anho, color, numero_puertas, tipo_combustible):<br>
  super().__init__(marca, modelo, anho, color)<br>
  auto.numero_puertas = numero_puertas<br>
  auto.tipo_combustible = tipo_combustible<br>

# Cuarta Etapa visualizacion de los resultados



<img width="461" alt="resultados" src="https://github.com/user-attachments/assets/edc4c315-1b08-4c9d-9869-39cb6ccde227" />



