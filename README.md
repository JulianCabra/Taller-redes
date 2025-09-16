## Taller 15 de septiembre
# Los puntos estan desarrollados en las carpetas con su nombre, organizados con las imagenes y docker-compose (punto 2 y 3)


# Dando respuesta a la pregunta "¿Qué red es mas practica para proyectos distribuidos? ¿Por qué?"
A partir de lo experimentado y aprendido durante el taller, se concluye que resulta más práctico utilizar user-defined network, ya que facilita la conexión entre servicios al permitir referenciarlos directamente por el nombre del servicio, en lugar de depender de direcciones IP que pueden cambiar al reiniciar los contenedores o el sistema. Esto hace que la comunicación entre servicios sea más sencilla.
