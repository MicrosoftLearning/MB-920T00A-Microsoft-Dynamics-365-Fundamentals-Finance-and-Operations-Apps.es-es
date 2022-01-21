---
lab:
    title: 'Laboratorio 3: Laboratorio de proyecto final de Dynamics 365 Finance'
    module: 'Módulo 2: Aprender los Fundamentos de Microsoft Dynamics 365 Finance'
---

## Laboratorio 3: Laboratorio de proyecto final de Dynamics 365 Finance

## Objetivo

En este laboratorio, explorará las funcionalidades principales de Microsoft Dynamics 365 Finance. Explorará la contabilidad general al crear una nueva entidad, agregar nuevos valores de cuenta y dimensión y al ejecutar un saldo de comprobación. También explorará las cuentas por pagar. Para ello, creará un nuevo proveedor, un pedido de compra y una factura y, luego, liquidará la factura. Al final, explorará las cuentas por cobrar al crear un nuevo cliente, una factura y un informe de vencimiento, y luego al aplicar el pago del cliente.

## Configuración del laboratorio

   - **Tiempo estimado**: 45 minutos

## Ejercicio 1: Explorar la contabilidad general

### Crear una nueva entidad jurídica

1. En el panel de navegación, seleccione **Módulos** > **Administración de la organización** > **Organizaciones** > **Entidades jurídicas**.

1. En el panel de acciones, seleccione **+Nuevo** para crear una nueva entidad jurídica.

1. En el panel **Nueva entidad**, cree una nueva entidad con la siguiente información y luego seleccione **Aceptar**:

    | **Parámetro** | **Valor** |
    | :--- | :--- |
    | Nombre | Contoso Training USA |
    | Empresa | USTR |
    | País/región | EE. UU. |

1. En la página Entidades jurídicas, seleccione la ficha desplegable **Direcciones** y seleccione **Editar**.

1. En el cuadro informativo, escriba las siguientes actualizaciones y, después, seleccione **Aceptar**:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | C.P./Código postal| 98052|
    | Calle| 123 Main Street|
    | Principal para el país/región | Compruebe que está seleccionado **Sí** |

1. Seleccione la ficha desplegable **Información de contacto**.

1. Seleccione **+Agregar** y luego escriba la información de contacto siguiente:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Descripción| Oficina principal|
    | Número/dirección de contacto| 888-555-1234|
    | Principal| Seleccione el cuadro |

1. Seleccione la ficha desplegable **Registro de impuestos**.

1. En el cuadro **Número de registro de impuestos**, escriba **88-1234567**.

1. En el panel de acciones, seleccione **Guardar**.

1. En el panel de navegación, seleccione **Inicio**.

### Crear una nueva cuenta en un plan de cuentas existente

1. En la página de inicio, en la esquina superior derecha, compruebe que se ha seleccionado la empresa **USMF**.  
    De no ser así, seleccione la empresa enumerada actualmente y cambie la empresa a **USMF**.

1. En el panel de navegación, seleccione **Módulos** > **Contabilidad general** > **Plan de cuentas** > **Cuentas** > **Cuentas principales**.

1. En el panel de acciones, seleccione **+Nuevo** para crear una nueva cuenta de ingresos.

1. En la página Cuentas principales, escriba las siguientes actualizaciones:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Cuenta principal| 401500|
    | Nombre| Ingresos por aprendizaje|
    | Tipo de cuenta principal| Ingresos |

1. En el panel de acciones, seleccione **Guardar**.

### Agregar un nuevo valor de dimensión

1. En el panel de navegación, seleccione **Módulos** > **Contabilidad general** > **Plan de cuentas** > **Dimensiones** > **Dimensiones financieras**.

1. En la lista de navegación, seleccione **ServiceLine**.  
    También puede utilizar el cuadro **Filtro** para buscar **ServiceLine**.

1. En el panel de acciones, seleccione **Valores de dimensión**.

1. En el panel de acciones, seleccione **+Nuevo**.

1. En las casillas **Valor de dimensión** y **Descripción**, especifique **Servicios de aprendizaje**.

1. En el panel de acciones, seleccione **Guardar**.

### Utilizar un valor de cuenta y dimensión en un diario general

1. En el panel de navegación, seleccione **Módulos** > **Contabilidad general** > **Entradas de diario** > **Diarios generales**.

1. En el panel de acciones, seleccione **+Nuevo**.

1. En la primera fila de la lista, en la columna **Nombre**, seleccione el menú y luego **Diario general**.

1. En el panel de acciones, seleccione **Líneas**.

1. En la lista, en la columna **Fecha**, seleccione el icono del calendario y luego cambie la fecha al día 1 del mes.

1. En la columna **Cuenta**, seleccione el menú y luego escriba las siguientes actualizaciones:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | MainAccount| 601200|
    | BusinessUnit| 004|
    | Department| 025|
    | CostCenter| 009|
    | ItemGroup| Services|

1. En el cuadro **Descripción**, escriba **Reclasificación de gastos**.

1. En el cuadro **Débito**, escriba **1 000,00**.

