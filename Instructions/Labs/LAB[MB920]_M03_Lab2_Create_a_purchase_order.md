---
lab:
  title: "Laboratorio\_2: Crear un pedido de compra"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 3: Obtener información sobre los fundamentos de Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-2---create-a-purchase-order"></a>Laboratorio 2: Creación de un pedido de compra

## <a name="objectives"></a>Objetivos

It's more typical for purchase orders to be created automatically as result of master planning, direct delivery, and other processes. When created manually, a purchase order is usually created by a purchasing agent. Create a purchase order using the the USMF company.

## <a name="lab-setup"></a>Configuración del laboratorio

   - **Tiempo estimado**: 10 minutos

## <a name="instructions"></a>Instrucciones

1. En la página de inicio de Finance and Operations, en la parte superior derecha, compruebe que esté trabajando con la empresa USMF.

1. Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**.

1. En la esquina superior izquierda, seleccione el menú de hamburguesa **Expandir el panel de navegación**.

1. Seleccione **Módulos** > **Adquisiciones y abastecimiento** > **Pedidos de compra** > **Todos los pedidos de compra**.

1. En la página Todos los pedidos de compra, en el menú superior, seleccione **+ Nuevo**.

1. En el panel Crear pedido de compra, seleccione el menú **Cuenta del proveedor** y, después, seleccione **US-101**.

1. When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, will be copied as default values into the order header. You can change these values at any time.

1. Expanda la sección **General**.

1. Debajo de **DIMENSIONES DE ALMACENAMIENTO**, seleccione el menú **Sitio** y revise la lista de sitios.

1. The Site field, together with the Warehouse field, specifies where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

1. Debajo de **FECHAS**, el campo Fecha de entrega se utiliza para especificar cuándo deben entregarse los bienes y servicios adquiridos.

1. You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here cannot be met for specific products or services because they have longer lead times, then those lines will be created with a later delivery date to accommodate for this.

1. Expand the <bpt id="p1">**</bpt>Administration<ept id="p1">**</ept> section. The <bpt id="p1">**</bpt>Orderer<ept id="p1">**</ept> box can be used to specify who is placing the order.

1. Es más común que los pedidos de compra se creen automáticamente como resultado de la planificación maestra, la entrega directa y otros procesos.

1. Seleccione **Aceptar**.

1. Cuando se crean de forma manual, los pedidos de compra suelen crearse por un agente de compras.

    ![Imagen de pantalla que muestra la ubicación del menú Encabezado](./media/lp1-m3-purchase-order-header-option.png)

1. Debajo de **Líneas de pedido de compra**, en el menú, seleccione **Línea de pedido de compra**.

    ![Imagen de pantalla que muestra la ubicación de la opción de menú Línea de pedido de compra](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. Debajo de **MOSTRAR**, seleccione **Dimensiones**.

1. Crear un pedido de compra mediante la empresa USMF.

1. En el panel Presentación de dimensiones, en **DIMENSIONES DEL PRODUCTO**, seleccione el cuadro **Color**.

1. Opcional: Si selecciona el conmutador de alternancia Guardar configuración, las dimensiones que ha elegido también se mostrarán en la cuadrícula de la línea de pedido la próxima vez que abra la página de pedido de compra.

1. Seleccione **Aceptar**.

1. Seleccione el menú de celda **Código de artículo** y, a continuación, **T0004**.

1. Recuerde que también puede escribir el cuadro de filtro en lugar de desplazarse por la lista.

1. Las líneas de pedido se crean para productos y servicios mediante la especificación de un código de producto o como gastos si se especifica una categoría de compras.

1. Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. This means that if you need to expense a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category and in this case, the procurement category is shown as informational only.

1. Seleccione el menú **Color**, revise las opciones disponibles y luego seleccione uno de los colores o combinaciones de colores.

1. El sitio y el almacén generalmente se rellenan con los valores del encabezado del pedido, pero es posible invalidar los campos si algunas líneas deben entregarse en diferentes ubicaciones.

1. En el cuadro **Cantidad**, escriba **10**.

1. El campo Cantidad se rellena automáticamente con la cantidad de pedido mínima para el producto si está configurado, o con el valor de 1.

1. Información adicional:

    - <bpt id="p1">**</bpt>Unit<ept id="p1">**</ept>: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

    - <bpt id="p1">**</bpt>Unit price<ept id="p1">**</ept>: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines—for example, if a unique price is negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount<ept id="p1">**</ept>: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount percentage<ept id="p1">**</ept>: When entered, this reduces the net amount for the line accordingly. The discount percent is often supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Net amount<ept id="p1">**</ept>: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It is possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields will be blank, and when you post toward the line, the amount posted will be proportional to the net amount. Generally, the Net Amount field is only used for displaying the net amount of the line.

1. Debajo de las líneas de pedido de compra, en la parte inferior de la página, seleccione **Detalles de línea**.

1. Seleccione la pestaña **Entrega**.

1. A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change this.

1. Cierre la página Línea de pedido de compra.

1. En la página Todos los pedidos de compra, use la función Filtro y busque su nuevo pedido de compra.

1. Cuando termine, cierre la página Todos los pedidos de compra y vuelva a la página de inicio.
