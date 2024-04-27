# PASOS 
PROYECTO DE SISTEMAS INTELIGENTES_ EP1



# Requisitos
Para llevar a cabo este proceso, se deb de de tener lo siguiente:

ROS Melodic: La versión específica de ROS que se requiere para este proyecto.
Python 3: Asegúrate de tener Python 3 instalado en tu sistema. 
Git: Se utilizará para clonar el repositorio donde se encuentra el código.

# Configuración del entorno
Aquí están los pasos que necesitas seguir para configurar el entorno correctamente: 
Clonar el repositorio Primero, clona el repositorio en tu espacio de trabajo de ROS.
Abre una terminal y ejecuta los siguientes comandos: cd Gabriela_Sánchez/src git clone https://github.com/gabriela-py/Examen_unida.git 
cd .. catkin_make

Ejecución del script A continuación, estos son los pasos para ejecutar el script:

# Iniciar el ROS Core: roscore
Ejecutar el nodo Turtlesim: En otra terminal, inicia el simulador turtle: rosrun turtlesim turtlesim_node
Correr el script turtle_movement.py: En una nueva terminal, navega al directorio donde se encuentra el script: cd Gabriela_Sánchez/src/turtle_unida/src python turtle_movement.py
Con estos pasos, la tortuga en el simulador ROS debería comenzar a moverse en un movimiento circular constante.
