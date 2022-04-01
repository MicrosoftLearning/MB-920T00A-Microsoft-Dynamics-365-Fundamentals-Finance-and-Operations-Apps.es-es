---
lab:
  title: 'Laboratorio 3: Laboratorio de proyecto final de Dynamics 365 Commerce'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: c498966dc4b2bba78b4e0d27077c4b346666323f
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909678"
---
## <a name="lab-3---dynamics-365-commerce-capstone-lab"></a>Laboratorio 3: Laboratorio de proyecto final de Dynamics 365 Commerce

## <a name="objective"></a>Objetivos

En este laboratorio, explorará los fundamentos de la configuración de sedes en Commerce. Las características principales incluyen la configuración de canales comerciales, creación de surtidos y configuración de descuentos comerciales.

## <a name="lab-setup"></a>Configuración del laboratorio

   - **Tiempo estimado**: 30 minutos 

## <a name="instructions"></a>Instrucciones

## <a name="exercise-1-explore-commerce-headquarters"></a>Ejercicio 1: Explorar la sede de Commerce

### <a name="create-a-new-store"></a>Crear una nueva tienda

1. En la página de aterrizaje, en la esquina superior derecha, compruebe que se ha seleccionado la empresa **USRT**.

1. De no ser así, seleccione la empresa enumerada actualmente y especifique **USRT**.

1. En el panel de navegación, seleccione **Módulos** > **Venta minorista y comercio** > **Canales** > **Tiendas** > **Todas las tiendas**.

1. En el panel de acciones, seleccione  **+Nuevo** para crear una nueva tienda.

1. En la ventana Nuevo registro, utilice los ajustes en la siguiente tabla para actualizar los valores:

    | **Configuración**| **Valor**|
    | :--- | :--- |
    | Nombre| Seattle Flagship Store|
    | Número de tienda| 000098|
    | Warehouse| Seattle|
    | Almacén de envío| Seattle|
    | Zona horaria de la tienda| (GMT-08:00) Hora del Pacífico|
    | Perfil de funcionalidad| FN001|
    | Búsqueda de inventario| Sí|
    | Perfil del canal| Valor predeterminado|
    | Perfil sin conexión| Valor predeterminado|
    | Grupo de impuestos| WA|
    | Usar impuesto basado en el destino| Sí|
    | Libreta de direcciones de cliente| Cliente comercial|
    | Libreta de direcciones de empleado| Seattle|
    | Cliente predeterminado| 3002|

1. En el panel de acciones, seleccione **Guardar**.

1. Seleccione la ficha desplegable **Extracto/cierre** y especifique las siguientes actualizaciones:

    | Configuración| Value|
    | :--- | :--- |
    | Cálculo del importe del extracto| Último|
    | Diferencia máxima > Registro| 100,00|

1. Seleccione la ficha desplegable **Dimensiones financieras** y especifique las siguientes actualizaciones:

    | Configuración| Value|
    | :--- | :--- |
    | BusinessUnit| 004|
    | RetailChannel| 000210|

1. Seleccione la ficha desplegable **Diseño de pantalla**.

1. En el cuadro **Id. de diseño de pantalla**, especifique  **A2CP16:9C**.

1. En el panel de acciones, seleccione **Guardar**.

1. En el panel de acciones, seleccione  **Configurar** y, en la pestaña **COPIAR**, seleccione **Copiar todo**.

1. En el panel **Copiar todo**, seleccione el menú **Desde la tienda** y, después, seleccione **ANNAPOL**.

1. Si es necesario, seleccione el menú **A la tienda** y, después, **00098**.

1. Seleccione  **Aceptar**.

1. Compruebe que se muestra el mensaje de operación correcta y cierre la página.

### <a name="add-a-group-of-products-to-an-assortment-and-publish"></a>Agregar un grupo de productos a un surtido y publicarlo

1. En el panel de navegación, seleccione  **Módulos** > **Administración de la organización** > **Organizaciones** > **Jerarquías organizativas**.

1. En la lista de navegación, seleccione **Tiendas por región**.

1. En el panel de acciones, seleccione **Ver**.

1. En la página Diseñador de jerarquías, en el panel de acciones, seleccione **Editar**.

1. En el icono **Oeste**, seleccione el icono de puntos suspensivos ( **...** ).

1. En la página Diseñador de jerarquías, seleccione  **Insertar** > **Canal comercial**.

1. En el panel **Canal comercial**, seleccione **Seattle Flagship Store** y luego **Aceptar**.

1. En el panel de acciones, seleccione **Guardar**.

1. En el cuadro de diálogo, revise la información y, después, seleccione **Cerrar**.

1. En el panel de acciones, seleccione **Publicar**.

