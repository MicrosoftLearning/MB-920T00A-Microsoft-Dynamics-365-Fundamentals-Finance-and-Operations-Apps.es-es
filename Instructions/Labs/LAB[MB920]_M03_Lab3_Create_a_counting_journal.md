---
lab:
  title: 'Laboratorio 3: Creación de un diario de recuento'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 3: Obtener información sobre los fundamentos de Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Laboratorio 3: Creación de un diario de recuento

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. En el panel de navegación izquierdo, seleccione **Módulos** > **Gestión del inventario** > **Entradas del diario** > **Recuento de artículos** > **Recuento**.

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. El formulario del diario de recuento de inventario aparecerá con encabezado e información detallada

![Captura de pantalla del formulario de diario de recuento de inventario con encabezado e información detallada cumplimentados](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Seleccione **Crear líneas: &gt; En línea** en el panel de acciones.

6. En el panel de diálogo **Crear el diario de recuento disponible**, establezca los campos **Almacén**, **Estado de inventario**, Ubicación y **Matrícula de entidad de almacén** en **Sí**. 

![Captura de pantalla del panel de diálogo Crear el diario de recuento disponible con los campos establecidos según lo descrito](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. Seleccione **Aceptar** en la parte inferior del formulario **Crear el diario de recuento disponible**.

La cantidad disponible del artículo A0001 aparecerá en la sección **Líneas de diario**, con un desglose por sitio, almacén, ubicación y matrícula de entidad de almacén.

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - Si la cantidad **Disponible** es la misma que la cantidad reflejada en **Contado**, el campo **Cantidad** estará en blanco.

    - Si el valor del campo **Contado** es mayor que el campo **Disponible**, el campo **Cantidad** contendrá un valor positivo.

    - Si el valor del campo **Contado** es menor que el campo **Disponible**, el campo **Cantidad** contendrá un valor negativo.

10. Seleccione el botón **Validar** en el panel de acciones y, a continuación, seleccione el botón **Publicar**.

11. Cierre la página y vuelva a la página de inicio.
