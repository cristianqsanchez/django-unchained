# django web project

## instructions :memo:
Crear una aplicación web bien sea con el framework Django o flask
1. Debe tener el modelo vista template y crear por lo menos 4 paginas htlm con manejos de estilos bien sea en boostrap o css.
2. Conexión a base de datos en PostgreSQL
3. Debe tener un formulario web de registro o contáctenos en donde se permite agregar información a una tabla en PostgreSQL.
4. Debe tener acceso al administrador de Django y permitir agregar registros
5. Debe tener una pagina de consulta de usuarios en donde se muestren todos los registros de la base de datos.

## installation :genie:

### set virtual environment :truck:
```
python -m venv venv
```

### set interpreter :snake:
```
source venv/bin/activate
```

### install dependencies :package:
```
pip install -r requirements.txt
```

## setup project :wrench:

### configs :elephant:
create an `.env` file in the webapp folder based on the `.env.example` to create the connection to the postgres database

### run sever :rocket:
```
python manage.py runserver
```
