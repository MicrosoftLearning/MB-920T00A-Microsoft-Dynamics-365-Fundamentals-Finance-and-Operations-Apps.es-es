---
demo:
  title: 'Demostración 2: Crear una factura'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
ms.openlocfilehash: 2c63541757afd9de3bea634353c739ed099d0bc6
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909737"
---
## <a name="demo-2---create-an-invoice"></a>Demo 2: Crear una factura

1. Vaya al área de trabajo **Administración de proyectos**.  
    En esta demo repasaremos el proceso de facturación de un único proyecto en Project Operations. Aunque es posible hacer una facturación en masa, en esta demostración nos centraremos en un único proyecto de tiempo y material. También veremos los resultados del registro y la información financiera del informe del proyecto. Comencemos con la facturación del proyecto. 

1. En el selector de empresas de la parte superior derecha, compruebe que la entidad legal a la que está conectado es **USSI**. Si no es así, cambie la entidad jurídica a **USSI**.  
    Desde el área de trabajo **Administración de proyectos**, podremos ver todos los proyectos activos. Podemos buscar proyectos mediante el filtro o, como en este ejemplo, podemos seleccionar una id. de proyecto conocida. 

1. En la columna **Id. de proyecto** de la tabla **Proyectos activos**, seleccione **00000093 Consultoría Contoso**.  

1. Después, abra la página **Propuestas de factura de proyecto** para ver todas las facturas anteriores procesadas para Consultoría Contoso. 

1. En la pestaña **FACTURA** del panel de acciones, seleccione **Propuestas de factura de proyecto**. 

1. En la barra de navegación de la página **Propuestas de factura de proyecto**, seleccione **Nueva** y después **Propuesta de factura**.  
    Como se trata de una factura de tiempo y material, no es necesario que seleccionemos la opción Propuesta de factura desde la regla de facturación. 

    ![Una factura de pantalla de la página Propuestas de factura de proyecto con la nueva propuesta de factura resaltada.](./media/projops_invoice_1_new_invoice_proposal.png)

1. En el panel **Crear propuesta de factura**, apunte a los cuadros bajo **Seleccionar transacciones**.  
    Desde aquí, podremos seleccionar opciones como el método de facturación, la fecha de la factura, la fuente de financiación y el proyecto. También podremos optar por incluir subproyectos, además de incorporar tipos de transacciones, las fechas de inicio y finalización de las transacciones y cualquier dimensión financiera que necesitemos. 

    ![Una captura de pantalla del panel Crear propuesta de factura con la sección Seleccionar transacciones resaltada.](./media/projops_invoice_2_select_transactions.png)

1. En el menú desplegable **Proyecto**, seleccione **00000093 Consultoría Contoso**. 

1. Para este ejemplo, asegúrese de que la **Fecha de factura** está establecida en **01/02/21**, la **Fecha de inicio** está establecida como **01/02/21** y que la fecha de finalización es la fecha de hoy.  
    Una vez ha seleccionado todo, seleccione el botón de búsqueda para buscar las transacciones que cumplan dichos parámetros.

1. Seleccione **Search**.  
    Luego, para facturar todas las transacciones, seleccione la opción Seleccionar todo. De esta forma se seleccionarán los elementos que elegimos para gastos y horas.

1. Bajo la pestaña **Transacciones de proyectos**, seleccione **Seleccionar todo**.

1. Seleccione **Aceptar**. 

1. En la página **Propuesta de factura**, apunte a la columna **Importe de línea de factura**.  
    Aquí podremos ver el importe y el resumen de la factura, las transacciones de horas y los gastos.

    ![Una captura de pantalla de la página Propuesta de factura con la columna Importe de línea de factura resaltada.](./media/projops_invoice_3_invoice_line_amount_column.png)

1. Apunte a la pestaña **Hora**. 

1. Apunte a la pestaña **Gasto**.  
    También puede cambiar y mirar la transacción de gastos.  
Después, vamos a comprobar el botón de totales para ver el aspecto que tendrá la factura desde una perspectiva tanto de costes como de ingresos.

