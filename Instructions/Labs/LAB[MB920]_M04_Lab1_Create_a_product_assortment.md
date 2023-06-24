---
lab:
  title: "Laboratorio\_1: Crear un surtido de productos"
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

# Módulo 4: Aprender los fundamentos de Microsoft Dynamics 365 Commerce

## Laboratorio 1: Crear un surtido de productos

## Objetivo

Debe crear un surtido de productos relacionados que se asignen a un canal de comercio específico que estará disponible en una fecha futura. 

## Configuración del laboratorio

   - **Tiempo estimado**: 10 minutos

## Instrucciones

1.  En la **página de inicio de Finance and Operations**, en la parte superior derecha, compruebe que esté trabajando con la empresa **USMF**. 

1.  Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**. 

1.  En el panel de navegación izquierdo, en el módulo **Venta minorista y comercio** , seleccione **Catálogos y surtidos** > **Surtidos**. 

1.  En la página **Surtidos**, seleccione **+ Nuevo**. 

1.  En el formulario **Nuevo registro**, si es necesario, expanda la ficha desplegable **General**. 

1.  Seleccione el cuadro **Fecha de entrada en vigor** y, después, una fecha en el futuro.  

1.  En el cuadro **Nombre de surtido**, escriba un nombre para el nuevo surtido. Por ejemplo: `New Spring Season`

    > **Nota**: la **fecha de expiración** se puede utilizar para desactivar automáticamente un surtido publicado. 

1.  Expanda la ficha desplegable **Canales de comercio**. 

1.  En el menú **Canales de comercio**, seleccione **+ Agregar línea**. 

1.  En el panel **Seleccionar nodos de organización**, para el campo **Jerarquía de organización**, seleccione **Tiendas minoristas por tipo (Fabrikam)** . 

1.  En la lista NODOS ORGANIZATIVOS DISPONIBLES, seleccione En línea y luego el icono agregar ![Icono de flecha derecha](./media/d365-fo-add-org-node-icon.png) para agregarlo a los **NODOS ORGANIZATIVOS SELECCIONADOS**.

    Esto agregará el nodo principal y todos los nodos secundarios. 

1.  Agregue el nodo principal **Correo** y luego seleccione **Aceptar**. 

1.  Compruebe que los dos nodos se han añadido a la pestaña desplegable **Canales de comercio**. 

1.  Expanda la pestaña desplegable **Productos**. 

1.  En la barra de herramientas **Productos**, seleccione **+Agregar línea**. 

1.  En el campo **Categoría**, expanda **Deportes de equipo (deportes de equipo),** y seleccione **Aceptar**.

    De esta manera se agregarán todos los elementos secundarios de la categoría principal.

1.  Revise la última columna llamada **Tipo de línea**. De manera predeterminada, se incluirán todos los elementos.

1.  Seleccione **+ Agregar línea**, el menú **Categoría**, expanda **Deportes de equipo (deportes de equipo)** , **Béisbol** y, a continuación, **Aceptar**. 

1.  Para excluir un artículo de una categoría mayor ya incluida, en este caso Deportes de equipo, en la columna **Tipo de línea**, cambie el valor a `Exclude`. 

1.  Con la fila de categoría Béisbol, seleccione el menú **Productos**. 

1.  Cuando se definen productos de una categoría, puede seleccionar un producto específico para incluirlo o excluirlo. Seleccione **AdultBaseballInfield** o escriba `0013`. 

    > **Nota:** Para eliminar un producto agregado, elimine el contenido del campo **Producto** y luego presione la tecla Tabulador de su teclado o seleccione otra área de la página. 

1.  En el panel de acciones, seleccione **Guardar** y seleccione **Publicar**. 

1.  Seleccione **Yes** (Sí) en el cuadro de diálogo de confirmación. El surtido de productos recién creado estará disponible en la **fecha de entrada en vigor**. 