1. Desplácese a la derecha y, en la columna **Cuenta de contrapartida**, seleccione el menú y luego escriba las siguientes actualizaciones:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | MainAccount| 602200|
    | BusinessUnit| 004|
    | Department| 025|
    | CostCenter| 009|
    | ItemGroup| Services|

1. En el panel de acciones, seleccione **Guardar**.

1. En el panel de acciones, seleccione **Validar** > **Validar**.  
    Espere a que se complete la validación del diario.

1. Revise el banner de advertencia.  
    Este mensaje de advertencia se puede pasar por alto en este laboratorio.

1. En el panel de acciones, seleccione **Registrar**.

### Ejecutar un saldo de comprobación con un conjunto de dimensiones

1. En el panel de navegación, seleccione **Módulos** > **Contabilidad general** > **Consultas e informes** > **Saldo de comprobación**.

1. En la página Saldo de comprobación, seleccione **Calcular saldos**.

1. El botón **Calcular saldos** está ubicado bajo los ajustes **DATOS QUE INCLUIR**.

1. En la tabla, revise los resultados.

1. En la página Saldo de comprobación, en **Vista estándar**, expanda **Parámetros**.

1. En **DATOS QUE INCLUIR**, seleccione el menú **Conjunto de dimensiones financieras** y seleccione **MA-BU-DEPT-CC**.

1. Seleccione **Calcular saldos** para ver las dimensiones utilizadas en el diario.

1. Cierre la página.

## Ejercicio 2: Explorar proveedores

### Crear un proveedor

1. En el panel de navegación, seleccione **Módulos** > **Cuentas por pagar** > **Proveedores** > **Todos los proveedores**.

1. En el panel de acciones, seleccione **+Nuevo** para crear un proveedor.

1. En la página Nuevo registro, cree un nuevo proveedor con la siguiente información:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Cuenta de proveedor| V00001|
    | Nombre| ABC Training, Inc|
    | Grupo| 20|

1. En el panel de acciones, seleccione **Guardar**.

1. Seleccione la ficha desplegable **Direcciones** y, después, **+Agregar**.

1. En el panel Nueva dirección, escriba las siguientes actualizaciones y, después, seleccione **Aceptar**:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Nombre o descripción| Oficina principal|
    | C.P./Código postal| 98052|
    | Calle| 123 Front Street|

1. En el panel de acciones, seleccione **Guardar**.

1. Seleccione la ficha desplegable **Pago**.

1. Seleccione el menú **Método de pago** y luego **CHEQUE**.

1. Seleccione la ficha desplegable **Impuesto 1099** y especifique las siguientes actualizaciones:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Informe 1099| Sí|
    | Id. de impuestos federales| 82-1234567|
    | Tipo de id. de impuesto| Número de identificación de empresa|
    | Casilla de declaración del IRPF| MISC-03|

1. En el panel de acciones, seleccione **Guardar**.

1. Cierre el formulario.

### Crear un pedido de compra para el nuevo proveedor

1. En V00001: Página ABC Training, Inc, en el panel de acciones, seleccione **Adquisición**.

1. En el panel de acciones, en la pestaña **NUEVO**, seleccione **Pedido de compra**.

1. En la página Pedido de compra, en **Líneas de pedido de compra**, escriba las siguientes actualizaciones:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Número de artículo| S0001|
    | Cantidad| 2|

    >[!NOTA] Es posible que deba desplazarse hacia la derecha para ver la columna **Cantidad**.

1. En el panel de acciones, seleccione **Guardar**.

1. En el panel de acciones, seleccione **Compra** y, en la pestaña **ACCIONES**, seleccione **Confirmar**.

### Registrar la factura del proveedor para el pedido de compra

1. En el panel de acciones, seleccione **Factura**.

1. En la pestaña **GENERAR**, seleccione **Factura**.

1. En el panel de acciones, seleccione **Valor predeterminado de origen: Cantidad de la recepción de producto**.

1. En el menú **Cantidad predeterminada para líneas**, seleccione **Cantidad pedida** y luego seleccione **Aceptar**.

1. En la página Factura de proveedor, escriba las siguientes actualizaciones:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Número| INV001|
    | Descripción de la factura| Servicio de instalación inicial|
    | Fecha de la factura| *escribir la fecha de hoy*|

1. En el panel de acciones, seleccione **Guardar**.

1. En el Panel de acciones, seleccione **Actualizar estado de conciliación**.

1. En el panel de acciones, seleccione **Registrar**.

### Liquidar la factura del proveedor

1. En el panel de navegación, seleccione **Módulos** > **Cuentas por pagar** > **Pagos** > **Diario de pagos a proveedores**.

1. En el panel de acciones, seleccione **+Nuevo**.

1. En la página del Diario de pagos a proveedores, en la primera fila, en la columna **Nombre**, seleccione el menú y luego **VendPay**.

1. En el panel de acciones, seleccione **Líneas** para registrar un pago.

1. En la página Pagos a proveedores, en el cuadro **Cuenta**, especifique **V00001**.

1. En la barra de herramientas, seleccione **Liquidar transacciones**.

1. En la página Liquidar transacciones para ABC Training, Inc, en la columna **Marcar**, seleccione el cuadro.

