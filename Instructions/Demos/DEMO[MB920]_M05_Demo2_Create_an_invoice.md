---
demo:
  title: 'Demostración 2: Crear una factura'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>Demo 2: Crear una factura

1. Vaya al área de trabajo  **Administración de proyectos**.  
    In this demo, we'll go over the process of invoicing a single project within project operations. Although it's possible to perform mass invoicing, for demonstration purposes we will focus on just a single time and material project. We'll also see the posting results and financial insights within the project statement. Let's start with project invoicing. 

1. In the top-right company picker, verify the legal entity you are connected to is<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>.  
    From the<bpt id="p1"> **</bpt>Project management<ept id="p1">**</ept> workspace, we can see all the active projects. We can search for projects using the filter, or in this example, we will select a known Project ID. 

1. En la tabla  **Proyectos activos** , en la tabla  **ID de proyecto** , seleccione  **00000093 Contoso Consulting**.  

1. Después, abra la página  **Propuestas de factura de proyecto**  para ver todas las facturas anteriores procesadas para Contoso Consulting. 

1. En la pestaña  **FACTURA**  del panel de acciones, seleccione  **Propuestas de factura de proyecto**. 

1. En la barra de navegación de la página  **Propuestas de factura de proyecto** , seleccione  **Nueva** y después  **Propuesta de factura**.  
    Como se trata de una factura de tiempo y material, no es necesario que seleccionemos la opción Propuesta de factura desde la regla de facturación. 

    ![Una factura de pantalla de la página Propuestas de factura de proyecto con la nueva propuesta de factura resaltada.](./media/projops_invoice_1_new_invoice_proposal.png)

1. En el panel  **Crear propuesta de factura** , apunte a los cuadros bajo  **Seleccionar transacciones**.  
    From here, we can select things such as the invoicing method, the invoice date, the funding source, and the project. We can also choose to include sub projects, as well as incorporate transaction types, the start and end dates for transactions, and any financial dimensions we need. 

    ![Una captura de pantalla del panel Crear propuesta de factura con la sección Seleccionar transacciones resaltada.](./media/projops_invoice_2_select_transactions.png)

1. En el menú desplegable  **Proyecto** , seleccione  **00000093 Contoso Consulting**. 

1. Para este ejemplo, asegúrese de que la  **Fecha de factura** está establecida en  **01/02/21**, la  **Fecha de inicio**  está establecida como  **01/02/21** y que la fecha de finalización es la fecha de hoy.  
    Una vez ha seleccionado todo, seleccione el botón de búsqueda para buscar las transacciones que cumplan dichos parámetros.

1. Seleccione  **Buscar**.  
    En esta demo repasaremos el proceso de facturación de un único proyecto en Project Operations.

1. En la pestaña  **Transacciones del proyecto** , seleccione  **Seleccionar todo**.

1. Seleccione  **Aceptar**. 

1. En la página  **Propuesta de factura** , apunte a la columna  **Importe de línea de factura** .  
    Aquí podremos ver el importe y el resumen de la factura, las transacciones de horas y los gastos.

    ![Una captura de pantalla de la página Propuesta de factura con la columna Importe de línea de factura resaltada.](./media/projops_invoice_3_invoice_line_amount_column.png)

1. Apunte a la pestaña  **Hora** . 

1. Apunte a la pestaña  **Gasto**.  
    También puede cambiar y mirar la transacción de gastos.  
Después, vamos a comprobar el botón de totales para ver el aspecto que tendrá la factura desde una perspectiva tanto de costes como de ingresos.

1. En la barra de navegación, seleccione  **Totales**.

1. En la página  **Totales**, apunte a la columna  **CONTABILIDAD GENERAL**, a la columna  **CLIENTE**  y a la columna  **Descuento de línea**.  
    En la pantalla Totales, podemos ver cuál será el impacto en la contabilidad general, cualquier información del cliente, como los límites de crédito, los descuentos, los impuestos y el impacto neto de la factura. 

1. En el lado derecho de la pantalla, seleccione  **X**  para cerrar la página.  
    Aunque es posible hacer una facturación en masa, en esta demostración nos centraremos en un único proyecto de tiempo y material. 

1. En la barra de navegación de la página  **Propuesta de factura** , seleccione  **Vista previa de impresión**. 

1. En el cuadro de diálogo, seleccione  **Vista previa de impresión**.  
    Aquí puede ver un ejemplo de la vista previa de impresión de una factura proforma. 

1. Seleccione **X**  para cerrar la página.  
    Una vez validada toda la información y si todos están satisfechos con la vista previa de impresión de la factura, podemos registrar la propuesta de factura.

1. En la barra de navegación, seleccione  **Registrar**.

1. Seleccione la pestaña  **Parámetros** .

1. En  **PARÁMETRO**, establezca  **Registro**  en  **Sí**.

1. En  **OPCIONES DE IMPRESIÓN**, establezca  **Imprimir factura** en  **Sí**.

1. Seleccione  **Aceptar**.

1. En la página  **Factura** , apunte al número de  **factura**.  
    Se habrá generado un número de factura.  
    Una vez registrada la factura, podemos revisar la información del diario de factura y explorar en profundidad las transacciones contables.

1. Vaya al área de trabajo  **Administración de proyectos**.

1. En la tabla  **Proyectos activos** , seleccione el proyecto  **00000093** **Contoso Consulting**.

1. En la pestaña  **FACTURA**  del panel de acciones, seleccione  **Diarios de factura**.

1. En la barra de acciones de la página  **Diario de factura** , seleccione  **Vale**.

1. En la página  **Transacciones de vales** , apunte a la columna  **Cuenta contable**.  
    También veremos los resultados del registro y la información financiera del informe del proyecto.

1. Vaya al área de trabajo  **Administración de proyectos** . 

1. En la tabla  **Proyectos activos** , seleccione el proyecto  **00000093 Contoso Consulting**.

1. En la barra de navegación de la página  **Contoso Consulting** , seleccione  **Control**.  
    Desde aquí podemos ver todos los detalles del proyecto.  
    Ahora vamos a mirar los aspectos financieros del proyecto en un informe de proyecto.

1. Seleccione  **Informes de proyecto**.

1. En la página  **Informes de proyecto** , apunte a la sección  **FECHA DEL PROYECTO** .  
Puede crear un informe de cualquier intervalo de fechas que desee.

1. Seleccione el cuadro de fecha  **Desde** y escriba  **01/02/2021**.
1. 
1. Seleccione el cuadro de fecha  **Hasta**  y escriba la fecha de hoy.

1. Cuando termine, seleccione  **Calcular**.

    ![Una captura de pantalla de la página Informes de proyecto con la opción Calcular resaltada.](./media/projops_invoice_4_calculate.png)

1. Apunte a  **Transacciones**.  
    Comencemos con la facturación del proyecto.
