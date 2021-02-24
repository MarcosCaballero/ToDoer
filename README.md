# todoer
 
ToDolist hecho con python con el framework de flask

Inicializacion:

Para inicializar la aplicacion hay que instalar flask en el caso de que no lo tengan, pip install Flask en el caso de Windows o en el caso de MAC colocar pip3 install Flask. Seguido entramos en entorno de desarrollo venv, para entrar en entorno de desarrollo nos tenemos que colocar en la direccion de la aplicacion y colocamos
'. venv/Scripts/activate' Luego seteamos los valores por default de nuestra app, para esto vamos a tener que escribir en el terminal las siguientes lineas de código:

set FLASK_APP=todo
set FLASK_ENV=development (Esto nos sirve para que las modificaciones que le hagamos al codigo se vean impactadas en el momento y no tengamos que prender y apagar flask para poder ver los cambios)
set FLASK_DATABASE_HOST='localhost'
set FLASK_DATABASE_USER=(Usuario de su base de datos, si no funciona con un superusuario prueben con su usuario root)
set FLASK_DATABASE_PASSWORD=(password de su base de datos)
set FLASK_DATABASE=(base de datos que queramos utilizar)
En el caso de que set NO FUNCIONE utilice export si utiliza alguna terminal como gitbash o la misma terminal de MAC y repita otra vez los comandos.

Ahora lo que hacemos es correr el archivo 
Para iniciar la aplicacion hay que declararle una database en nuestro servidor y luego declarar las variables previamente dichas en el anteriior apartado, despues de esto tenemos que ejecutar python init-db y cuando nos salga 'base de datos inicializada', vamos a poder poner flask run y correr nuestro codigo.

Rutas: La ruta por defecto de flask es localhost:5000, la app los redigira a la ruta de auth/login si no es asi, autocompletenlo manualmente.

La aplicacion se encuentra en estado beta.

Proximamente tendra nuevas actualizaciones a medida que avance y adquiera mayores conocimientos.

Muchas gracias
