# CIAT_Test-BI


## Pentaho

1. La DB proporcionada en la prueba realizada la llame **ciat**, los datos para acceder:
**Usuario**: *root*
**Contraseña**: *toortoor*

2. La DB a la que lleve los datos la llame **bi_ciat**, los datos acceso son los mismos que el punto anterior.

3. Las conexiones a las bases de datos **ciat** y **bi_ciat** las llame **dw** y **bi** respectivamente.

Al correr los procesos ETL, lo primero que ocurre es la creación de las tablas dentro de **bi_ciat**.
Me ha pasado que para poder correr los procesos es necesario abrirlos y verificar que la conexión a la base datos es correcta, aunque al estar todos dentro de un mismo trabajo con hacerlo en un solo ETL, los actualiza todos.


PD: La tabla de hechos no esta terminada, no fue por falta tiempo, por lo anterior la imagen de la primera carpeta no esta disponible. 
