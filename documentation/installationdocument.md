## Installation Document
### Crud Flask Api Rest with PyMongo

1. Instalar entorno virtual    
   
   ~~~
   pip install virtualenv
   ~~~

2. Crear el entorno virtual (venv es el nombre del entorno, sin embargo el nombre es opcional), se indica además que el entorno correrá con python3

    ~~~
    virtualenv -p python3 venv
    ~~~

3. Iniciar el entorno virtual

    ~~~
    source venv/bin/activate
    ~~~

4.  Instalar las dependencias    

    ~~~
    pip install -r requirements.txt
    ~~~

5. Inicializar la conexión a la base de datos

    ~~~
    sudo mongod --dbpath flask/ --port 27018
    ~~~