1. En la esquina inferior derecha, seleccione **Aceptar**.

1. En el Panel de acciones, seleccione **Generar pagos**.

1. En el panel **Generar pagos**, escriba las siguientes actualizaciones y, después, seleccione **Aceptar**:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Método de pago| CHEQUE|
    | Cuenta bancaria| USMF OPER|

1. En el panel **Pago mediante cheque**, revise la información y seleccione **Aceptar**.

    >[!ALERT] Verá un error que dice **No se puede encontrar la impresora con la ruta de acceso**. Debe ignorarlo. No hay ninguna impresora instalada en el laboratorio.

1. Desplácese hacia la derecha y, en la columna **Estado de pago**, compruebe que se muestra **Enviado**.

1. En el panel de acciones, seleccione **Validar** > **Validar**.

1. En el panel de acciones, seleccione **Registrar**.

## Ejercicio 3: Explorar Cuentas por cobrar

### Crear un cliente

1. En el panel de navegación, seleccione **Módulos** > **Cuentas por cobrar** > **Clientes** > **Todos los clientes**.

1. En el panel de acciones, seleccione **+Nuevo** para crear un cliente.

1. En el panel **Crear cliente**, cree un nuevo cliente con la siguiente información y luego seleccione **Guardar**:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Cuenta de cliente| US-901|
    | Nombre| Fabrikam Consulting Services|
    | Grupo de clientes| 30|
    | C.P./Código postal| 98052|
    | Calle| 123 Middle Street|

1. En la página US-901 Fabrikam Consulting Services, seleccione la ficha desplegable **Valores predeterminados del pago**.

1. Seleccione el menú **Método de pago** y luego **CHEQUE**.

1. Seleccione la ficha desplegable **Dimensiones financieras**.

1. En el cuadro **Unidad de negocio**, escriba **004**.

1. En el panel de acciones, seleccione **Guardar**.

### Crear una factura de servicios para el nuevo cliente

1. En el panel de acciones, seleccione **Factura** y en la pestaña **NUEVO**, seleccione **Factura de servicios**.

1. En la página US-901 Fabrikam Consulting Services, en el **encabezado** **Factura de servicios**, establezca la fecha de la **FACTURA** a la fecha de hoy.

1. En **Líneas de factura**, realice los siguientes cambios:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Descripción| Aprendizaje del servicio de consultoría|
    | Cuenta principal| 401200|
    | Grupo de impuestos| WA|
    | Importe| 1 500,00|

1. En el panel de acciones, seleccione **Impuestos**.

1. En la página Transacciones de impuestos, revise el registro y seleccione **Aceptar**.

1. En el panel de acciones, seleccione **Registrar**.

1. En el panel **Registrar factura de servicios**, en **IMPRIMIR OPCIONES**, establezca **Imprimir factura** en **Sí** y luego seleccione **Aceptar**.

1. En el panel **Parámetros de destino de impresión**, seleccione **Aceptar** para imprimir la factura en la pantalla.

1. Revise la factura y luego, al terminar, ciérrela.

1. Cierre el formulario.

### Ejecutar un informe de vencimiento de cuentas por cobrar para comprobar

1. En el panel de navegación, seleccione **Módulos** > **Crédito y cobros** > **Consultas e informes** > **Clientes** > **Informe de vencimiento de clientes**.

1. En el panel **Informe de vencimiento de clientes**, escriba las siguientes actualizaciones y, después, seleccione **Aceptar**:

    | **Parámetro**| **Valor**|
    | :--- | :--- |
    | Vencimiento a partir de| La fecha de hoy|
    | Definición de período de vencimiento| 30_60_90_180|
    | Detalles| Años|

1. En el Informe de vencimiento de clientes, seleccione el icono con la flecha hacia abajo **Siguiente página** y desplácese hasta la última página.
    Revise la factura creada para el cliente US-901.

1. Cierre el formulario.

### Aplicar pagos de clientes para facturas de servicios

1. En el panel de navegación, seleccione **Módulos** > **Cuentas por cobrar** > **Pagos** > **Diario de pagos de cliente**.

1. En el panel de acciones, seleccione **+Nuevo**.

1. En la página del Diario de pagos de cliente, en la columna **Nombre**, seleccione el menú y luego **CustPay**.

1. En el Panel de acciones, seleccione **Introducir pagos de cliente**.

1. En el cuadro **Cliente**, escriba **US-901**.  
    Espere a que se carguen los datos y luego, en la columna **Marcar**, seleccione el cuadro.

1. Encima de la cuadrícula, en el cuadro **Importe**, escriba **1 597,50**. El importe que se muestra en el cuadro **Importe restante** debería cambiar automáticamente de **1 597,50** a **0**.  
    Es posible que tenga que seleccionar un espacio vacío para que se calcule el valor.

1. En el cuadro **Referencia de pago**, escriba **Check# 123**.

1. En el panel de acciones, seleccione **Guardar en diario**.

1. Cierre el formulario.

1. En el panel de acciones, seleccione **Líneas**.

1. En el panel de acciones, seleccione **Validar** > **Validar**.

1. En el panel de acciones, seleccione **Registrar**.
