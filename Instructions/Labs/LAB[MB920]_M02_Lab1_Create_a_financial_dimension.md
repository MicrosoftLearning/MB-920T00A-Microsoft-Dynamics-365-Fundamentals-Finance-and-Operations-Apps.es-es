---
lab:
    title: 'Laboratorio 1: Crear una dimensión financiera'
    module: 'Módulo 2: Aprender los Fundamentos de Microsoft Dynamics 365 Finance'
---

## Laboratorio 1: Crear una dimensión financiera

## Objetivos

Use la página Dimensiones financieras para crear dimensiones financieras que pueda usar como segmentos de cuenta para planes de cuentas. Existen dos tipos de dimensiones financieras: dimensiones personalizadas y dimensiones respaldadas por entidades. Las dimensiones personalizadas se comparten entre entidades jurídicas y los usuarios especifican y mantienen los valores. Para las dimensiones respaldadas por entidades, los valores se definen en otro lugar del sistema, como en las entidades Clientes o Tiendas. Algunas dimensiones respaldadas por entidades se comparten entre entidades jurídicas, mientras que otras dimensiones respaldadas por entidades son específicas de las empresas.

Debe crear una dimensión financiera personalizada que se utilizará para su empresa.

## Configuración del laboratorio

   - **Tiempo estimado**: 5 minutos

## Instrucciones

1. En la página de inicio de Finance and Operations, en la parte superior derecha, compruebe que esté trabajando con la empresa USMF.

1. Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**.

1. En el panel de navegación izquierdo, seleccione **Módulos** > **Contabilidad general** > **Plan de cuentas** > **Dimensiones** > **Dimensiones financieras**.

1. En el menú superior, seleccione **+ Nuevo**.

1. En la página Dimensiones financieras, seleccione el menú **Usar valores de** y, a continuación, seleccione **< Dimensión personalizada >**.

1. En el cuadro de nombres **Dimensión**, especifique **Affliate_Revenue**.

1. En el cuadro **Nombre de columna de informe**, escriba **Afflt**.

1. En el menú superior, seleccione **Activar**.

    ![Captura de pantalla que muestra la nueva dimensión financiera personalizada con el menú Usar valores de, Nombre de dimensión, Nombre de columna de informe y Activar resaltado](./media/lp2-m3-new-financial-dimension.png)

1. Revise la información en el cuadro de diálogo y luego seleccione **Cerrar**.

1. Revise el banner de notificación de advertencia.

    ![Captura de pantalla que muestra un banner de información de advertencia que hace referencia al requisito del modo de mantenimiento para activar una nueva dimensión.](./media/lp2-m3-activation-warning-banner.png)

    >[!NOTA] El modo de mantenimiento se puede activar y desactivar directamente a través de Lifecycle Services (LCS) en sus entornos de espacio aislado y de producción. Si desea obtener más información sobre la administración de Lifecycle Services, puede consultar: [https://docs.microsoft.com/es-es/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure](https://docs.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure).
