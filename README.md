# Hola, soy Daniel Pérez

VBA · SQL Server · C# · PHP · Python — Mollet del Vallès (Barcelona)

Llevo programando desde 2007. Empecé casi por necesidad: hacía falta una herramienta para ubicar los productos del almacén y acabé haciéndola yo en Access. Desde entonces no he parado. Hoy soy el responsable de IT de la empresa y el único perfil técnico, así que me toca un poco de todo: desarrollo, sistemas, redes, soporte a los compañeros y a los clientes que usan mis aplicaciones, y el mantenimiento de equipos y servidores.

Este año he terminado el curso de **Programación en Python de Tokio School**, con el proyecto final aprobado. Ahora busco **prácticas en un equipo de desarrollo**: quiero trabajar con más gente, ver cómo se hacen las cosas en otros sitios y seguir aprendiendo.

---

### Proyectos

**[ERP de suministros informáticos](https://github.com/Dperez0209/erp-suministros-flask)** — Python · Flask · SQLAlchemy · MySQL

Mi proyecto final del curso de Tokio School. Una aplicación web para gestionar productos, proveedores y usuarios con roles, que avisa cuando un producto baja de su stock mínimo. Es el único proyecto con el código a la vista; el resto pertenece a la empresa.

**Servicio de facturación VeriFactu** — C# · .NET · Odoo 18 · *en desarrollo*

Con VeriFactu, las facturas tienen que llegar a Hacienda, y las nuestras salen de un ERP en Access 97 que no se puede rehacer de un día para otro. Así que he montado un servicio de Windows con cola que las lleva hasta la AEAT: Access → servicio Windows → Odoo → VeriFactu → AEAT. Por el camino respeta la numeración correlativa de cada serie y recoge la respuesta de Hacienda. Es el proyecto del que más orgulloso estoy, y el que más capas tiene.

**Implantación de Odoo 18** — Python · Odoo 18 · XML · *desde enero de 2026, ahora en pausa*

Empecé llevando la implantación como responsable interno del proyecto y enlace técnico con el proveedor externo. Por el camino, la empresa decidió hacer el desarrollo internamente y me tocó a mí, aprendiendo sobre la marcha. Hasta ahora he hecho la personalización de contactos (res.partner) y productos (product.template) con herencia de modelos y vistas, y había empezado con los permisos de los usuarios del portal web. Está en pausa hasta terminar VeriFactu, que ahora es la prioridad.

**Integración de expediciones con la central de transporte** — C# · .NET · multihilo · *en producción*

Una aplicación de escritorio conectada al web service de la red de transporte. Permite grabar expediciones a mano, arrastrando y soltando o con una importación automática cada cierto tiempo, en directo o en diferido, y también eliminarlas, reetiquetarlas y seguir su trazabilidad. Está hecha por capas, es multihilo y tiene su propio sistema de actualizaciones. Funciona desde marzo de 2026 en dos equipos de la empresa y en dos clientes (cinco puestos en total), y tengo dos clientes más confirmados.

**API de integración de pedidos** — PHP · SQL Server · MySQL · Firebase · *en producción*

Por aquí entran los pedidos: los que manda por cola el ERP de un cliente y los del portal B2B de la empresa. La API valida los datos, controla el stock, calcula el coste del envío, guarda el pedido en nuestra base de datos y avisa a las PDAs del almacén con una notificación. Funciona cada día. Creció a medida que hacía falta, y si la hiciera hoy la organizaría de otra forma.

**App de almacén para PDAs** — C# · Xamarin.Forms · SQL Server · *en producción*

La aplicación que usan los operarios en las PDAs para las salidas de mercancía: stock, ubicaciones, etiquetas y tracking. La hice yo solo, a base de buscar y probar, y sigue en producción.

**Mantenimiento y migración de sistemas heredados** — Access 97 · VBA · SQL Server · PHP · *en curso*

También mantengo código que no escribí yo. El ERP de facturación del anterior informático, en Access 97: me he leído su código (genera las series de facturas a partir de las líneas de pedido) y lo estoy pasando a Access actual con SQL Server. Las tablas de facturas ya están en tablas espejo en SQL Server, que es de donde tira el servicio de VeriFactu. Y el portal B2B, en PHP 5.6, del que estoy haciendo la versión nueva en PHP 8, esta vez bien estructurada.

**Sistema de almacén y orquestación** — Access/VBA · SQL Server · Python · *desde 2007*

Por aquí empezó todo, en 2007. Empecé haciendo una herramienta para ubicar productos y, con el tiempo, fue creciendo: control de stock, ubicaciones, validación de pedidos, importaciones e integración con el portal mediante ODBC y MySQL. Hoy es el motor logístico de la empresa y sigue evolucionando: también calcula los costes que se facturan de los pedidos que entran por la API. En 2025 le añadí la importación de pedidos por OCR para la empresa de transporte, con scripts en Python integrados con la central, que quitan mucho trabajo manual. Ahora estoy validando un motor nuevo para las tarifas de transporte.

> El código de los proyectos de la empresa no es público, pero cualquiera de ellos lo puedo explicar con detalle en una entrevista.

---

### Tecnologías

- **Principal:** VBA · Access · SQL Server · SQL
- **Uso habitual:** C# · .NET · PHP · Python
- **En proyectos concretos:** Xamarin.Forms · Flask · Odoo · Firebase · Docker
- **Herramientas:** Git · APIs REST / XML-RPC · asistentes de IA (Copilot, Claude) · Visual Studio Code · Visual Studio 2026

---

### Contacto

Si crees que puedo encajar en tu equipo, escríbeme a [pereznavarrodaniel@gmail.com](mailto:pereznavarrodaniel@gmail.com). También tienes mi web en [dperez0209.github.io](https://dperez0209.github.io).
