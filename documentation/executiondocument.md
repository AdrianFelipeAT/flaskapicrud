## Execution Document
### Crud Flask Api Rest with PyMongo

1. Iniciar el entorno virtual

    ~~~
    source venv/bin/activate
    ~~~

2.  Instalar las dependencias    

    ~~~
    pip install -r requirements.txt
    ~~~

3.  Correr servidor local    

    ~~~
    python3 src/app.py
    ~~~

4. Inicializar la conexión a la base de datos

    ~~~
    sudo mongod --dbpath flask/ --port 27018
    ~~~

5.  Acceder al navegador    

    [http://127.0.0.1:5000/](http://127.0.0.1:5000/)