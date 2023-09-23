<p align="center">
  <img src="https://i.postimg.cc/Ssj5rHRZ/Banner-01-medio.png">
</p>

## Tabla de Contenidos
1. [Información General](#información-general)
2. [Gráfica del Datafactory](#gráfica-del-datafactory)
3. [Servicios Azure Utilizados](#servicios-azure-utilizados)
4. [Documentación tecnica](#documentación-técnica)
   
### Información General
Este proceso ETL, Integra la data proveniente de On-premise, en formato .CSV, la registra en la Base de Datos Azure, Obtiene data cuyo origen es el Datalake

| Ambiente | Nombre del Datafactory | Rama |
|----------|----------|----------|
| Desarrollo | dafaceddeu2d01 | developer|
| Calidad| dafaceddeu2c01 | release|
| Producción | dafaceddeu2p01 |master|

### Gráfica del Datafactory

![Grafica del Datafactory](https://i.ibb.co/ctXwBjc/Captura-de-pantalla-2023-09-22-162727.png)

### Servicios Azure utilizados
En esste proyecto se utilizaron los siguientes servicios Azure:

1. Azure Storage Account (stacceddeu2p01 y stacceddeu2p02)
   Almacenamiento en blob Storage.
3. Azure SQL Database.(sqldbceddeu2p01)
   Almaceenamiento SQL.
5. Azure Automation.(azaaceddeu2p01)
   Proceso de automatizacion de procesos.
7. Azure Logic App.(azlaceddeu2p01)
   Para la ejecucion de envio de Correos.
9. Azure KeyVault.(azkvceddeu2d01)
    Almacenamiento seguro de Keys.
   
### Documentación técnica

La documentación se encuentra disponible en :

https://pacificocia.sharepoint.com/:f:/r/sites/LosMorochucos/Shared%20Documents/General/Documentacion%20del%20Squad/Documentacion_ProyectoADAF/Cloud?csf=1&web=1&e=Kr5ovJ
