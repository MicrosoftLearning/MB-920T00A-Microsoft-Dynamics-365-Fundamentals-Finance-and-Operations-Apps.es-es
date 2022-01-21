---
lab:
    title: 'Laboratorio 8: Laboratorio de proyecto final de Dynamics 365 Supply Chain Management'
    module: 'Módulo 1: Aprender los fundamentos de Microsoft Dynamics 365 Supply Chain Management'
---

## Laboratorio 8: Laboratorio de proyecto final de Dynamics 365 Supply Chain Management

## Objetivo

En este laboratorio, explorará la creación de productos y el mantenimiento de los precios También revisará los procesos empresariales clave de las cadenas de suministro, como la gestión de inventarios, adquisiciones y abastecimiento.

## Configuración del laboratorio

- **Tiempo estimado**: 45 minutos 

## Ejercicio 1: Explorar la administración de productos

### Crear un producto

En Contoso Entertainment System USA (USMF), debe crear un nuevo artículo para un recinto de altavoces recién configurado que se comprará a los proveedores.

1. En la página de inicio, en la esquina superior derecha, compruebe que se ha seleccionado la empresa **USMF**.

1. De no ser así, seleccione la empresa enumerada actualmente y cambie la empresa a **USMF**.

1. En el panel de navegación, seleccione **Módulos** > **Gestión de información de productos** > **Productos** > **Productos liberados**.

1. En la página Detalles de producto liberado, en el panel de acciones, seleccione **+ Nuevo**.

1. En el panel **Nuevo producto liberado**, en el menú **Tipo de producto**, compruebe que **Artículo** está seleccionado.

1. En el menú **Subtipo de producto**, compruebe que **Producto** está seleccionado.

1. Seleccione el menú **Grupo de dimensiones de seguimiento** y luego **Ninguno**.

1. En **IDENTIFICACIÓN**, en el cuadro **Número de producto**, escriba **GTL201**.

1. En el cuadro **Nombre de producto**, escriba **Recinto de altavoz**.

1. En **FISCALIDAD DE VENTAS**, seleccione el menú **Grupo de impuestos de artículos** y luego **TODOS**.

1. En **FISCALIDAD DE COMPRAS**, seleccione el menú **Grupo de impuestos de artículos** y luego **TODOS**.

1. En **PRECIOS**, en el cuadro **Precio de compra**, escriba **30,00**.

1. En el cuadro **Precio de venta**, escriba **30,00**.

1. En **GRUPOS DE REFERENCIA**, seleccione el menú **Grupo de modelos de artículo** y luego **FIFO (el primero en entrar; el primero en salir)**.

1. Seleccione el menú **Grupo de artículo** y luego **Audio para automóvil**.

1. Seleccione el menú **Grupo de dimensiones de almacenamiento** y luego **SiteWH**.

1. En **UNIDADES DE MEDIDAS**, compruebe que se establezcan los siguientes valores:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Unidad de inventario| ud.|
    | Unidad de compra| ud.|
    | Unidad de ventas| ud.|
    | Unidad de BOM| ud.|

1. Seleccione **Aceptar**.

1. Para asegurarse de que el producto está finalizado, en el panel de acciones, seleccione **Producto** y luego, en **Mantener**, seleccione **Validar**.

1. Compruebe que se le presenta el banner de información que confirma que todos los valores de campo obligatorios se validaron.

1. Cierre todas las páginas y vuelva a la página de inicio.

## Ejercicio 2: Explorar la gestión de almacenes

### Crear un almacén

1. En el panel de navegación, seleccione **Módulos** > **Gestión de inventarios** > **Configuración** > **Desglose del inventario** > **Almacenes**.

1. En la página Almacenes, en el panel de acciones, seleccione **Nuevo**.

1. En el cuadro **Almacén**, escriba **150**.

1. En el cuadro **Nombre**, escriba **Almacén de avanzada**.

1. Seleccione el menú **Sitio** y, después, **1 Producción de altavoces casera**.

1. Seleccione la ficha desplegable **Nombres de ubicación**.

1. Las opciones de esta sección definen el formato predeterminado para los nombres de ubicación.

1. Establezca las opciones **Incluir pasillo** e **Incluir estantería** en **Sí**.

