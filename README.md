Aplicacion que permite mandar mails con asunto y contenido, además de almacenar dichos mails en una base de datos.
La aplicación tiene también un buscador que permite identificar palabras dentro de los contenidos de los mails y mostrar dichos mails como resultado, descartando aquellos mails que no cumplen con los contenidos buscados.
A tener en cuenta que no se encuentra subida la carpeta de venv (entorno virtual) al repositorio ya que es demasiado pesada, para poder inicializar el programa se necesita desde terminal hacer los siguientes pasos: pararse en la carpeta con los archivos y: py -3 -m venv venv, damos enter venv\Scripts\activate, damos enter pip install Flask, damos enter pip3 install mysql-connector-python, damos enter set FLASK_APP=todo, damos enter set FLASK_ENV=development, damos enter set FLASK_DATABASE_HOST=localhost, damos enter set FLASK_DATABASE_PASSWORD=contraseña, damos enter set FLASK_DATABASE_USER=nombre de usuario, damos enter set FLASK_DATABASE=nombre base de datos, damos enter flask init-db, damos enter flask run, damos enter