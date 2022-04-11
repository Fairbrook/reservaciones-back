# Funcionalidad para el proyecto de Ingeniería de Software __Reservaciones__

## Instalación de paquetes
El proyecto depende de múltiples librerías que están anotadas en requirements.txt y se pueden instalar con el siguiente comando
```
pip install -r requirements.txt
```

## Conección a la base de datos

Require un archivo .env en el root del proyecto con la siguiente forma

```
DB_USER=root
DB_PASSOWRD=
DB_HOST=127.0.0.1
DB_NAME=sistema_de_reservacion
```
## Importación de nuevo módulo para interactuar con imágenes
Para poder redimensionar imagenes para ser mostradas con un formato uniforme y no exceda la medida de las columnas, 
es necesario instalar el módulo PIL. Se realiza mediante el comando 
---

pip install Pillow
---