1. En el panel **Publicar cambios**, en el cuadro **Fecha de vigencia**, seleccione el primer día del mes actual.

1. En el cuadro **Describir cambios**, escriba **Adición de Seattle Flagship Store** y luego seleccione **Publicar**.

1. En el cuadro de diálogo, revise la información y, después, seleccione **Cerrar**.

1. En el panel de acciones, seleccione **Guardar**.

1. En el cuadro de diálogo, revise la información y, después, seleccione **Cerrar**.

1. Cierre la página.

1. En el panel de navegación, seleccione  **Módulos** > **Venta minorista y comercio** > **Catálogos y surtidos** > **Surtidos**.

1. En la página Surtidos, seleccione **AW-Outlet**.

1. En el panel de acciones, seleccione **Editar**.

1. En el cuadro de diálogo, seleccione **Sí** para confirmar la selección de edición.

1. En la página AW-Outlet, seleccione la ficha desplegable **canal de Commerce**.

1. En la barra de herramientas, seleccione **+Agregar línea**.

1. En el panel **Elegir nodos de organización**, seleccione el menú **Jerarquía organizativa** y, después, seleccione **Tiendas por región**.

1. En **NODOS ORGANIZATIVOS DISPONIBLES**, seleccione  **Seattle Flagship Store** y luego el icono de flecha derecha **Agregar** para que se agregue a los **NODOS ORGANIZATIVOS SELECCIONADOS**.

1. Seleccione  **Aceptar**.

1. En el panel de acciones, seleccione **Publicar**.

1. En el cuadro de diálogo, revise la información y, después, seleccione **Sí**.

1. En el panel de acciones, seleccione **Editar**.

1. En el cuadro de diálogo de **confirmación**, seleccione **Sí**.

1. En la página AW-Outlet, seleccione la pestaña **Productos**.

1. En la página AW-Outlet, seleccione **+ Agregar línea**.

1. Seleccione el menú **Categoría**,  **Deportes de equipo** y, después,  **Aceptar**.

1. En el panel de acciones, seleccione **Publicar**.  

### <a name="run-the-retail-scheduler-job-for-products"></a>Realizar el trabajo de programador minorista para productos

1. En el panel de navegación, seleccione  **Módulos** > **Venta minorista y comercio** > **TI de venta minorista y comercio** > **Programación de distribución**.

1. En la lista de navegación, seleccione **1040 (Productos)** .

1. En el panel de acciones, seleccione **Ejecutar ahora**.

1. En el panel **Sincronización incremental con programación “1040”** , revise la información y seleccione  **Aceptar**.

### <a name="create-a-new-product-discount"></a>Crear un nuevo descuento de producto

1. En el panel de navegación, seleccione  **Módulos** > **Venta minorista y comercio** > **Precios y descuentos** > **Todos los descuentos**.

1. En el panel de acciones, seleccione  **Nuevo** > **Descuento**.

1. En el cuadro **Nombre** de la página Descuentos, escriba  **Apertura de tienda**.

1. En la ficha desplegable **Detalles**, en el cuadro **Descripción**, escriba **Apertura de tienda 20 % de descuento**.

1. En la ficha desplegable **Precios/descuentos**, en el cuadro **Porcentaje de descuento**, escriba **20,00**.

1. En la ficha desplegable **Período de validación**, en el cuadro **Fecha de vigencia**, escriba una fecha del mes anterior.

1. En el cuadro **Fecha de vencimiento**, escriba una fecha a una semana de la fecha actual.

1. En la ficha desplegable **Líneas**, en la barra de herramientas, seleccione **+Agregar**.

1. En la columna **Categoría**, seleccione el menú, luego **Deportes de equipo** y, después, **Aceptar**.

1. En el panel de acciones, seleccione **Guardar**.

1. En el panel de acciones, seleccione **Grupos de precios**.

1. En la página Grupos de precios, seleccione el menú **Grupos de precios** y luego **Oeste**.

1. En el panel de acciones, seleccione **Guardar**.

1. En el panel de navegación, seleccione  **Módulos** > **Venta minorista y comercio** > **Precios y descuentos** > **Todos los descuentos**.

1. En la lista de navegación, seleccione **ST100101**.

1. En la ficha desplegable **General**, seleccione el menú **Estado** y luego  **Habilitado**.

1. En el panel de acciones, seleccione **Guardar**.

1. Cierre el formulario.

1. En el panel de navegación, seleccione  **Módulos** > **Venta minorista y comercio** > **TI de venta minorista y comercio** > **Programación de distribución**.

1. En la lista de navegación, seleccione **1020 (Productos)** .

1. En el panel de acciones, seleccione **Ejecutar ahora**.

1. En el panel **Sincronización incremental con programación “1020”** , revise la información y seleccione  **Aceptar**.
