> [!IMPORTANT]  
> Antes de cualquier cambio, revisar [documentación oficial](https://github.com/Smile-SA/gdpr-dump/wiki).

### Extends disponibles

**CleanCustomers**: Trunca todas las tablas de Customers

**CleanOrders**: Trunca todas las tablas de Sales

**CleanCompanies**: Trunca todas las tablas de Companies (Probado en SKC)

### ¿Cómo crear un Dumper para mi Proyecto?

1) Crea una cópia de **sample.yaml** con el nombre del proyecto
2) Modifica el **Nombre del Dump** y **Base de Datos**
3) Agrega todas las tablas que necesites truncar, filtrar o actualizar. Ej.: Tenés **VIU / SKC** en Projects.
4) ¡Dumpeá!

Si necesitas modificar el usuario o contraseña de la base de datos podés hacerlo desde el Yaml del proyecto tal cual asignamos el nombre de la base.