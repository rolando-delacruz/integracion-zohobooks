# Integración de ZohoBooks con Efacturapty

## Crear campos personalizados 

### Campos personalizados para los clientes

Debe crear los campos personalizados para los clientes: 
- RUC 
- DV

![image](https://github.com/efacturapty/integracion-zohobooks/assets/145995728/4331ee2f-322a-43b4-a816-dc73c4eda4a5)


### Campos personalizados de facturas (Invoices) y notas de crédito (Credit Notes)

Debe crear los siguientes campos personalizados para las facturas y las notas de crédito: 
- Fecha de autorización
- Protocolo de autorización
- CUFE

Todos los campos personalizados deben crearse con tipo de dato de TEXTO y contener los mismos nombres en las etiquetas, respetando las tildes en los nombres.

![image](https://github.com/efacturapty/integracion-zohobooks/assets/145995728/09996e35-4663-4b01-a6dc-02b4c4c1fed6)


![image](https://github.com/efacturapty/integracion-zohobooks/assets/145995728/ba7a3f20-d43e-40a2-8459-b0a6df5a8177)


### Botón personalizado para autorización y anulación de facturas y notas de crédito.

Para enviar la factura a ser autorizada, debe crear un botón personalizado, el cual debe contener los scripts correspondientes que están en este repositorio, tal como se ve en la siguiente imagen.

![image](https://github.com/efacturapty/integracion-zohobooks/assets/145995728/bf6df7a6-7283-4e12-ad85-bce092953d69)

Debe reemplazar el APIKEY del script por uno generado en el apartado de integraciones con la cuenta correspondiente de efacturapty

![image](https://github.com/efacturapty/integracion-zohobooks/assets/145995728/e52dd382-52de-4ef9-8247-cf853a9a83b0)



