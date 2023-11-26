# Blog en Django alumno: thomas paniagua

Este es un simple blog desarrollado utilizando Django, un marco de desarrollo web en Python. Este proyecto permite a los usuarios crear, editar y eliminar publicaciones de blog, así como comentar en ellas.

## Requisitos

Asegúrate de tener instalado Python y pip en tu sistema. Luego, instala las dependencias del proyecto ejecutando:

```bash
pip install -r requirements.txt


git clone https://github.com/tu-usuario/blog-django.git
cd blog-django


python -m venv venv
source venv/bin/activate  # En sistemas basados en Unix/Linux
# O
venv\Scripts\activate  # En sistemas basados en Windows


python manage.py migrate


python manage.py createsuperuser


python manage.py runserver
