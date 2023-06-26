# DJANGO-ECOMMERCE
Proyecto Ecommerce con DJANGO y Paytm (método de pago)
## Configuración inicial
1. Tener instalado Django:
```shell 
pip install django
```
2. Crear proyecto de Django (Crea una estructura de directorios y archivos iniciales para el proyecto) en este con el nombre "ecommerce":
 ```shell   
django-admin startproject ecommerce
```
3. Crear la aplicación ecommerceapp:
 ```shell     
python manage.py startapp ecommerceapp
```
4. Crear también el auth para manejar la autenticación y autorización de los usuarios.
 ```shell  
python manage.py startapp auth
```

## Creació del superusuario
Para crear el superusuario en la base de datos Django, utiliza el siguiente comando:
 ```shell  
python manage.py createsuperuser
```

## Instalación de dependencias
Asegúrate de tener las siguientes dependencias instaladas:
- Six (biblioteca de compatibilidad entre Python 2 y 3):
 ```shell  
pip install six
```
- Pillow (biblioteca para el manejo de imágenes en Django):
 ```shell  
pip install Pillow
```

## Ejecución del proyecto
Para inicializar el proyecto, ejecuta el siguiente comando:
 ```shell  
python manage.py runserver
```
