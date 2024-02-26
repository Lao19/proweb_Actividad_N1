# proweb_Actividad_N1
Primera evaluación de la materia Programación Web

## Pasos para la realizacion de la evaluacion

### 1. Creamos el repositorio en Github, indicandole su nombre, que este sea publico y que tenga su propio README.md

De la forma en la que se ve en la imagen 
![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/248b2487-f1c2-4827-ad7a-0a8254e1bd89)


### 2. Agregamos como colaborador al usuario "wilfredvasquez"

Esta actividad se puede realizar de dos maneras, por la terminal de Git Bash, o manualmente desde el repositorio en Github
Primero, se hara desde la terminal de Git Bash:

#### Pasos

a. Ingresamos a los ajustes del repositorio, especificamente al apartado de colaboradores

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/4ada7a48-b2c7-40ac-a567-ddab4c163f84)

b. Se ingresa el usuario del colaborador y se envia la solicitud para que se una al repositorio

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/54f95041-2f43-48ac-b6e1-4ed6a705d0c9)

Como se ve aqui, esta a la espera de confirmacion

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/5baa1011-7c07-449e-b54e-74b2c82ed7f1)



### 3. Se crean las branches staging y develop, puesto que la branch main, es nuestra rama principal del repositorio, para ello se siguen estos pasos:

#### Desde la terminal de Git Bash:

a. Se comienza clonando el repositorio remoto en nuestro equipo local con el comando git clone https://github.com/Lao19/proweb_Actividad_N1.git

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/4537f2be-1696-44a6-84c9-dd9b0e092f4b)

b. Se accede al repositorio local y se verifica que estemos parados en la rama main con el comando git branch

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/e351dc93-4c4c-45c2-b4f1-084700d94527)

c. Se crean las nuevas ramas llamadas staging y develop, con los comandos "git checkout -b staging" y "git checkout -b develop", y con 
git branch, se verifican

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/727fc9d7-4339-4989-879f-f410fb134c1f)

d. Ahora, se deben subir las ramas del repositorio local al remoto:
Primero, utilizando el comando "git add ." (parados en la rama la cual se quiere subir) se agregan todos los cambios realizados, luego se utiliza el comando "git commit -m "comentario"" 
para dejar un comentario sobre cual es el cambio que se esta realizando. Por ultimo, se utiliza el comando "git push origin nombre_de_la_rama" para de esta forma, subir la rama con 
todos sus cambios actualizados a nuestro repositorio remoto.

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/b3105105-70a3-4c86-aaed-c8323cca0a39)

Se sigue este mismo procedimiento para la rama staging (cambiando a ella con el comando "git checkout nombre_de_la_rama")


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Link a la pagina web: https://lao19.github.io/proweb_Actividad_N1/
![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/ed16e7f0-cbd7-4ade-abb3-222fa69b19b0)

Viendo de esta forma, todas las branches en el repositorio remoto

![image](https://github.com/Lao19/proweb_Actividad_N1/assets/126922271/aceea4cb-6ccb-4ced-96c4-0161ce60e069)

