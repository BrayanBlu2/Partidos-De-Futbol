Este es un sitio web hecho con el framework de Flask y está implementado con la BBDD de pgAdmin para el logueo de usuarios.
Esta es un sitio web en donde puedes ver las temporadas de los partidos de fútbol, la web tiene implementada una api de donde extraemos los dados, por lo tanto, los datos son rales y se actualizan.

Falta crear el entorno de Flask para poder ejecutarlo, no lo he subido, ya que, es un archivo bastante pesado. El entorno se crea de la siguiente manera:
Estando en tu carpeta dentro de el editor de código VSCode abrimos una termina cmd y ahí ponemos los siguientes comandos:
python -m venv nombreEntorno    esto crea la carpeta del entorno.
nombreEntorno\Scripts\activate    esto activa nuestro entorno.

una vez activo el entorno hay que instalar distintas librerías de flask como por ejemplo flask-sqlalchemy, flask. También psycopg2.
