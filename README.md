# django_test

Configuración del entorno (haciendo uso de virtualenv):

- Tener Python v3.4.3 y PostgreSQL instalados.
- Crear una BD en PostgreSQL, llamada "db_sigos". Nota: Se debe usar el puerto 5432, usuario: postgres, pw: 1234 y host: localhost; o sino, se cambian esos campos directamente en el código del proyecto.
- Instalar virtualenv (pip install virtualenv).
- Crear un entorno virtual de Python (virtualenv NombreDeEntornoVirtual).
- Accesar al entorno virtual (source NombreDeEntornoVirtual/Scripts/activate).
- Clonar este repositorio (git clone https://github.com/araymoises/django_test.git NombreDeServidor). Nota: Puede clonarse dento de la carpeta del virtualenv, para una mayor organización.
- Ingresar al directorio del proyecto (cd NombreDeServidor).
- Instalar paquetes de Python (pip install -r requirements.txt).
- Crear los archivos de migración de la BD (./manage.py makemigrations).
- Ejecutar archivos de migración de la BD (./manage.py migrate).
- Ejecutar el servidor (./manage.py runserver).
- Accesar al puerto 8000, desde el navegador.
