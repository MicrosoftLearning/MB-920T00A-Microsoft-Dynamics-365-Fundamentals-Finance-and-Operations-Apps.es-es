---
lab:
  title: "Laboratorio\_4: Crear un pedido de producción"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

## <a name="lab-4---create-a-production-order"></a>Laboratorio 4: Creación de un pedido de producción

## <a name="objectives"></a>Objetivos

The production order contains information about what will be produced, the quantity to produce, and the planned finish date. It also contains information about which materials to consume and which process to follow to produce the item.

Debe crear un nuevo pedido de producción para su empresa.

## <a name="lab-setup"></a>Configuración del laboratorio

   - **Tiempo estimado**: 5 minutos

## <a name="instructions"></a>Instrucciones

1. En la página de inicio de Finance and Operations, en la parte superior derecha, compruebe que esté trabajando con la empresa USMF.

1. Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**.

1. En el panel de navegación izquierdo, seleccione **Módulos** > **Control de producción** > **Pedidos de producción** > **Todos los pedidos de producción**.

1. En el menú superior, seleccione **Nuevo pedido de producción**.

1. En **IDENTIFICACIÓN**, en el cuadro **Número de artículo**, escriba **D0001** y luego seleccione el artículo identificado.

1. En **PRODUCCIÓN**, en el cuadro **Entrega**, seleccione una fecha un mes después de la fecha de hoy.  
    The delivery date indicates when the production order should end in order to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

1. En el cuadro **Cantidad**, escriba **20**.

1. Under <bpt id="p1">**</bpt>BOM/ROUTE<ept id="p1">**</ept>, the BOM number field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The Route number field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

    ![Imagen de pantalla que muestra el panel completo de Crear pedido de producción](./media/lp1-m4-new-production-order-pane.png)

1. Seleccione **Crear**.