1. Establezca la opción **Incluir estante** en **Sí**.

1. En el cuadro **Formato**, para el estante, especifique **-##**.

1. En el panel de acciones, seleccione **Almacén**.

1. En **Mantener**, seleccione **Asistente para ubicación**.

1. En la página principal, revise la información y, después, en la esquina inferior derecha, seleccione **Siguiente**.

1. Desmarque las casillas **Muelles de llegada** y **Ubicaciones de almacenaje**.

1. Seleccione **Siguiente** y revise la información.

1. Continúe hacia cada página y, cuando termine, seleccione **Finalizar**.

1. Cierre la página y vuelva a la página de inicio.

### Crear un acuerdo comercial para el precio de venta

1. En el panel de navegación, seleccione **Módulos** > **Gestión de información de productos** > **Productos** > **Productos liberados**.

1. En la página Detalles de producto liberado, busque el número de producto **GTL201**.

1. A la izquierda de **GTL201**, seleccione el cuadro **Seleccionar o anular selección de fila**.

1. En el panel de acciones, seleccione **Vender** y luego, en **ACUERDOS COMERCIALES**, seleccione **Crear acuerdos comerciales**.

1. En el panel de acciones, seleccione **+Nuevo**.

1. Seleccione la columna **Nombre**, el menú y luego **S_Price**.

1. En el panel de acciones, seleccione **Líneas**.

1. En las líneas de diario, en la página de acuerdo comercial, en la columna **Relación de artículo**, seleccione el menú y luego seleccione **GTL201**.

1. Este es el número de artículo del producto que creó.

1. En la columna **Almacén**, seleccione el menú y luego **150**.

1. Es posible que deba desplazarse hacia la derecha para ver la columna.

1. En la columna **Importe en divisa**, en el cuadro, escriba **100,00**.

1. En la sección Detalles, en el cuadro **Fecha desde**, escriba la primera fecha del año actual.

1. En el panel de acciones, seleccione **Validar** > **Validar todas las líneas.**

1. En el panel **Registro del diario de precios/descuentos**, seleccione **Aceptar**.

1. Compruebe que no haya errores.

1. En el panel de acciones seleccione **Registrar**.

1. En el panel **Registro del diario de precios/descuentos**, seleccione **Aceptar**.

1. Compruebe que la operación se completa.

1. Cierre la página.

1. En la página Detalles de producto liberado, en el panel de acciones, en **Vender** > **ACUERDOS COMERCIALES,** seleccione **Ver acuerdos comerciales**.

1. El acuerdo comercial debería estar registrado. Revise la línea para ver la información de precios.

1. Cierre las páginas y vuelva a la página de inicio.

## Ejercicio 3: Explorar la administración de la producción

### Crear un pedido de producción para un producto

1. En el panel de navegación, seleccione **Módulos** > **Control de producción** > **Pedidos de producción** > **Todos los pedidos de producción**.

1. En el panel de acciones, seleccione **Nuevo pedido de producción**.

1. En el panel **Crear pedido de producción**, en **IDENTIFICACIÓN**, en el cuadro **Número de artículo**, escriba **D0004** y seleccione el artículo identificado.

1. En **PRODUCCIÓN**, en el cuadro **Entrega**, seleccione una fecha un mes después de la fecha de hoy.

1. La fecha de entrega indica cuándo debe finalizar el pedido de producción para entregar a tiempo. Esta fecha se puede usar en el proceso de programación. Por ejemplo, puede programar el pedido hacia atrás desde la fecha de entrega.

1. En el cuadro **Cantidad**, escriba **30**

1. Seleccione **Crear**.

1. Cierre todas las páginas y vuelva a la página de inicio.

## Ejercicio 4: Explorar la gestión de inventarios

### Crear un diario de recuento con el producto para el almacén creado

1. En el panel de navegación, seleccione **Módulos** > **Gestión de inventarios** > **Entradas de diario** > **Recuento de artículos > Recuento**.

1. En el panel de acciones, seleccione **+Nuevo**.

1. En el panel **Crear inventario de diario**, en **Recuento por**, seleccione el conmutador de alternancia **Almacén** para establecerlo en **Sí**.

