---
lab:
  title: 'Laboratorio 2: Integración con Excel'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116355"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>Módulo 1: Exploración de las capacidades principales de las aplicaciones de finanzas y operaciones de Dynamics 365

## <a name="lab-2---excel-integration"></a>Laboratorio 2: Integración con Excel

Ahora que ya estamos familiarizados con las aplicaciones de Finance and Operations, vamos a dedicar algo de tiempo a explorar el escenario de integración con Excel.

### <a name="task-1-create-template"></a>Tarea n.° 1: Creación de una plantilla

1. Abra la página de inicio de Finance and Operations. 

2. Vaya a **Módulos** > **Común** > **Común** > **Integración con Office** > **Diseñador de libros** **de Excel**. Tenga en cuenta que casi toda la navegación se realiza a través de módulos, por lo que no suele especificarse.

3. Busque **VendorGroup** en el filtro.

4. En la lista de campos disponibles, seleccione los campos **Grupo de proveedores**, **Descripción** y **Condiciones de pago** y seleccione la flecha derecha para moverlos al cuadro de campo seleccionado.

5. En el panel de acciones, seleccione el botón **Crear libro**.

6. A la derecha, en el panel **Guardar en**, seleccione el botón **Descargar**.

7. Descargue el archivo seleccionando **Guardar como** y almacénelo en la carpeta **Descargas**.

8. Vaya a **Común** > **Integración con Office** > **Plantillas** **de documento**.

9. Seleccione **Nuevo**.

10. En el panel derecho, en la sección **Cargar plantilla**, seleccione el botón **Examinar** y seleccione el archivo descargado anteriormente (si usó el nombre predeterminado, es DynamicsWorkbook).

11. En el campo **Nombre de plantilla**, escriba **CustomVendorGroup**.

12. Seleccione **Aceptar** y después **Guardar**.

### <a name="task-2-open-in-excel"></a>Tarea n.°2: Abrir en Excel

1. Vaya a **Adquisición y abastecimiento** > **Configuración** > **Proveedores** > **Grupos de proveedores**.

2. Seleccione **Abrir en Microsoft Office** > **Abrir en Excel** para buscar la nueva plantilla que cargó, CustomVendorGroup.

3. Seleccione **CustomVendorGroup** y descargue la plantilla de Excel.

4. Guarde y abra la plantilla de Excel descargada, dele permiso si es necesario, cierre la activación y seleccione **Habilitar edición**. Confíe en este complemento y luego inicie sesión (con las mismas credenciales, si se le piden).

Todos los datos existentes de la tabla Grupo de proveedores aparecerán en la hoja de cálculo de Excel.

5. Introduzca un nuevo registro.

6. Escriba **100** en el campo **Grupo de proveedores**, **Proveedor de seguros** en el campo **Descripción** y **Net10** en el campo **Condiciones de pago**.

7. Seleccione el botón **Publicar** en la aplicación de complemento de Office de Microsoft Dynamics.

8. Abra el formulario **Grupo de proveedores** para confirmar que el nuevo registro se ha agregado.

