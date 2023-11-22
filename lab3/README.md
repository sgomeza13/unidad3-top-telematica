# Laboratorio 3

## Paso a paso:

1. Creacion de la base de datos:
   1. Desde AWS GLUE:
   ![Alt text](image.png)
    2. Desde Athena:
    ![Alt text](image-1.png)
    3. Desde Hive:
        * ![Alt text](image-2.png)
        * ![Alt text](image-3.png)
        * ![Alt text](image-4.png)
        * ![Alt text](image-5.png)
2. Wordcount en Hive
   1. ![Alt text](image-6.png)
   2. ![Alt text](image-7.png)
   3. ![Alt text](image-8.png)

3.  IMPLEMENTACIÓN DE UN DATA WAREHOUSE CON EMR y HIVE
    1. Crear redshift cluster
        ![Alt text](image-9.png)
        ![Alt text](image-10.png)
    2. Correr los querys de tickit
        ![Alt text](image-11.png)
        ![Alt text](image-12.png)
    3. Crear un rol IAM para Amazon Redshift
    ![Alt text](image-13.png)
    ![Alt text](image-14.png)
    ![Alt text](image-15.png)
    ![Alt text](image-16.png)
    4. Crear una base de datos externa en s3
    ![Alt text](image-17.png)
    ![Alt text](image-18.png)
    5. Cargar datos en tabla event2
    ![Alt text](image-19.png)
    ![Alt text](image-20.png)
