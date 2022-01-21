---
lab:
    title: 'Laboratorio 1: Crear un producto con descuento'
    module: 'Módulo 3: Aprender los fundamentos de Microsoft Dynamics 365 Commerce'
---

## Laboratorio 1: Crear un producto con descuento

## Objetivos

La tienda de Boston de su empresa está lista para impulsar las ventas de algunos productos que deben venderse para dejar espacio a la nueva línea. Debe crear y activar un nuevo descuento de producto.

## Configuración del laboratorio

   - **Tiempo estimado**: 10 minutos

## Instrucciones

1. En la página Finance and Operations, en la parte superior izquierda, seleccione el menú de hamburguesa **Expandir el panel de navegación**.

1. En el panel de navegación, seleccione **Áreas de trabajo** > **Administración de precios y descuentos**.

1. En la página Administración de precios y descuentos, revise los **Descuentos activos** mostrados actualmente.

1. En el menú, seleccione **Nuevo**, revise las opciones disponibles y luego elija **Descuento**.

1. En la página Descuentos, en cuadro **Nombre**, escriba un nombre para el descuento. Por ejemplo, 20 % en Año Nuevo.

1. En la pestaña General, compruebe que el Estado esté configurado en **Deshabilitado**.

1. El descuento solo se puede editar cuando está deshabilitado.

1. Seleccione el menú **Modo de simultaneidad de descuentos**, revise las opciones disponibles y luego elija **Mejor precio**.

    >[!NOTA] Al elegir entre las opciones del modo de simultaneidad, tenga en cuenta lo siguiente:
    >
    >  - Cuando se aplican varios descuentos simultáneos, siempre se calculará primero el descuento mayor.  El siguiente descuento más alto se calcula entonces sobre el importe pendiente.  Esta jerarquía de cálculo continuará hasta que se hayan aplicado todos los descuentos simultáneos aplicables.  
    >    **Correcto**: 40 % de descuento + 20 % de descuento = 52 % de descuento  
    >      - (40 % de descuento sobre 100 $ = 40 $. Resto = 60 $.  20 % de descuento sobre 60 $ = 12. Resto = 48 $)  
    >
    >    **Incorrecto**: 40 % de descuento + 20 % de descuento = 60 % de descuento
    >
    >  - Los descuentos exclusivos siempre se aplicarán sobre el mejor precio o el descuento simultáneo, incluso si es el porcentaje de descuento menor.
    >    - Cuando sea aplicable más de un descuento exclusivo, se utilizará el más alto.
    >  - Cuando tanto el mejor precio como la simultaneidad son aplicables, o si varios del mismo tipo son aplicables, se utilizará el descuento más alto.

1. Seleccione el menú **Cuenta de descuento** y revise la lista.

1. En el cuadro Cuenta de descuento, especifique un **descuento**.

1. La lista se filtrará automáticamente.

1. En los resultados, seleccione el número de cuenta de descuento **403200**.

1. Revise las otras opciones y luego expanda **Detalles**.

1. En el campo **Descripción**, escriba una descripción del descuento. Por ejemplo, descuento de Año Nuevo que ofrece una rebaja del 20 %.

1. Expanda **Precio/descuento**.

1. En el cuadro Porcentaje de descuento, escriba **20,00**.

1. Expanda **Período de validación**.

1. Seleccione la **Fecha de entrada en vigor** y la **Fecha de vencimiento** del descuento.

1. Asegúrese de establecer la fecha de vencimiento en el futuro; de lo contrario, el descuento no se mostrará en la lista Descuentos activos.

1. Expanda **Líneas**.

1. En el menú, seleccione **+ Agregar**.

1. Seleccione el menú **Categoría** y luego elija **Moda (Moda)**.

1. Esto aplicará el descuento a todos los productos de la categoría Moda.

1. Expanda **Detalles de línea** y luego, en el cuadro **Descripción**, especifique una descripción de las líneas de productos. Por ejemplo, todos los productos de la categoría Moda se incluirán en el descuento.

1. En la parte superior de la página, en el menú, seleccione **Grupos de precios**.

1. En la página Grupos de precios, seleccione el menú **Grupo de precios**.

1. Revise los grupos de precios disponibles, seleccione **Grupo de precios Boston** y luego elija **Guardar**.

1. En la parte superior derecha de la página Grupos de precios, seleccione el icono **Cerrar**.

1. En la página Descuentos, en la pestaña Detalles, seleccione el menú **Estado** y luego elija **Habilitado**.

1. Tenga en cuenta que ya no se podrá editar la configuración de descuentos.

1. Guarde los cambios y luego cierre la página Descuento.

1. En la página Administración de precios y descuentos, revise la pestaña Descuentos activos y compruebe que el descuento recién agregado aparezca en la parte inferior de la lista.

1. Si es necesario, en la parte superior derecha, seleccione el icono **Actualizar** para actualizar la lista de descuentos.
