"# DjangoSocialApp" 
Esta es una aplicacion similar a tuiter, se pueden crear usuarios, se pueden hacer publicaciones, se pueden borrar las publicaciones del usuario en turno
se pueden editar los perfiles, agregar imagenes de perfil, no se puede dar like ni hacer comentarios.

Debido al tiempo, cuenta aun con algunos errores, pero el potencial de proyecto para la aplicacion de la analitica es muy amplio, sugerir personas a quienes seguir podria ser un gran sistema de recomendacion.

Para funcionamiento local sigue los siguientes pasos

1-Clona el repositorio o descargalo como zip.


2-Crea un ambiente virtual
python -m venv socialenv

3-Instala las dependencias/librerias en requirements.txt
pip install -r requirements.txt

4-Ejecuta las migraciones.
python manage.py makemigrations python manage.py migrate

5-Crea un superusuario.
python manage.py createsuperuser

6-Corre el servidor.
python manage.py runserver

7- Abre localhost:8000

EL CODIGO FINAL SE ENCUENTRA EN EL BRANCH: FINAL_FILES

---------------------------------------------------------------------------
Aqui sera agregado un link para probar en clase:
