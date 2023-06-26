# DJANGO-ECOMMERCE
Proyecto Ecommerce con DJANGO y Paytm (método de pago)

1. Tener instalado Django
pip install django

2. Crear proyecto de Django (Crea una estructura de directorios y archivos iniciales para el proyecto) en este con el nombre "ecommerce"
django-admin startproject ecommerce

3. Crear la aplicación ecommerceapp
python manage.py startapp ecommerceapp

4. Crear también el auth para manejar la autenticación y autorización de los usuarios.
python manage.py startapp auth

5. Crear el superusuario en la base de datos Django
python manage.py createsuperuser

6. Instalar el six para poder usar las versiones tanto python 2 como 3
pip install six

7. Instalar el Pillow
pip install Pillow

8. Ya por último para inicializar el proyecto
python manage.py runserver
