---
lab:
  title: "Laboratorio\_2: Crear un pedido de compra"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Módulo 3: Obtener información sobre los fundamentos de Microsoft Dynamics 365 Supply Chain Management

## Laboratorio 2: Crear un pedido de compra

## Configuración del laboratorio

   - **Tiempo estimado**: 15 minutos

## Objetivo

En este laboratorio, se familiarizará con la interfaz de usuario y los distintos campos disponibles en el formulario de pedido de compra. También aprenderá a crear un pedido de compra.


## Configuración del laboratorio

   - **Tiempo estimado**: 10 minutos

## Instrucciones

1. En la página de inicio de Finance and Operations, en la parte superior derecha, compruebe que esté trabajando con la empresa **USMF**. Si es necesario, seleccione la empresa y, en el menú desplegable, seleccione **USMF**.

2. En la esquina superior izquierda, seleccione el menú de hamburguesa **Expandir el panel de navegación**.

3. Seleccione **Módulos** > **Adquisiciones y abastecimiento** > **Pedidos de compra** > **Todos los pedidos de compra**.

4. En la página **Todos los pedidos de compra**, en el menú superior, seleccione **+ Nuevo**.

5. En el panel **Crear pedido de compra**, seleccione el menú desplegable **Cuenta del proveedor** y, después seleccione **US-101**.

> [!NOTE]
> Nota: Al seleccionar un proveedor, los detalles del registro del proveedor, como la dirección, la cuenta de la factura, y las condiciones y el modo de entrega, se copian como valores predeterminados en el encabezado del pedido. Puede cambiar estos valores en cualquier momento.

6.  Expanda la sección **General** si es necesario.

7. En **DIMENSIONES DE ALMACENAMIENTO**, seleccione el menú desplegable **Sitio** y revise la lista de sitios.

El campo **Sitio**, junto con el campo **Almacén**, especifican dónde deben entregarse los bienes o servicios adquiridos. La dirección predeterminada de entrega es el sitio.  Ambos campos se pueden rellenan con valores configurados para el proveedor seleccionado, o puede especificarlos manualmente.

8.  En **FECHAS**, el campo **Fecha de entrega** se utiliza para especificar cuándo deben entregarse los bienes y servicios adquiridos.

    Puede especificar una fecha de entrega única para el pedido, o las líneas de pedido individuales pueden tener fechas de entrega únicas.  Si la fecha de entrega especificada aquí no se puede cumplir para bienes o servicios específicos porque tienen plazos de entrega más largos, esas líneas se crean con una fecha de entrega posterior.

9. Expanda la sección **Administración**. El cuadro **Solicitante** se puede utilizar para especificar quién realiza el pedido.

    Esto puede ser práctico para compartir con el proveedor en caso de que necesite ponerse en contacto con esa persona. El valor se puede asignar automáticamente si la cuenta de usuario actual está asociada a un nombre de la página **Usuarios**.

10. Seleccione **Aceptar**.

Se ha creado el encabezado del pedido. Cuando trabaja con líneas de pedidos de compra, solo se muestra un resumen de la información del encabezado. Si necesita ver el resto de la información, seleccione **Encabezado**.

![Captura de pantalla que muestra el encabezado de los pedidos donde aparece el resumen de la información de estos. La palabra Encabezado aparece resaltada.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. En **Líneas de pedido de compra**, en el menú, seleccione **Línea de pedido de compra**.

![Captura de pantalla que muestra las líneas de pedidos de compra.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. Debajo de **MOSTRAR**, seleccione **Dimensiones**.

    Los productos pueden encontrarse en variantes que se diferencian por dimensiones, como color, tamaño o estilo. Los productos también se pueden configurar para usar dimensiones de almacenamiento, como sitio y almacén.  También hay dimensiones de seguimiento opcionales, como números de serie y de lote.  Para mejorar la eficiencia de la entrada de pedidos, puede agregar los campos de dimensión que normalmente utiliza directamente en la cuadrícula de pedidos.

13.  En el panel **Presentación de dimensiones**, en **DIMENSIONES DEL PRODUCTO**, seleccione el cuadro **Color**.

Opcional: Si selecciona el conmutador **Guardar configuración**, las dimensiones que ha elegido también se mostrarán en la cuadrícula de la línea de pedido la próxima vez que abra la página de pedido de compra.

14. Seleccione **Aceptar**.

15. Seleccione el menú de celda desplegable **Número de producto** y, a continuación, **T0004**.

Recuerde que también puede escribir el cuadro de filtro en lugar de desplazarse por la lista.

Las líneas de pedido se crean para productos y servicios mediante la especificación de un código de producto o como gastos si se especifica una categoría de compras.

La categoría de compras se usa para agregar líneas donde los artículos adquiridos se cargan directamente, en lugar de ir al inventario. Si necesita hacer una compra como gasto, puede hacerlo si crea una línea de pedido de compra que especifique una categoría de compras, en lugar de crear una línea con un número de artículo. Los artículos también se pueden asociar a una categoría de compras y, en este caso, la categoría de compra se muestra solo de modo informativo.

16. Seleccione el menú desplegable **Color**, revise las opciones disponibles y luego seleccione uno de los colores o combinaciones de colores.

17. Los campos **Sitio** y **Almacén** generalmente se rellenan con los valores del encabezado del pedido, pero es posible invalidar los campos si algunas líneas deben entregarse en diferentes ubicaciones.

18. En el cuadro **Cantidad**, escriba **10**.

    El campo **Cantidad** se rellena automáticamente con la cantidad de pedido mínima para el producto si está configurado, o con el valor de **1**.

19. Información adicional:

- **Unidad**: indica la unidad de medida para la cantidad pedida. Normalmente, la unidad se obtiene automáticamente de la unidad de compra en los datos maestros de producto.

- **Precio unitario**: contiene un valor de un acuerdo de compra o de un acuerdo comercial. Se puede cambiar el precio unitario en líneas de pedido individuales, por ejemplo, si se negocia un precio único con el proveedor.

- **Descuento**: representa un importe de descuento por unidad. Por tanto, este descuento reduce el precio unitario por el descuento. Este descuento suele darse automáticamente a partir de acuerdos de compra o acuerdos comerciales, pero es posible invalidar en líneas individuales si se han negociado descuentos únicos con el proveedor.

- **Porcentaje de descuento**: cuando se especifica, reduce el importe neto de la línea en consecuencia. El porcentaje de descuento suele darse automáticamente a partir de acuerdos de compra o acuerdos comerciales, pero es posible invalidar en líneas individuales si se ha negociado un porcentaje de descuento único con el proveedor.

- **Importe neto**: se calcula a partir de otros campos de la línea, incluida la cantidad, el precio unitario, el descuento y el porcentaje de descuento. Es posible cambiar el importe neto, pero los campos Precio unitario, Descuento y Porcentaje de descuento están en blanco. Cuando luego publique hacia la línea, el importe registrado será proporcional al importe neto. Por lo general, el campo Importe neto solo se usa para mostrar el importe neto de la línea.

20. Debajo de las líneas de pedido de compra, en la parte inferior de la página, seleccione **Detalles de línea**.

21. Seleccione la pestaña **Entrega**.

    Se puede asignar una fecha de entrega única a cada línea de pedido. La fecha se hereda del campo del encabezado del pedido de compra, pero puede cambiarlo.

22.  Cierre la página **Línea de pedido de compra**.

23.  En la página **Todos los pedidos de compra**, use la función Filtro y busque su nuevo pedido de compra.

24. Cuando termine, cierre la página **Todos los pedidos de compra** y vuelva a la página de inicio.

