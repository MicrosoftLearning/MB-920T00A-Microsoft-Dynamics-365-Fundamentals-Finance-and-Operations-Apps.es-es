---
lab:
  title: 'Laboratorio 3.1: Crear un producto nuevo'
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Ruta de aprendizaje 3: Aspectos básicos de Microsoft Dynamics 365 Supply Chain Management
# ódulo 2: descripción de los procesos de ventas y adquisiciones

## Laboratorio 3.1: Crear un producto nuevo

En tu organización, tienes previsto crear un nuevo artículo, una camisa. La camisa tendrá diferentes colores y tamaños. En este laboratorio, aprenderás a crear un nuevo artículo con varias variantes y registrarlo en la entidad jurídica USMF.

## Pasos de laboratorio

1. En el panel de navegación de Dynamics 365 Supply Chain Management, selecciona **Módulos** y luego selecciona **Gestión de información de productos** > **Configuración** > **Grupos de variantes y dimensiones**. Abre la página **Grupos de colores** y crea un nuevo registro.

    - Grupo de colores: **ShirtColor**

    - Descripción: **Color de la camisa**

2. En la ficha desplegable **Líneas de grupo de colores**, escribe los tres registros siguientes:

| **Color**| **Nombre del color** |
| - |
| Azul| Azul |
| Blanco| Blanco |
| Negro| Negro |

3. Guarde los registros.

4. Selecciona **Gestión de información de productos** > **Configuración** > **Grupos de variantes y dimensiones**. Abre la página **Grupos de tamaños** y crea un nuevo registro.

    - Grupo de tamaños: **ShirtSize**

    - Descripción: **Tamaño de la camisa**

5. En la ficha desplegable **Líneas de grupo de tamaños**, escribe los tres registros siguientes.

| **Tamaño**| **Nombre del tamaño** |
| - |
| S| Pequeño |
| M| Mediano |
| L| Grande |

6. Guarda los registros

7. En el panel de navegación de Dynamics 365 Supply Chain Management, selecciona **Módulos** y luego selecciona **Gestión de información de productos**. Luego, en el menú **Productos**, selecciona **Productos maestros**.

8. En la página **Productos maestros**, en el menú superior, selecciona **+ Nuevo**.

9. En la página **Nuevo producto**, en el campo **Tipo de producto**, comprueba que está seleccionado **Artículo**.

10. En el campo **Subtipo de producto**, comprueba que **Productos** **maestros** está seleccionado.

11. En la pestaña **Identificación**, en el cuadro **Número de producto**, escribe **SH001**.

12. En el campo **Nombre de producto**, escribe **Camista**.

13. En el campo **Grupo de dimensiones de producto**, selecciona **ColorSize**.

14. Selecciona el botón **Aceptar**.

15. En el menú **Producto** del panel de acciones, selecciona **Grupos de dimensiones** en **Configurar** grupo.

16. En la lista desplegable **Grupo de dimensiones de almacenamiento** selecciona **SiteWH**.

17. En la lista desplegable **Grupo de dimensiones de seguimiento** selecciona **Ninguno**.

18. Selecciona el botón **Aceptar**.

19. Selecciona **ShirtColor** en la lista **Grupo de colores**.

20. Selecciona **ShirtSize** en la lista **Grupo de tamaños**.

21. En el panel de acciones, selecciona **Variantes del producto**.

22. En el panel de acciones, en la pestaña **Variante del producto**, selecciona **Sugerencias de variantes**.

23. Selecciona el botón **Sugerir todo** en la página **Sugerencias de variantes**.

24. Selecciona las variantes sugeridas seleccionando el botón **Seleccionar todo** seguido del botón **Crear**.

Las variantes se crearán en la página Variantes del producto.

25. Selecciona el botón **Emitir productos** en el panel de acciones para emitir el producto en una persona jurídica.

26. Se abre una página que muestra el primer paso como **Seleccionar productos para liberar**.

27. Selecciona el botón **Siguiente** situado en la parte inferior de la página.

28. Selecciona las variantes que deseas emitir en la entidad jurídica y selecciona el botón **Siguiente**.

29. En la página **Seleccionar empresas para las que liberar**, selecciona la entidad jurídica **USMF** donde se debe liberar el producto.

30. Selecciona el botón **Siguiente** situado en la parte inferior de la página.

31. En la página **Confirmar selección**, establece el valor de **Mostrar el registro de información tras un error** en **Sí** y **Ejecutar como lote** en **No**.

32. Selecciona el botón **Finalizar** ubicado en la parte inferior de la página.

16. En el panel de navegación, selecciona **Módulos** y luego **Gestión de información de productos**. Luego, en el menú **Productos**, selecciona **Productos emitidos**.

33. En la página **Productos emitidos**, busca el nuevo artículo **SH001** en la cuadrícula.

34. Selecciona el vínculo del producto y ve a la página **Detalles del producto**.

35. En la ficha desplegable **General**, especifica lo siguiente:

    - Grupo de modelos de artículo: **FIFO**

36. En la ficha desplegable **Comprar**, escribe lo siguiente:

    - Unidad: **ea**

    - Grupo de impuestos de artículos: **TODOS**

    - Precio: **30**

37. En la ficha desplegable **Vender**, especifica lo siguiente:

    - Unidad: **ea**

    - Grupo de impuestos de artículos: **TODOS**

    - Precio: **35**

38. En la ficha desplegable **Administrar inventario**, escribe lo siguiente:

    - Unidad: **ea**

39. En la ficha desplegable **Ingeniero**, escribe lo siguiente:

    - Unidad BOM: **ea**

40. En la ficha desplegable **Administrar costes**, escribe lo siguiente:

    - Grupo de artículos: **audio**

41. Para completar la configuración, selecciona **Producto** en el panel de acciones. Selecciona el botón **Validar** en el grupo **Mantener**.

42. Cierra todas las páginas y vuelve a la página de **inicio**.

 
