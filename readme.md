Primero, hay que estar seguros de que estamos en la ubicación correcta usando cd + ruta de la carpeta en el terminal.
Luego, con el git status comprobamos que el proyecto esté inicializado como un repositorio Git.
A continuación, usamos git add . para añadir los cambios del archivo al stage. Este estado indica que los cambios están preparados para ser incorporados al proyecto.
Después de este paso, hacemos un git commit para confirmar los cambios realizados. (Recomendable -m "" para describir el cambio que hemos hecho).
Ahora agregamos el repositorio remoto de GitHub como destino con el comando: git remote add origin urlrepositorio.
Para terminar, hacemos un git push para subir todos los cambios a GitHub.