1. En la barra de navegación, seleccione **Totales**.

1. En la página **Totales**, apunte a la columna **CONTABILIDAD GENERAL**, a la columna **CLIENTE** y a la columna **Descuento de línea**.  
    En la pantalla Totales, podemos ver cuál será el impacto en la contabilidad general, cualquier información del cliente, como los límites de crédito, los descuentos, los impuestos y el impacto neto de la factura. 

1. En el lado derecho de la pantalla, seleccione **X** para cerrar la página.  
    Ya estamos listos para crear una vista previa de impresión para asegurarnos de que toda la información de la factura es correcta. Algunas organizaciones utilizan la vista previa durante las reuniones de revisión del proyecto para asegurarse de que todos están de acuerdo con los totales antes de finalizar la factura. 

1. En la barra de navegación de la página **Propuesta de factura**, seleccione **Vista previa de impresión**. 

1. En el cuadro de diálogo, seleccione **Vista previa de impresión**.  
    Aquí puede ver un ejemplo de la vista previa de impresión de una factura proforma. 

1. Seleccione **X** para cerrar la página.  
    Una vez validada toda la información y si todos están satisfechos con la vista previa de impresión de la factura, podemos registrar la propuesta de factura.

1. En la barra de navegación, seleccione **Registrar**.

1. Seleccione la pestaña **Parámetros** .

1. Bajo **PARÁMETRO**, establezca **Registro** en la opción **Sí**.

1. Bajo **OPCIONES DE IMPRESIÓN**, establezca **Imprimir factura** en la opción **Sí**.

1. Seleccione **Aceptar**.

1. En la página **Factura**, apunte al número de **Factura**.  
    Se habrá generado un número de factura.  
    Una vez registrada la factura, podemos revisar la información del diario de factura y explorar en profundidad las transacciones contables.

1. Vaya al área de trabajo **Administración de proyectos**.

1. En la tabla **Proyectos activos**, seleccione el proyecto **00000093** **Consultoría Contoso**.

1. En la pestaña **FACTURA** del panel de acciones, seleccione **Diarios de factura**.

1. En la barra de acciones de la página **Diario de factura**, seleccione **Vale**.

1. En la página **Transacciones de vales**, apunte a la columna **Cuenta contable**.  
    Aquí podemos ver los resultados registrados de la contabilidad general. Las cuentas de contabilidad general están determinadas por la configuración de cuenta y las dimensiones financieras aplicadas a cada proyecto.

1. Vaya al área de trabajo **Administración de proyectos**. 

1. En la tabla **Proyectos activos**, seleccione el **00000093 Proyecto Consultoría Contoso**.

1. En la barra de navegación de la página **Consultoría Contoso**, seleccione **Control**.  
    Desde aquí podemos ver todos los detalles del proyecto.  
    Ahora vamos a mirar los aspectos financieros del proyecto en un informe de proyecto.

1. Seleccione **Informes de proyecto**.

1. En la página **Informes de proyecto**, apunte a la sección **FECHA DEL PROYECTO**.  
Puede crear un informe de cualquier intervalo de fechas que desee.

1. Seleccione el cuadro de fecha **Desde** y escriba **01/02/2021**.
1. 
1. Seleccione el cuadro de fecha **Hasta** y escriba la fecha de hoy.

1. Cuando termine, seleccione **Calcular**.

    ![Una captura de pantalla de la página Informes de proyecto con la opción Calcular resaltada.](./media/projops_invoice_4_calculate.png)

1. Apunte a **Transacciones**.  
    Una vez se hayan actualizado los datos, los directores de proyectos podrán explorar en profundidad los detalles de las transacciones para tomar decisiones sobre el proyecto o para hacer modificaciones en caso de que sea necesario. En esta demostración hemos procesado una factura de tiempo y material con una transacción tanto de horas como de gastos. Hemos mirado una vista previa de la factura, la hemos registrado, hemos revisado el registro de contabilidad y por último hemos revisado el impacto financiero a través del informe del proyecto.
