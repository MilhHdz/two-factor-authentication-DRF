# README.MD
Este proyecto esta hecho con **Django Rest Framework** usando **Django-OTP** para la autenticacion de doble factor.

## Instale lo siguiente para un correcto funcionamiento.
```bash
pip3 virtualenv

virtualenv nombre_de_entorno_virtual
```

En linux o Mac

```bash
source nombre_de_entorno_virtual/bin/activate

pip3 install -r requirements.txt
```

### Guarde sus variables de entorno
Puede crear un archivo variable.sh donde almacene las variables de entono

**export ENV_SECRET_KEY="TU-LLAVE-SECRETA"**

ejecuta el siguiente comando
```bash
. ./variable.sh
```

Terminando la configuracion ejecute lo siguiente

```bash
python3 manage.py makemigrations
python3 manage.py migration

python3 manage.py createsuperuser

python3 manage.py runserver
```