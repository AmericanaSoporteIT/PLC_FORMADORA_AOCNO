# PLC_FORMADORA_AOCNO
Firmrware de Traducción del panel de Chino a Ingles



## PASOS PARA CONECTARSE Y CARGAR LA ACTUALIZACION DEL FIRMWARE DEL PANEL TOUCH
  
  #### REQUISITOS:
    * PC con adaptador de red Lan
    * Tener los archivos previamentea descargados: WDML.ZIP 
    * cable de red rj45 T568B

  + 1. CONFIGURAR LA IP DE LA COMPUTADORA EN EL RANGO: 192.168.2.25
  ![image](https://user-images.githubusercontent.com/76213844/112014563-a29e4e80-8af0-11eb-8dbe-62d04c20d920.png)
  
  + 2. Conectar el cable RJ45 de la Pantalla a la computadora. y hacer pruebas de conectividad.  la pantalla estara en el rango ip 192.168.2.1 - 192.168.1.7
  confirmar haciendo ping.

  + 2. Descargar los archivos y descomprimir.
 ![image](https://user-images.githubusercontent.com/76213844/112015931-de85e380-8af1-11eb-8f15-abf2fde824fc.png)
 
 al Descomprimir nos creara el siguiente estructura de directorios:
\WDML
|   file.txt
|   
├───GYJ
|   └───Pack&Go.Smart 700 IE V3
|       |   device.conf
|       |   DownLoadTask.xml
|       |   pdata.ETH0.cnk
|       |   pdata.ORIE.cnk
|       |   pdata.srt
|       |   pdata.transfer
|       |   ProjectCharacteristics.rdf
|       |  # StartTransfer.bat
|       |   
|       ├───Extern
|       |   └───VersionStore
|       |           zip.exe
|       |           
|       └───Transfer
|           |   mfc100.dll
|           |   mfc100u.dll
|           |   msvcp100.dll
|           |   msvcr100.dll
|           |   transfer.log
|           |   TransferTool.exe
|           |   TransferToolLib.dll
|           |   
|           └───3.0
|                   DeviceMapping_TP176IEV3ColorI06_V1.xml
|                   ErrorHandler.dll
|                   expat.dll
|                   ScsClient.dll
|                   StreamingFileTransfer.dll
|                   tpi2onl_dll.dll
|                   tr_smart1.dll
|                   tr_smart1_res409.dll
|                   XMLParser.dll
|                   
└───PPJ
    └───Pack&Go.Smart 700 IE V3
        |   device.conf
        |   DownLoadTask.xml
        |   dump.txt
        |   pdata.ETH0.cnk
        |   pdata.ORIE.cnk
        |   pdata.srt
        |   pdata.transfer
        |   ProjectCharacteristics.rdf
        |   StartTransfer.bat
        |   
        ├───Extern
        |   └───VersionStore
        |           zip.exe
        |           
        └───Transfer
            |   mfc100.dll
            |   mfc100u.dll
            |   msvcp100.dll
            |   msvcr100.dll
            |   transfer.log
            |   TransferTool.exe
            |   TransferToolLib.dll
            |   
            └───3.0
                    DeviceMapping_TP176IEV3ColorI06_V1.xml
                    ErrorHandler.dll
                    expat.dll
                    ScsClient.dll
                    StreamingFileTransfer.dll
                    tpi2onl_dll.dll
                    tr_smart1.dll
                    tr_smart1_res409.dll
                    XMLParser.dll




