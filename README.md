> [!IMPORTANT]  
> Antes de cualquier cambio, revisar [documentación oficial](https://github.com/Smile-SA/gdpr-dump/wiki).

### Extends disponibles

**CleanCustomers**: Trunca todas las tablas de Customers

**CleanOrders**: Trunca todas las tablas de Sales

### ¿Cómo usar los Extends?

Para usar los extends basta solo con requerirlos al principio del yaml. Ej.:

```
---
extends:
- 'magento2'
- 'extends/CleanCustomers.yaml'
- 'extends/CleanOrders.yaml'
```

Se puede extender todos los yaml's que deseen