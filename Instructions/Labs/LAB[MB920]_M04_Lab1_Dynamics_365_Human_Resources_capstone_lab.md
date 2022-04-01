---
lab:
  title: 'Laboratorio 1: Laboratorio de proyecto final de Dynamics 365 Human Resources'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Human Resources'
ms.openlocfilehash: e1d0f9974a3c1d6f4b31bb62733153850e2c86b0
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 01/27/2022
ms.locfileid: "137910180"
---
## <a name="lab-1---dynamics-365-human-resources-capstone-lab"></a>Laboratorio 1: Laboratorio de proyecto final de Dynamics 365 Human Resources

## <a name="objective"></a>Objetivos

En este laboratorio, explorará el proceso de incorporación para un nuevo empleado, incluida la creación de un registro de empleado. También revisará el proceso de evaluaciones de rendimiento, que incluyen el establecimiento de objetivos y la evaluación del desempeño. Además, utilizará características de autoservicio para enviar un informe de gastos.

## <a name="lab-setup"></a>Configuración del laboratorio

- **Tiempo estimado**: 20 minutos 

## <a name="exercise-1-explore-human-resources"></a>Ejercicio 1: Explorar Dynamics 365 Human Resources

### <a name="create-a-new-hire-record"></a>Crear un registro de nueva contratación

1. En el panel de navegación, seleccione **Módulos** > **Recursos humanos** > **Puestos** > **Puestos**.

1. En el panel de acciones, seleccione **+Nuevo** para crear un nuevo puesto.

1. En el cuadro de diálogo **Crear nuevo puesto**, seleccione el menú **Trabajo** y luego **Administrador de la tienda**.

1. Seleccione **Crear puesto**.

1. En el panel de navegación, seleccione **Módulos** > **Trabajadores** > **Empleados**.

1. En el panel de acciones, seleccione **+Nuevo** para crear un nuevo empleado.

1. En el panel **Contratar trabajador nuevo**, especifique las siguientes actualizaciones y luego seleccione **Contratar y agregar detalles**.

    | **Configuración** | **Valor** |
    | :--- | :---- |
    | Nombre | Bill |
    | Apellido | Smith |
    | Fecha inicial del empleo | Seleccione la fecha actual|

### <a name="create-a-goal-for-the-new-hire"></a>Crear un objetivo para la nueva contratación

1. En el panel de acciones, seleccione **Trabajador**.

1. En la pestaña **DESARROLLO**, seleccione **Objetivos**.

1. Es posible que deba desplazarse hacia la derecha para ver la pestaña.

1. En el panel de acciones, seleccione **+Nuevo** para crear un nuevo objetivo.

1. En la ficha desplegable **General**, especifique las siguientes actualizaciones:

    | **Configuración** | **Valor** |
    | :--- | :---- |
    | Nombre | Objetivo de ventas trimestral |
    | Información general | Ayude al equipo de la tienda a alcanzar el objetivo de ventas trimestral. |
    | Categoría del objetivo | Sales |
    | Fecha de inicio | Seleccione una fecha una semana después de la fecha actual |
    | Fecha de finalización | Seleccione una fecha 2 semanas después de la fecha de inicio |

1. En el panel de acciones, seleccione **Guardar**.

1. Cierre la página Objetivo de ventas trimestral.

1. Cierre la página Objetivos | Bill.

### <a name="assign-learning-course-to-the-new-hire"></a>Asignar cursos de aprendizaje a la nueva contratación

1. En la página Empleados de Bill, en el panel de acciones, seleccione **Trabajador**.

1. En la pestaña **COMPETENCIAS**, seleccione **Cursos**.

1. Es posible que deba desplazarse hacia la derecha para ver la pestaña.

1. En el panel de acciones, seleccione **+Nuevo** para crear un nuevo curso.

1. En la vista de cuadrícula, en la columna **Id. del curso** seleccione el menú y luego **00004**.

1. En el cuadro de diálogo de **Transferir los datos del curso**, seleccione **Sí**.

1. En la columna **Fecha de inicio**, seleccione el icono del calendario y luego la fecha de hoy.

1. En la columna **Fecha final**, seleccione el icono del calendario y una fecha a dos semanas de hoy.

1. En el panel de acciones, seleccione **Guardar**.

1. Cierre la página Cursos | Bill.

### <a name="create-an-expense-report"></a>Crear un informe de gastos

1. En el panel de navegación, seleccione **Módulos** > **Recursos humanos** > **Áreas de trabajo** > **Autoservicio para empleados**.

1. En la sección **Mi carrera profesional**, en el icono **Gastos**, seleccione **Nuevo informe**.

1. En el panel **Nuevo informe de gastos**, seleccione el menú **Propósito**, **Aprendizaje** y luego **Aceptar**.

1. En la cuadrícula **Gastos**, en la línea de gastos nueva, especifique las siguientes actualizaciones:

    | **Configuración** | **Valor** |
    | :--- | :---- |
    | Fecha de transacción | Seleccionar la fecha de hoy |
    | Categoría de gastos | Alquiler de vehículo |
    | Comerciante | LitWare Travel |
    | Importe de la transacción | 150.00 |

1. Con la máquina virtual del laboratorio, abra el **Bloc de notas**.

1. En el cuerpo del bloc de notas, escriba **recibo de LitWare Travel**.

1. Guarde el archivo en el escritorio como **Recibo.txt** y luego cierre el bloc de notas.

1. Utilizará este archivo para representar un recibo que se adjuntará a un informe de gastos.

1. Vuelva a la pestaña del explorador de Microsoft Dynamics 365 Finance & Operations.

1. En el panel de acciones, seleccione **Recibos de encabezado**.

1. En el panel **Recibos de encabezado**, seleccione **Cargar y adjuntar nuevo recibo**.

1. Haga clic en **Examinar**.

1. Seleccione el archivo **Recibo.txt** que creó antes y, luego, **Abrir**.

1. En el cuadro **Notas**, especifique **Alquiler de vehículo** y luego seleccione **Cargar**.

1. Seleccione el cuadro **Recibo** y seleccione **Seleccionar líneas**.

1. En el panel **Adjuntar recibos a líneas**, seleccione el cuadro **150,00 LitWare Travel** y luego **Aceptar**.

1. Seleccione **Close** (Cerrar).

1. En el panel de acciones, seleccione **Flujo de trabajo** y luego **Enviar**.

1. En el panel **Informe de gastos - USMF - Enviar**, en el cuadro **Comentarios**, especifique **Revisar mi informe de gastos**.

1. Seleccione **Submit** (Enviar).

### <a name="record-performance-journal"></a>Registrar diario de desempeño

1. En el panel de navegación, seleccione **Módulos** > **Recursos humanos** > **Rendimiento** > **Diario de desempeño**.

1. En el panel de acciones, seleccione **+Nuevo**.

1. En la página **Nuevo diario**, escriba las siguientes actualizaciones.


    | **Configuración** | **Valor** |
    | :--- | :---- |
    | Título | Aprendizaje al que asistió |
    | Descripción | Completó aprendizaje empresarial para ser administrador de tienda |
    | Person | Bill Smith |
    | Fecha de finalización | La fecha de hoy |

1. En el panel de acciones, seleccione **Guardar**.

1. En el panel de acciones, seleccione **Agregar a objetivo**.

1. Seleccione **Objetivo de ventas trimestral** y, después, seleccione **Aceptar**.

1. Cierre la página Diario de desempeño.
