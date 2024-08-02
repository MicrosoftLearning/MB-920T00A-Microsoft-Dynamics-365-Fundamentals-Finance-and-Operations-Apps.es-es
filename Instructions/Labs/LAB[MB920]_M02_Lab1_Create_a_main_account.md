---
lab:
  title: "Laboratorio\_2.1: Creación de una cuenta principal"
  module: 'Learning Path 2: Learn the fundamentals of Microsoft Dynamics 365 Finance'
---

# Ruta de aprendizaje 2: Aspectos básicos de Microsoft Dynamics 365 Finance
# Módulo 2: descripción de los libros de contabilidad general en Finance

## Laboratorio 2.1: Creación de una cuenta principal

## Configuración del laboratorio

   - **Tiempo estimado**: 5 minutos

## Objetivo

En este laboratorio, harás las siguientes actividades:

1. Crear una entidad jurídica.

2. Crear un calendario fiscal.

3. Crear un plan de cuentas.

4. Crear cuentas principales en el plan de cuentas.

5. Crear una unidad operativa de tipo de departamento y centro de costes.

6. Crear una estructura contable mediante las cuentas principales y los centros de costes.

7. Configuración del libro de mayor.

# Pasos de laboratorio

## Crear una entidad jurídica

1. En el panel de navegación izquierdo de Dynamics 365 Finance, selecciona **Módulos****&gt;****Administración de la organización****&gt; Organizaciones &gt; Entidades jurídicas**.

2. En la página **Entidades jurídicas**, selecciona el botón **Nuevo** en el panel de acciones para crear una nueva entidad jurídica y escribe la siguiente información:

    - Nombre: **Contoso Demo Systems**

    - Empresa: **CDS**

    - País/región: **EE. UU.**

3. Selecciona **Aceptar** en la parte inferior.

## Crear un calendario fiscal

1. En el panel de navegación izquierdo de Dynamics 365 Finance, selecciona **Módulos****&gt;**** Contabilidad general****&gt; Calendarios &gt; Calendarios fiscales**. 

2. En la página **Calendario fiscal**, selecciona el botón **Nuevo calendario** en el panel de acciones para crear un nuevo calendario fiscal y escribe la siguiente información:

    - Calendario: **CDS**

    - Descripción: **Calendario de Demo Systems**

    - Inicio del ejercicio: **1/10/2023**

    - Fin del ejercicio: **30/9/2023**

    - Nombre del ejercicio: **2023-24**

    - Longitud del período: **1**

    - Unidad: **Meses**

3. Selecciona el botón **Crear**.

El sistema generará 14 períodos, incluyendo una apertura y un período de cierre y 12 períodos durante 12 meses.

## Crear un plan de cuentas

1. En el panel de navegación izquierdo de Dynamics 365 Finance, selecciona **Módulos** > **Contabilidad general****&gt;****Plan de cuentas****&gt; Cuentas &gt; Plan de cuentas**.

2. En la página **Plan de cuentas**, selecciona el botón **Nuevo** en el panel de acciones para crear un nuevo plan de cuentas y escribe la siguiente información:

    - **Planes de cuentas**: Demo systems

    - **Descripción**: Contoso Demo Systems

3. Selecciona el botón **Nuevo** en la ficha desplegable **Cuentas principales** para crear cuentas principales con los valores siguientes:

    - Cuenta principal: **1000**

    - Nombre: **Cash**

    - Tipo de gasto principal: **Balance**

    - Categoría de cuenta principal: **CASH**

    - Valor predet. Debe/Haber: **Debe**

4. Crea otra cuenta principal:

    - Cuenta principal: **3000**

    - Nombre: **Revenue**

    - Tipo de gasto principal: **Ingresos**

    - Categoría de cuenta principal: **REV**

    - Valor predet. Debe/Haber: **Haber**

5. Crea otra cuenta principal:

    - Cuenta principal: **6000**

    - Nombre: **Gastos de viaje**

    - Tipo de gasto principal: **Expense**

    - Categoría de cuenta principal: **EXP**

    - Valor predet. Debe/Haber: **Debe**

##  Crear una unidad operativa

1. Ve a **Módulos** **&gt;** **Administración de la organización****&gt; Organizaciones &gt; Unidades operativas**.

