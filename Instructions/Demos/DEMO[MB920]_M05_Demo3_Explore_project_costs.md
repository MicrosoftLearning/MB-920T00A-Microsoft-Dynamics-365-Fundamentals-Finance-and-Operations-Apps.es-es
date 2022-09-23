---
demo:
  title: 'Demostración 3: Explorar los costes del proyecto'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>Demo 3: Explorar los costes del proyecto

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. En **Dynamics 365 for Finance and Operations**, en el panel de navegación, seleccione **Módulos > Gestión de proyectos y contabilidad > Hojas de horas > Mis hojas de horas (optimizadas para móvil)** .  
    Para empezar, aunque en este momento no estoy en un dispositivo móvil, reconocerá los formularios como diseñados para móviles después de que seleccionemos la opción **Mis hojas de horas (optimizadas para móvil)** .

    ![Captura de pantalla del menú de gestión de proyectos y contabilidad con mis hojas de horas (optimizadas para móvil) resaltadas.](./media/projops_costs_1_select_my_timesheets.png)  

    Esta optimización es un factor diferenciador clave para Microsoft Business Applications y ayuda a garantizar que haya una curva de aprendizaje mínima entre el uso en la web y en dispositivos móviles.

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. En la página **Mis hojas de horas**, seleccione **Nueva**.  
    Ahora crearemos una nueva hoja de horas que se basará en los ajustes configurados.

1. En el panel **Nueva hoja de horas**, señale el cuadro **Fecha**.  
    La fecha especificada determinará el periodo de la hoja de horas.

1. Señale **Crear desde favoritos**.  
    Si ha guardado favoritos, puede seleccionar crear desde favoritos para ahorrar tiempo.

1. Cuando haya terminado, seleccione **Aceptar**.

1. En la página **Detalles de mis hojas de horas**, seleccione el icono **Nueva +** .

1. En el **panel Nueva línea de hoja de horas**, señale el cuadro **Entidad jurídica**.  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. Seleccione el menú **Id. de proyecto**.

1. Seleccione uno de los proyectos disponibles, como el proyecto **Contoso Consulting**.

1. Cuando haya terminado, seleccione **Aceptar**.  
    Se abrirá la pantalla optimizada para móvil para la entrada de tiempo y podrá empezar a reservar sus horas cada día para el proyecto y la categoría, en este caso **Servicio**.

1. En la página **Entrada de tiempo**, en el cuadro **Lun**, escriba **8**.  
    Esto representa la entrada de las horas de un solo día.

    ![Captura de pantalla de la página Entrada de tiempo.](./media/projops_costs_2_mon_box.png)

1. En esta demo, veremos la creación de una entrada de tiempo y gastos que se cargará al proyecto Contoso Consulting.  
    También puede escribir comentarios internos y externos sobre el proyecto para asegurarse de que todas las partes comprenden la naturaleza de las horas registradas.

1. Exploraremos las entradas en formatos optimizados para su presentación en la web y en dispositivos móviles, y veremos cómo se utiliza un flujo de trabajo para administrar el proceso de aprobación.

1. En la barra de navegación, seleccione **Guardar**.

1. En el menú de navegación de la izquierda, en **Hojas de horas**, seleccione **Mis hojas de horas**.

1. En la página **Mis hojas de horas**, seleccione la entrada de tiempo que creó anteriormente.

1. En la pestaña **Hoja de horas**, señale la columna Categoría.  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. En **Detalles de línea**, señale **Comentario interno** y **Comentario externo**.  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. En la barra de navegación, seleccione la pestaña **Flujo de trabajo**.  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. En el panel **Revisar flujo de trabajo de hoja de horas**, seleccione **Enviar**.

1. En el panel **Revisar flujo de trabajo de hoja de horas – Enviar**, agregue comentarios adicionales.

1. Seleccione **Submit** (Enviar).

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. En la página **Transacciones por horas**, revise la página.  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

Posteriormente, podemos explorar en profundidad las Transacciones de asiento.

1. En la barra de navegación, seleccione **Asiento**.

1. En la página **Transacciones de asiento**, señale las secciones **Cuenta contable** y **Nombre de cuenta**.  
    En estas secciones podemos ver el impacto en la contabilidad general, así como las cuentas que se utilizarán.  

Ahora, creemos una entrada de gastos para el mismo proyecto Contoso Consulting.

1. En el panel de navegación, seleccione **Módulos > Administración de gastos > Mis gastos > Informes de gastos**.

1. En la página **Administración de gastos**, en la pestaña **Informes**, seleccione **+ Nuevo informe de gastos**.

1. En el selector de empresas de la parte superior derecha, compruebe que la entidad jurídica a la que se está conectando es **USSI**.

1. Seleccione **Aceptar**.

1. En la página **Gastos**, seleccione **+ Nuevo gasto**.  
Aparecerá una nueva línea de gasto.

1. En la columna **Categoría de gasto**, seleccione **Combustible** en el menú desplegable **Categoría**.  
Aquí podemos escribir el nuevo gasto con detalles sobre el mismo.

1. En la columna **Importe de transacción**, escriba **25,00**.

1. En la columna **Divisa**, seleccione **USD**.

1. Si no es así, cambie la entidad jurídica a **USSI**.  
    Una vez que haya escrito todos los detalles, puede guardar el gasto.

1. Seleccione **Guardar**.

1. En el menú de navegación de la izquierda, en **Áreas de trabajo**, seleccione **Administración de gastos**.

1. En la página **Administración de gastos**, seleccione el informe de gastos que acaba de crear.

1. En la página **Informe de gastos**, seleccione el cuadro **Id. del proyecto** y luego seleccione **00000093 Contoso Consulting**.  

Después, podemos indicar que el combustible se cobrará en el proyecto Contoso Consulting, así como información adicional sobre el gasto.

1. Señale el cuadro **Información adicional**.

1. En la parte inferior derecha de la pantalla, seleccione **Guardar y continuar**.

1. En la parte derecha de la pantalla, seleccione **Enviar**.

1. En el cuadro **Comentario**, agregue cualquier comentario adicional.

1. Seleccione **Submit** (Enviar).

1. En la página **Administración de gastos**, señale la columna **Estado de aprobación**.  
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
