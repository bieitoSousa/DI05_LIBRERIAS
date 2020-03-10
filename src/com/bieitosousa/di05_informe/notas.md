
## [1] Añadir las dependencias :

#### [OPCION 1] maven
```xml
<dependency>
    <groupId>org.hibernate</groupId>
    <artifactId>hibernate-core</artifactId>
    <version>5.4.10.Final</version>
</dependency>
```

## [OPCION 2 ] librerias

[![Añadir Librerias Netbeans](.\capturasPantalla\DI05_añadirLibrerias_ireport_netbeans.png)
[![Añadir Librerias Proyecto](.\capturasPantalla\DI05_añadirLibrerias_ireport_proyect.png)

## [2] Crear un informe [NOMBREINFORME.jasper]

conectar servidor [WINDOWS] :

cd D:\Entregas\DI_DB\hsqldb-2.5.0\hsqldb
java -cp lib/hsqldb.jar org.hsqldb.Server -database.0 file:data/demo_db -dbname.0 xdb