2. En el panel de acciones, selecciona el botón **Nuevo** seguido del tipo de unidad **operativa Departamento** y escribe el siguiente valor:

    - Nombre: **CDS_Training**

3. En el panel de acciones, selecciona el botón Nuevo seguido del tipo de unidad operativa Centro de costes y escribe el siguiente valor:

    - Nombre: **CDS_Purchase**

4. Agregua dos centros de costes más: **CDS_IT** y **CDS_Admin**.

## Crear una estructura de contabilidad

1. En la página de **inicio de Finance and Operations**, en la parte superior derecha, comprueba que estés trabajando con la empresa **CDS**.

2. Si es necesario, selecciona la empresa y, en el menú, selecciona **CDS**.

3. En el panel de navegación izquierdo de Dynamics 365 Finance, selecciona **Módulos** > **Contabilidad general****&gt;****Plan de cuentas &gt; Estructuras &gt; Configurar estructuras contables**.

4. En el panel de acciones, selecciona el botón **Nuevo** para crear una nueva estructura contable con los siguientes valores:

    - Estructura contable: **CDS_BS**

    - Descripción: **Balance de CDS**

    - Agregar cuenta principal: **SÍ**

5. Selecciona el botón **Crear**.

6. En la ficha desplegable **Segmentos y valores permitidos**, selecciona el botón **Agregar** para agregar el **intervalo de cuentas principal 1000..2999**.

7. Selecciona el botón **Activar** en el panel de acciones seguido del botón **Activar** en el cuadro de diálogo de procesamiento por lotes.

8. En el panel de acciones de la página **Estructuras contables**, selecciona el botón **Nuevo** para crear otra estructura contable con los valores siguientes:

    - Estructura contable: **CDS_Revenue**

    - Descripción: **Ingresos de CDS**

    - Agregar cuenta principal: **SÍ**

9. Selecciona el botón **Crear**.

10. En la ficha desplegable **Segmentos y valores permitidos**, selecciona el botón **Agregar** para agregar el **intervalo de cuentas principales 3000..5999**.

11. Selecciona el botón **Activar** en el panel de acciones seguido del botón **Activar** en el cuadro de diálogo de procesamiento por lotes.

12. En el panel de acciones de la página **Estructuras contables**, selecciona el botón **Nuevo** para crear otra estructura contable con los valores siguientes:

    - Estructura contable: **CDS_Expense**

    - Descripción: **Gastos de CDS**

    - Agregar cuenta principal: **SÍ**

13. Selecciona el botón **Crear**.

14. En la ficha desplegable **Segmentos y valores permitidos**, selecciona el botón **Agregar** para agregar el **intervalo de cuentas principales 6000..9999**.

15. Selecciona el botón **Segmento** en la ficha desplegable **Segmentos y valores permitidos**.

16. En el cuadro de diálogo **Agregar segmento**, selecciona **CostCenter** seguido del botón **Agregar segmento**.

17. En el campo **CostCenter**, escribe **253..255**. 

18. Selecciona el botón **Activar** en el panel de acciones seguido del botón **Activar** en el cuadro de diálogo de procesamiento por lotes.

## Configuración del libro de contabilidad

1. En la página de **inicio de Finance and Operations**, en la parte superior derecha, comprueba que estés trabajando con la empresa **CDS**.

2. Si es necesario, selecciona la empresa y, en el menú, selecciona **CDS**.

3. En el panel de navegación izquierdo de Dynamics 365 Finance, selecciona la página **Módulos** > **Contabilidad general &gt; Configuración &gt; Libro de contabilidad** y configura lo siguiente:

    - Plan de cuentas: **Demo Systems**

    - Calendario fiscal: **CDS**

    - Divisa de contabilidad: **USD**

    - Divisa de notificación: **USD**

    - Tipo de tipo de cambio de divisa de contabilidad: **valor predeterminado**

    - Tipo de tipo de cambio de presupuesto: **Presupuesto**

4. En la ficha desplegable **Estructura contable**, selecciona el botón **Agregar** para agregar la estructura contable **CDS_BS**.

5. Agrega dos estructuras contables más: **CDS_Revenue** y **CDS_Expense**.

Esto completa la configuración básica del módulo de contabilidad general. Ahora puedes planear la configuración del diario para contabilizar los diarios. 

 
