---
lab:
  title: "Laboratorio\_4: Crear un pedido de producción"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Módulo 3: Obtener información sobre los fundamentos de Microsoft Dynamics 365 Supply Chain Management

## Laboratorio 4: Crear un pedido de producción

## Objetivo

El pedido de producción contiene información sobre lo que se va a producir, cuánto se va a producir y la fecha de finalización planificada. También contiene información sobre qué materiales consumir y qué proceso seguir para producir el artículo.

Debe crear un nuevo pedido de producción para su empresa.

## Configuración del laboratorio

   - **Tiempo estimado**: 5 minutos

## Instrucciones

1.  En la **página de inicio de Finance and Operations**, en la parte superior derecha, compruebe que esté trabajando con la empresa **USMF**. 

1.  Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**. 

1.  1\. En el panel de navegación izquierdo, en el módulo **Control de producción**, seleccione **Pedidos de producción** > **Todos los pedidos de producción**. 

1.  En el panel de acciones, seleccione **Nuevo pedido de producción**. 

1.  En **IDENTIFICACIÓN**, en el campo **Número de elemento**, escriba `D0001` y seleccione el elemento **MidRangeSpeaker**. 

1.  En **PRODUCCIÓN**, en el campo **Entrega**, seleccione una fecha un mes después de la fecha de hoy. 
   
    > **Nota**: La fecha de **entrega** indica cuándo debe finalizar el pedido de producción para entregar a tiempo. Esta fecha se puede usar en el proceso de programación. Por ejemplo, puede programar el pedido hacia atrás desde la fecha de entrega. 

1.  En el campo **Cantidad**, escriba `20.00`. 

    > **Nota**: En **L. MAT/RUTA**, el campo **Número de L. MAT** muestra automáticamente el número de cualquier L. MAT activa para el producto actual, pero puede cambiar la L. MAT del pedido de producción si selecciona una L. MAT activa de la lista de versiones de L. MAT aprobadas. El campo **Número de ruta** muestra automáticamente el número de cualquier ruta activa para el producto actual, pero puede cambiar la ruta del pedido de producción si selecciona una ruta activa de la lista de versiones de rutas aprobadas. 

    ![Imagen de pantalla que muestra el panel completo de Crear pedido de producción](./media/lp1-m4-new-production-order-pane.png)

1.  Seleccione **Crear**. 

1.  **Cierre** la página y vuelva a la página de inicio. 

