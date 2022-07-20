---
lab:
  title: 'Laboratorio 3: Creación de un diario de recuento'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 5e61646d33f284bb7e30b6f63a7db4778f58b47c
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116366"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 3: Obtener información sobre los fundamentos de Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Laboratorio 3: Creación de un diario de recuento

1. En la página de inicio de Finance and Operations, en la parte superior derecha, compruebe que está trabajando con la empresa **USMF**. Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**.

2. En el panel de navegación izquierdo, seleccione **Módulos** > **Gestión del inventario** > **Entradas del diario** > **Recuento de artículos** > **Recuento**.

3. Seleccione el botón **+Nuevo** en el panel de acciones. El formulario de diálogo **Crear diario de inventario** aparecerá con el botón **Aceptar** en la parte inferior. Seleccione el botón **Aceptar**.

4. El formulario del diario de recuento de inventario aparecerá con encabezado e información detallada

![Captura de pantalla del formulario de diario de recuento de inventario con encabezado e información detallada cumplimentados](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Seleccione **Crear líneas: &gt; En línea** en el panel de acciones.

6. En el panel de diálogo **Crear el diario de recuento disponible**, establezca los campos **Almacén**, **Estado de inventario**, Ubicación y **Matrícula de entidad de almacén** en **Sí**. 

![Captura de pantalla del panel de diálogo Crear el diario de recuento disponible con los campos establecidos según lo descrito](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expanda la sección **Registros que incluir** y seleccione el vínculo **Filtrar**. En el campo **Código de artículo**, seleccione **A0001** y, a continuación, seleccione **Aceptar**.

8. Seleccione **Aceptar** en la parte inferior del formulario **Crear el diario de recuento disponible**.

La cantidad disponible del artículo A0001 aparecerá en la sección **Líneas de diario**, con un desglose por sitio, almacén, ubicación y matrícula de entidad de almacén.

9. En la columna **Contado** de la sección **Líneas de diario**, escriba las cantidades que se han contado en cada sitio/almacén/ubicación/matrícula de entidad de almacén. Tenga en cuenta lo siguiente:

    - Si la cantidad **Disponible** es la misma que la cantidad reflejada en **Contado**, el campo **Cantidad** estará en blanco.

    - Si el valor del campo **Contado** es mayor que el campo **Disponible**, el campo **Cantidad** contendrá un valor positivo.

    - Si el valor del campo **Contado** es menor que el campo **Disponible**, el campo **Cantidad** contendrá un valor negativo.

10. Seleccione el botón **Validar** en el panel de acciones y, a continuación, seleccione el botón **Publicar**.

11. Cierre la página y vuelva a la página de inicio.