1. Seleccione **Aceptar**.

1. En la página del diario de recuento de inventario, en la ficha desplegable **Detalles de encabezado de diario**, en **Líneas de diario** en la barra de herramientas, seleccione **+Nuevo**.

1. En la columna **Número de artículo**, seleccione el menú y luego **GTL201**.

1. En la columna **Almacén**, seleccione el menú y luego **150**.

1. En el cuadro **Contado**, escriba **100,00**.

1. Esto especificará el número de artículos guardados en el almacén para este producto.

1. En el panel de acciones, seleccione **Validar**.

1. En el panel **Comprobar diario**, seleccione **Aceptar**.

1. En el panel de acciones, seleccione **Registrar**.

1. En el panel **Registrar diario**, seleccione **Aceptar**.

1. Cierre todas las páginas y vuelva a la página de inicio.

### Comprobar el inventario disponible para el producto

1. En el panel de navegación, seleccione **Módulos** > **Gestión de inventarios** > **Consultas e informes** > **Lista disponible**.

1. En el panel de acciones, seleccione **Dimensiones**.

1. En el panel **Visualización de la dimensión**, en **DIMENSIONES DE ALMACENAMIENTO**, seleccione las casillas **Sitio** y **Almacén** y luego **Aceptar**.

1. En el panel **Filtros**, seleccione **Aplicar**.

1. Localice y revise el inventario disponible de **GTL201**.

1. Cierre todas las páginas y vuelva a la página de inicio.

## Ejercicio 5: Explorar la adquisición y el abastecimiento

### Crear un pedido de compra con un producto

1. En el panel de navegación, seleccione **Módulos** > **Adquisición y abastecimiento** > **Pedidos de compra** > **Todos los pedidos de compra**.

1. En la página Todos los pedidos de compra, en el panel de acciones, seleccione **+ Nuevo**.

1. En el panel **Crear pedido de compra**, seleccione el menú **Cuenta del proveedor** y, después, seleccione **US-101**.

1. Al seleccionar un proveedor, los detalles del registro del proveedor, como la dirección, la cuenta de la factura, y las condiciones y el modo de entrega, se copiarán como valores predeterminados en el encabezado del pedido. Puede cambiar estos valores en cualquier momento.

1. En la sección **General**, en **DIMENSIONES DE ALMACENAMIENTO**, seleccione el menú **Sitio** y, después, **1 Producción de altavoces casera**.

1. En **FECHAS**, seleccione una **Fecha de entrega** para una semana a partir de la fecha de hoy.

1. Seleccione **Administración**.

1. Seleccione el menú **Solicitante** y luego **Lars Giusti** para especificar quien hace el pedido.

1. En el panel **Crear pedido de compra**, seleccione **Aceptar**.

1. En la barra de herramientas, seleccione **Línea de pedido de compra**.

1. Debajo de **MOSTRAR**, seleccione **Dimensiones**.

1. En el panel **Presentación de dimensiones**, en **DIMENSIONES DEL PRODUCTO**, seleccione el cuadro **Color**.

1. Seleccione **Aceptar**.

1. En la columna **Número de artículo**, seleccione el menú y luego **T0005**.

1. En la columna **Número de variante**, seleccione el menú y luego uno de los colores.

1. En el cuadro **Cantidad**, escriba **15**.

1. Debajo de las **Líneas de pedido de compra**, en la parte inferior de la página, seleccione la ficha desplegable **Detalles de línea**.

1. Esta pestaña puede estar ya expandida.

1. Seleccione la pestaña **Entrega** y, en el cuadro **Fecha de entrega**, utilice la fecha asignada actualmente o especifique una fecha futura.  
    Se puede asignar una fecha de entrega única a cada línea de pedido. La fecha se hereda del campo del encabezado del pedido de compra, pero puede cambiarlo.

1. Anote su número de pedido de compra. Lo necesitará más adelante.

1. En el panel de acciones, seleccione **Guardar**.

1. Cierre la página Línea de pedido de compra.

1. En la página Todos los pedidos de compra, use la función **Filtro** y busque su nuevo pedido de compra.

1. Cuando termine, cierre la página Todos los pedidos de compra y vuelva a la página de inicio.
