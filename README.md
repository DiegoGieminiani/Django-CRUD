# 📝 Django Task Organizer

Organizador de tareas web desarrollado con **Django**, diseñado para ayudarte a gestionar tus pendientes de forma simple y eficiente.

## ✨ Características

- Crear, ver, editar y eliminar tareas
- Registro e inicio de sesión de usuarios
- Vista detallada por tarea
- Interfaz responsiva con Bootstrap
- Autenticación de usuarios
- Protección CSRF
- Mensajes flash para feedback al usuario

## 🛠 Tecnologías utilizadas

- Python 3.9.6
- Django 4.2.21
- HTML5
- CSS3
- Bootstrap 5 (vía CDN)
- SQLite3 (base de datos)

## 📋 Prerrequisitos

- Python 3.9 o superior (pero menor a 3.10)
- pip (gestor de paquetes de Python)
- Virtualenv (opcional, pero recomendado)

## 🚀 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/DiegoGieminiani/Django-CRUD.git
cd django_crud_auth
```

2. Crea y activa un entorno virtual:
```bash
python3 -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. Instala las dependencias:
```bash
pip3 install -r requirements.txt
```

4. Configura las variables de entorno:
Crea un archivo `.env` en la raíz del proyecto con:
```
SECRET_KEY=tu_clave_secreta
DEBUG=True
```

5. Realiza las migraciones:
```bash
python3 manage.py migrate
```

6. Crea un superusuario (opcional):
```bash
python3 manage.py createsuperuser
```

7. Inicia el servidor:
```bash
python3 manage.py runserver
```

## 💻 Uso

1. Accede a http://localhost:8000 en tu navegador
2. Regístrate como nuevo usuario o inicia sesión
3. Comienza a crear y gestionar tus tareas
4. Para acceder al panel de administración, visita http://localhost:8000/admin

## 🔒 Seguridad

- Autenticación de usuarios implementada
- Protección contra CSRF
- Contraseñas hasheadas
- Variables de entorno para datos sensibles

## 🤝 Contribuir

Las contribuciones son bienvenidas. Para contribuir:

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

