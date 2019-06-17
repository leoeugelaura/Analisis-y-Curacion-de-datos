# Analisis-y-Curacion-de-datos
Pasos para ejecutar la notebook
1. Crear el directorio "AnalisisYCuracion" sobre la carpeta "home"
  Para ello ejecutar los siguientes comandos sobre la terminal de linux:
  a. cd /home
  b. sudo mkdir AnalisisYCuracion

2. Bajar la notebook de github sobre el directorio creado
  Seguir los siguiente pasos sobe github
  a. Hacer click en el boton "Clone or download"
  b. Seleccionar la opción "Download zip"
  c. El archivo zip se bajara en la carpetas "Descargas". Debemos moverlo a la carpeta creada en el punto 1
    Utilizar el siguiente comando estando situados en la carpeta "Descargas"
    sudo mv Analisis-y-Curacion-de-datos-master.zip /home/AnalisisYCuracion
  d. Luego descomprimir el archivo 
   unzip Analisis-y-Curacion-de-datos-master.zip

3. Para finalizar, estando situados sobre la carpeta creada en el punto 1 ejecutamos el siguiente comando
  a. jupyter notebook
