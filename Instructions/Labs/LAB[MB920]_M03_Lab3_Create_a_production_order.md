---
lab:
  title: "Laboratorio\_3.2: Creación de una orden de producción"
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Ruta de aprendizaje 3: Aspectos básicos de Microsoft Dynamics 365 Supply Chain Management
# Módulo 4: descripción del proceso de fabricación

## Laboratorio 3.2: Creación de una orden de producción

## Objetivo

Los pedidos de producción ayudan a iniciar el proceso de producción en Supply Chain Management. En esta práctica de laboratorio, te familiarizarás con la interfaz de usuario y la funcionalidad del formulario de orden de producción. Además, aprenderás a crear y procesar una orden de producción al final del ejercicio.

## Pasos de laboratorio

1. En la parte superior derecha de la página de inicio de Dynamics 365 **Supply Chain Management**, comprueba que estás trabajando con la empresa **USMF**.

2. Si es necesario, selecciona la empresa y, en el menú, seleccione **USMF**.

3. En el panel de navegación izquierdo, selecciona **Módulos** > **Control de producción** > **Pedidos de producción** > **Todos los pedidos de producción**.

4. En el menú superior, selecciona **Nueva orden de producción** y escribe los siguientes datos.

    - Número de artículo: **D0002**

    - Cantidad: **10**

    - Sitio: **1**

    - Almacén: **11**

    - Entrega: [selecciona una fecha un mes después de la fecha de hoy]

    - Número de BOM: **D0002BOM**

    - Número de ruta: **000004**

5. Selecciona el botón **Crear**.

Se crea una nueva orden de producción para 10 cantidades del artículo D0002.

6. Selecciona **Orden de producción (menú del panel de acciones) &gt; Proceso &gt; Estimación.**

7. En el cuadro de diálogo **Estimación**, selecciona **Estándar** en el campo **Margen**, selecciona el **campo Referencias** y selecciona el botón **Aceptar**.

El **estado** de la orden de producción cambiará a **Estimado**.

8. Selecciona **Programación (menú del panel de acciones) &gt; Orden de producción &gt; Programar operaciones.**

9. En el cuadro de diálogo **Programación de operaciones**, selecciona **Remitir a partir de hoy** en el campo **Dirección programación** y selecciona el botón **Aceptar**.

10. Selecciona **Ver (menú del panel de acciones) &gt; Información relacionada &gt; Reserva de capacidad**.

11. Comprueba los nuevos registros creados en la página **Reserva de capacidad**.

12. Vuelve a la página **Todas las órdenes de producción**. Ten en cuenta que el **estado** de la orden de producción cambia a **Programado**.

13. Selecciona **Orden de producción (menú del panel de acciones) &gt; Procesar &gt; Liberar**.

14. En el cuadro de diálogo **Liberar**, selecciona el **campo Referencias** y selecciona el botón **Aceptar**.

15. El **estado** de la orden de producción cambiará a **Liberado**.

16. Selecciona **Orden de producción (menú del panel de acciones) &gt; Procesar &gt; Iniciar**.

17. En el cuadro de diálogo **Iniciar**, selecciona la pestaña **General**.

18. Escribe los siguientes detalles en la pestaña **General**.

    - Fecha: **fecha de hoy**

    - Cantidad: **10**

    - Iniciar producción: **SÍ**

    - Registrar ahora la tarjeta de ruta: **NO**

    - Registrar ahora la lista de selección: **NO**

19. Selecciona el botón **Aceptar**.

El **estado** de la orden de producción cambiará a **Iniciado**.

20. Selecciona **Ver (menú del panel de acciones) &gt; Diarios &gt; Lista de selección**.

Se crea un nuevo diario de lista de selección con tres líneas.

21. Publica el diario de la lista de picking.

22. Vuelve a la página **Todas las órdenes de producción** y selecciona **Ver (menú del panel de acciones) &gt; Diarios &gt; Tarjeta de ruta**.

Se crea un nuevo diario de tarjeta de ruta con tres líneas.

23. Selecciona el campo **Operación completada** en las tres líneas y registra el diario de tarjeta de ruta.

24. Vuelve a la página **Todas las órdenes de producción** y selecciona **Órdenes de producción (menú del panel de acciones) &gt; Procesar &gt; Notificar como terminado**.

25. En el cuadro de diálogo **Notificar como terminado** , escribe **10** en el campo **Cantidad sin errores**. Selecciona el campo **Cierre final** y selecciona **Aceptar**.

El **estado** de la orden de producción cambiará a **Terminado**. El stock del artículo **D0002** aumenta en 10 en el sitio 1 y en el almacén 11.

26. Selecciona **Administrar costes (menú del panel de acciones) &gt; Cálculos &gt; Ver detalles de cálculo**.

Ten en cuenta el coste final del artículo fabricado en la pestaña **Información general de costes**.

 
