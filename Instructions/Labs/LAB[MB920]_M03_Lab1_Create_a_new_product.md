---
lab:
  title: 'Laboratorio 1: Crear un producto nuevo'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Módulo 3: Obtener información sobre los fundamentos de Microsoft Dynamics 365 Supply Chain Management

## Laboratorio 1: Crear un producto nuevo

## Objetivo

En Contoso Entertainment System USA (USMF), debe crear un nuevo artículo para una nueva configuración de armario que se comprará a los proveedores. 

## Configuración del laboratorio

   - **Tiempo estimado**: 10 minutos

## Instrucciones

1.  En la **página de inicio de Finance and Operations**, en la parte superior derecha, compruebe que esté trabajando con la empresa **USMF**. 

1.  Si es necesario, seleccione la empresa y, en el menú, seleccione **USMF**.

1.  En la esquina superior izquierda, seleccione el menú de hamburguesa **Expandir el panel de navegación**. 

1.  En el panel de navegación, en el módulo **Gestión de información de productos**, seleccione **Productos** > **Productos liberados**. 

1.  En la página **Detalles de producto liberado**, en el panel de acciones, seleccione  **+ Nuevo**. 

1.  En el panel **Nuevo producto liberado**, en el menú  **Tipo de producto** , compruebe que está seleccionado **Artículo**. 

1.  En el campo  **Subtipo de producto** , compruebe que **Producto** está seleccionado. 

1.  Seleccione el menú  **Grupo de dimensiones de seguimiento**  y escriba o seleccione  `None`. 

1.  En **IDENTIFICACIÓN**, para el **Número de producto**, escriba  `GTL007`.

1.  En el cuadro **Nombre del producto** , escriba `Cabinet 2`.

1.  En **GRUPOS DE REFERENCIA**, en el campo **Grupo de modelo de artículo** , introduzca o seleccione `FIFO`, Primero en caducar primero en salir (FIFO). 

1.  En el campo **Grupo de artículos**, escriba o seleccione  `TV&Video`. 

1.  En **Grupo de dimensiones de almacenamiento**, escriba o seleccione  `SiteWH`. 

1.  En **UNIDADES DE MEDIDAS**, compruebe que se establezcan los siguientes valores: 

    | **Configuración**    | **Valor** |
    | :------------- | :-------- |
    | Unidad de inventario | ud. (cada una)   |
    | Unidad de compra  | ud. (cada una)   |
    | Unidad de ventas     | ud. (cada una)   |
    | Unidad de L. MAT       | ud. (cada una)   |

1.  En **IMPUESTOS DE VENTAS**, en **Grupo de impuestos sobre ventas del artículo** , escriba o seleccione  `ALL`. 

1.  En **IMPUESTOS DE COMPRA**, en **Grupo de impuestos sobre ventas del artículo**, escriba o seleccione  `ALL`. 

1.  En **PRECIOS**, en el cuadro **Precio de compra** , escriba  `30.00`.

1.  En el campo **Precio de ventas** , escriba  `30.00`.

1.  Compruebe que el nuevo **producto liberado** tiene el siguiente aspecto: 

    ![Imagen de pantalla que muestra el formulario completado de nuevo producto liberado](./media/lp1-m2-new-release-product.png)

1.  Seleccione  **Aceptar**. 

1.  Para asegurarse de que el producto está finalizado, en el panel de acciones, en **Mantener**, seleccione la acción **Validar**. 

    ![Imagen de pantalla que muestra la barra de la cinta con Validar resaltado](./media/lp1-m2-validate-ribbon-bar.png)

1.  Compruebe que se le presenta la notificación que confirma que todos los valores de campo obligatorios se validaron. 

    ![Imagen de pantalla de la notificación de información de que todos los campos obligatorios se han validado](./media/lp1-m2-confirmation-of-validation.png)

1.  Seleccione **Guardar**, **cierre** todas las páginas y vuelva a la página principal. 

