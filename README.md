# Fase 1: Odo Clientes y ERP
a. Haremos un repaso de que tenemos instalado que piden el taller: 
**Aplicaciones (Apps). Inventario (Inventory) y Facturación (Invoicing).**

b. En el Visual Code creamos un archivo de datos sintéticos (Mock Data) en formato
CSV para poder posteriormente importarlo a odo con su herramienta de importación.

| Nombre | Correo electrónico | Teléfono | Ciudad | País | ¿Es una compañía? |
|--------|--------------------|----------|--------|------|-------------------|
| Tech Solutions Ibérica | info@techsolutions.es | +34 611 222 333 | Sevilla | España | True |
| María Fernández | maria.fernandez@ejemplo.com | +34 644 555 666 | Madrid | España | False |
| Distribuciones del Sur | ventas@delsur.es | +34 677 888 999 | Málaga | España | True |
| Carlos Ruiz | cruiz.dev@ejemplo.com | +34 699 111 222 | Valencia | España | False |
| Global Logistics S.L. | logistica@global.es | +34 622 333 444 | Barcelona | España | True |
| Laura Gómez | laura.gomez@ejemplo.com | +34 655 444 333 | Bilbao | España | False |
| Sistemas Avanzados | contacto@sistemas.es | +34 688 777 666 | Zaragoza | España | True |
| Pedro Sánchez | psanchez@ejemplo.com | +34 612 345 678 | Murcia | España | False |
| Innovaciones Web | dev@innovaciones.es | +34 698 765 432 | Granada | España | True |
| Elena Torres | etorres.design@ejemplo.com | +34 633 222 111 | Alicante | España | False |

c. Para realizar en la importación del archivo CSV entramos a odo y vamos a **Ventas > Pedidos > Clientes**, dentro le daremos a importar y subimos el archivo, 
luego se Pulsa el botón **"Test" (para validar que el tipo de dato coincide con la base de datos)** y si funciona saldra el boton de importar subiendo todos los datos	

d. Luego crearemos un presupuesto con un usuario comercial, y crearemos/añadiremos un producto que se pueda almacenar, 
cuando lo confirmamos pasará a estado de para poder entregarlo y tendremos que pasar a la cuenta de administrador para poder validar y enviar el producto

e. Una vez el producto haya sido validado y enviado volveremos al presupuesto y ahora nos saldra el boton 
de **Crear Factura**, dentro seguiremos la política de odo y la enviaremos como **"Factura normal"** confirmamos y enviamos, y terminaremos la factura

<img width="1858" height="715" alt="image" src="https://github.com/user-attachments/assets/28562af9-07fa-4655-8ec3-60c44b5fdc94" />

# Fase 2: Informes

a. Nos piden generarle que los PDF, lleve puestos una marca roja para la proteccion de datos, para ellos modifcarmeos la plantilla XML, para hacer esto Odoo usa un sistema de **"Herencia de vistas"** basado en XPath. Con el Modo Desarrollador
iremos a **Ajustes > Técnico > Interfaz de Usuario > Vistas (Views).**

b. 
