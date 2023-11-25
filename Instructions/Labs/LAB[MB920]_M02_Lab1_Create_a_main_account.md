---
lab:
  title: "Laboratorio\_1: Creación de una cuenta principal"
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Módulo 2: Obtener información sobre los fundamentos de Microsoft Dynamics 365 Finance

## Laboratorio 1: Creación de una cuenta principal

## Configuración del laboratorio

   - **Tiempo estimado**: 5 minutos

## Instrucciones


1.  En la página de **inicio de Finance and Operations**, en la parte superior derecha, compruebe que esté trabajando con la empresa **USMF**.

2.  Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**.
3.  En el panel de navegación izquierdo, seleccione **Módulos > Contabilidad general > Calendarios > Calendarios fiscales**.
4.  Seleccione Calendario **fiscal**
5.  Si el año natural actual ya está creado, salga de la página **Calendarios fiscales**.
6. Si el año natural actual no está creado, seleccione el botón **Nuevo año** en el panel de acciones y escriba el año actual como se muestra en la captura de pantalla siguiente. Seleccione el **botón Crear** para crear el calendario del año actual.

![En la captura de pantalla se muestra cómo crear el año nuevo en el calendario fiscal](./media/lab-create-a-main-account-04.png)


4.  En el panel de navegación izquierdo, seleccione **Módulos** > **Contabilidad general** > **Plan de cuentas** > **Cuentas** > **Cuentas principales**.

5.  En el panel de acciones, seleccione **+ Nuevo**.

6.  Escriba estos valores en la página **Cuenta principal**:

    - Cuenta principal: **601510**

    - Nombre: **Gasto en llamadas internacionales**

    - Tipo de cuenta principal: **Gasto**

    - Categoría de cuenta principal: **TANDEEXP**

    - Valor predet. Debe/Haber: **Debe**

    ![Captura de pantalla que muestra la página de cuentas principales: compartido donde se deben agregar valores diferentes.](./media/lab-create-a-main-account-01.png)

7.  Vaya a **Módulos &gt; Contabilidad general &gt; Entradas del diario &gt; Diarios generales.**

8.  En el panel de acciones, seleccione **+ Nuevo**.

9.  Escriba el siguiente valor en la página **Diarios generales** y seleccione **Líneas** en el panel de acciones:

    - Nombre: GenJrn

10.  Escriba los valores siguientes en la página **Vale del diario**:

    - Tipo de cuenta: **Libro de contabilidad**

    - Cuenta principal: **601510**

    - Débito: **10,00** 

    - Tipo de cuenta de compensación: **Libro de contabilidad**

    - Número de cuenta de compensación: **110180** 

11. Seleccione el botón **Guardar** en el panel de acciones.

12. Seleccione **Validar &gt; Simular publicación**. 

13. Seleccione el botón **Publicar** en el panel de acciones. El diario debería publicarse.
