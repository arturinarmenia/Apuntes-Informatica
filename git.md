# Resumen de Git
## Repositorio
¿Como crear un repositorio?
para crear un nuevo repositorio tenemos que usar el comando 'git init'
### Nota
en caso de tener ya creado un repositorio usaremos el comando 'git clone https://github.com/USUARIO/REPOSITORIO'
## add y commit
son comandos de git, empezemos con el add, este comando es para añadir un archivo a git, es decir para que git sepa que ese archivo existe, para usarlo 'git add NOMBREDELARCHIVO'
ahora vamos con el commit, el commit es para guardar los cambios realizados, y los guarda con un mensaje, se escribe asi 'git commit -a -u "MENSAJE"' en el mensaje pondremos nombre al commit para posteriormente reconocerlo
## Push
el comando push es para subir el ultimo commit realizado a github o bitbucket, se usa de la siguiente forma 'git push -u origin master' la parte de origin master es el servidor, es decir es el sitio donde lo va a subir.
### Nota
para hacer este comando tienes que haber le asignado un servidor, para hacerlo tienes usar el comando 'git remote add origin SERVIDOR' el servidor puede ser de github o bitbucket, ejemplo https://github.com
#### Nota 2
el nombre del servidor no tiene por que ser origin, se puede llamar como uno quiera pero se suele utilizar origin
