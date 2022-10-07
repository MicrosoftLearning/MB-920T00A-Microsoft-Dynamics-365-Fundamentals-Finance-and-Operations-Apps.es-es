---
demo:
  title: 'Demostración 3: Explorar los costes del proyecto'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>Demo 3: Explorar los costes del proyecto

En esta demo, veremos la creación de una entrada de tiempo y gastos que se cargará al proyecto Contoso Consulting. Exploraremos las entradas en formatos optimizados para su presentación en la web y en dispositivos móviles, y veremos cómo se utiliza un flujo de trabajo para administrar el proceso de aprobación.

1. En **Dynamics 365 for Finance and Operations**, en el panel de navegación, seleccione **Módulos > Gestión de proyectos y contabilidad > Hojas de horas > Mis hojas de horas (optimizadas para móvil)** .  
    Para empezar, aunque en este momento no estoy en un dispositivo móvil, reconocerá los formularios como diseñados para móviles después de que seleccionemos la opción **Mis hojas de horas (optimizadas para móvil)** .

    ![Captura de pantalla del menú de gestión de proyectos y contabilidad con mis hojas de horas (optimizadas para móvil) resaltadas.](./media/projops_costs_1_select_my_timesheets.png)  

    Esta optimización es un factor diferenciador clave para Microsoft Business Applications y ayuda a garantizar que haya una curva de aprendizaje mínima entre el uso en la web y en dispositivos móviles.

1. En el selector de empresas de la parte superior derecha, compruebe que la entidad jurídica a la que se está conectando es **USSI**. Si no es así, cambie la entidad jurídica a **USSI**.

1. En la página **Mis hojas de horas**, seleccione **Nueva**.  
    Ahora crearemos una nueva hoja de horas que se basará en los ajustes configurados.

1. En el panel **Nueva hoja de horas**, señale el cuadro **Fecha**.  
    La fecha especificada determinará el periodo de la hoja de horas.

1. Señale **Crear desde favoritos**.  
    Si ha guardado favoritos, puede seleccionar crear desde favoritos para ahorrar tiempo.

1. Cuando haya terminado, seleccione **Aceptar**.

1. En la página **Detalles de mis hojas de horas**, seleccione el icono **Nueva +** .

1. En el **panel Nueva línea de hoja de horas**, señale el cuadro **Entidad jurídica**.  
    Se abrirá la línea de la nueva hoja de horas, con detalles como el cliente, proyecto, categoría, propiedades de la línea y parámetros de impuestos. También puede seleccionar una entidad jurídica diferente si la entrada de tiempo se hace en nombre de otra empresa dentro de su organización

1. Seleccione el menú **Id. de proyecto**.

1. Seleccione uno de los proyectos disponibles, como el proyecto **Contoso Consulting**.

1. Cuando haya terminado, seleccione **Aceptar**.  
    Se abrirá la pantalla optimizada para móvil para la entrada de tiempo y podrá empezar a reservar sus horas cada día para el proyecto y la categoría, en este caso **Servicio**.

1. En la página **Entrada de tiempo**, en el cuadro **Lun**, escriba **8**.  
    Esto representa la entrada de las horas de un solo día.

    ![Captura de pantalla de la página Entrada de tiempo.](./media/projops_costs_2_mon_box.png)

1. En el cuadro **Comentario interno**, agregue un comentario. Por ejemplo: **Puede querer hablarles sobre las nuevas bicicletas**.  
    También puede escribir comentarios internos y externos sobre el proyecto para asegurarse de que todas las partes comprenden la naturaleza de las horas registradas.

1. En el cuadro **Comentario externo**, agregue un comentario. Por ejemplo: **Se ajustaron las cadenas y alinearon las ruedas delanteras en la flota**.

1. En la barra de navegación, seleccione **Guardar**.

1. En el menú de navegación de la izquierda, en **Hojas de horas**, seleccione **Mis hojas de horas**.

1. En la página **Mis hojas de horas**, seleccione la entrada de tiempo que creó anteriormente.

1. En la pestaña **Hoja de horas**, señale la columna Categoría.  
    Ahora supongamos que hemos vuelto a un equipo y estamos revisando nuestro tiempo desde el formulario de hoja de horas de la web. Todavía podemos ver la misma información, como la categoría y las horas.

1. En **Detalles de línea**, señale **Comentario interno** y **Comentario externo**.  
    También podemos revisar los comentario que escribimos anteriormente. La información está ahí, pero el formato de diseño es algo diferente. Este formato se suele utilizar para la revisión final porque puede ser más fácil para las personas revisar y validar su tiempo, especialmente cuando alguien está asignado a varios proyectos o categorías.

1. En la barra de navegación, seleccione la pestaña **Flujo de trabajo**.  
    Si estamos satisfechos con la hoja de horas, podemos enviarla. Las autorizaciones necesarias las determinará cada organización durante la fase de implantación, en función de sus propias directivas empresariales.

1. En el panel **Revisar flujo de trabajo de hoja de horas**, seleccione **Enviar**.

1. En el panel **Revisar flujo de trabajo de hoja de horas – Enviar**, agregue comentarios adicionales.

1. Seleccione **Submit** (Enviar).

1. Vaya a la página **Transacciones por horas**. Si la pestaña **Transacciones por horas** está atenuada, vaya a la **página Mis hojas de horas** y seleccione la hoja de horas creada anteriormente.

1. En la página **Transacciones por horas**, revise la página.  
    Una vez aprobados, los resultados se publicarán y serán visibles en la página Transacciones por horas. Podemos ver toda la información relevante, como la entidad jurídica, el proyecto, la categoría, las horas y, en este caso, incluso una vista del precio de coste y del precio de venta.  

Posteriormente, podemos explorar en profundidad las Transacciones de asiento.

1. En la barra de navegación, seleccione **Asiento**.

1. En la página **Transacciones de asiento**, señale las secciones **Cuenta contable** y **Nombre de cuenta**.  
    En estas secciones podemos ver el impacto en la contabilidad general, así como las cuentas que se utilizarán.  

Ahora, creemos una entrada de gastos para el mismo proyecto Contoso Consulting.

1. En el panel de navegación, seleccione **Módulos > Administración de gastos > Mis gastos > Informes de gastos**.

1. En la página **Administración de gastos**, en la pestaña **Informes**, seleccione **+ Nuevo informe de gastos**.

1. En el panel **Nuevo informe de gastos**, en el **cuadro Propósito**, escriba un título. Por ejemplo, **Contoso – Feb2021**.

1. Seleccione **Aceptar**.

1. En la página **Gastos**, seleccione **+ Nuevo gasto**.  
Aparecerá una nueva línea de gasto.

1. En la columna **Categoría de gasto**, seleccione **Combustible** en el menú desplegable **Categoría**.  
Aquí podemos escribir el nuevo gasto con detalles sobre el mismo.

1. En la columna **Importe de transacción**, escriba **25,00**.

1. En la columna **Divisa**, seleccione **USD**.

1. En la columna **Fecha de transacción**, seleccione una fecha. Por ejemplo, **2/1/2021**.  
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
    En ese momento, se activarán las directivas de viaje y el flujo de aprobación de gastos. Se han publicado y aplicado los costes al proyecto Contoso Consulting y estará disponible más tarde para la facturación, si se puede cobrar.

En esta demo, hemos procesado una entrada de tiempo y gastos que se cargará al proyecto Contoso Consulting. Hemos visto ejemplos en los formato web y móvil, y pudimos comprobar cómo se utilizan los flujos de trabajo para administrar las aprobaciones necesarias por la organización USSI.
