---
lab:
  title: "Laboratorio\_2: Integración con Excel"
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# Módulo 1: Exploración de las capacidades principales de las aplicaciones de finanzas y operaciones de Dynamics 365

## Laboratorio 2: Integración con Excel

## Objetivo

En este laboratorio, aprenderá a copiar datos de finanzas y operaciones a Excel mediante la aplicación de complemento de Office Dynamics Data Connector. También aprenderá cómo se puede usar la misma aplicación para insertar datos en Dynamics 365 Finance and Operations. 

## Configuración del laboratorio

   - **Tiempo estimado**: 5 minutos

## Instrucciones

Ahora que ya estamos familiarizados con las aplicaciones de Finance and Operations, vamos a dedicar algo de tiempo a explorar el escenario de integración con Excel. 

1.  En la **página de inicio de Finance and Operations**, en la parte superior derecha, compruebe que esté trabajando con la empresa **USMF**. 

2.  Vaya a **Adquisición y abastecimiento** > **Configuración** > **Proveedores** > **Grupos de proveedores**.

3.  En el panel de acciones, seleccione **Abrir en Microsoft Office** y, en **Abrir en Excel**, seleccione **Grupos de proveedores (usmf)** .

4.  En el panel **Abrir en Excel** , seleccione **Descargar**. 

5.  El archivo de plantilla de Excel se descargará y guardará. **Abra** el archivo de plantilla de Excel descargado, omita o permita otros avisos de seguridad estándar si es necesario, cierre la activación y seleccione **Habilitar edición**. Seleccione **Confiar en este complemento** y, a continuación, inicie sesión (utilizando sus mismas credenciales, si se le solicita). 

    Una vez iniciada la sesión, la aplicación Data Connector actualiza los datos existentes de la tabla **Grupo de proveedores** y los muestra en la hoja de cálculo Excel. 

6.  Para crear un nuevo registro, escriba `100` en el campo **Grupo de proveedores**, `Insurance vendor` en el campo **Descripción** y `Net10` en el campo **Condiciones de pago**. 

7.  Seleccione el botón **Publicar** en el panel de tareas de Microsoft Dynamics Data Connector. 

8.  Actualice la lista **Grupos de proveedores** en Dynamics 365 Finance and Operations para comprobar que el nuevo registro se ha agregado correctamente. 

