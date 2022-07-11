# Examen_Proyecto1_DevOps
Clúster de Docker Swarm de Pruebas
Este proyecto lo que realiza es levantar manager con nombre cesar y "n" clientes con nombre Worker+"n"
1. Primero iniciamos vagrant con el comando vagrant init
2. Luego colocamos el comando vagrant up
Esto lo que realizara es el levantado de las maquinas virtuales con los nombres indicados
3. Para poder verificar que las maquinas se iniciaron se coloca el comando Vagrant ssh cesar, esto nos levantara la maquina master con nombre cesar
Salimos de la configuracion con el comando exit
4. Inicializamos las otras maquinas que se comunican a travez del manager cesar con el comando vagrant ssh gonzalez01

