#  GESTIÓN DE UNA COMPRA - PEDIDOS A PROVEEDORES  

## Tabla de Contenido  

1. [Introducción](#1-introducción)  
2. [Creación de un pedido de compra](#2-creación-de-un-pedido-de-compra)  
3. [Pedido de compra: P00001](#3-pedido-de-compra-p00001)  
4. [Recepción de productos (WH/IN/00001)](#4-recepción-de-productos-whin00001)  
5. [Otro pedido de compra: P00003](#5-otro-pedido-de-compra-p00003)  
6. [Recepción de productos (S00009)](#6-recepción-de-productos-s00009)  
7. [Captura de productos con nueva cantidad de stock](#7-captura-de-productos-con-nueva-cantidad-de-stock)  
8. [Recursos adicionales](#8-recursos-adicionales)  

---

## 1. Introducción  

La gestión de compras en Odoo es un proceso clave para mantener un flujo de stock adecuado en la empresa. En este paso, aprenderemos a:  

- Crear pedidos de compra a proveedores.  
- Confirmar pedidos y calcular el total con impuestos.  
- Recibir productos en el almacén y verificar su stock.  

El propósito de este proceso es garantizar que nuestra empresa pueda abastecerse de los productos necesarios para su funcionamiento y posterior venta.  


![compra1](/site/img/compra1.png)



---

## 2. Creación de un pedido de compra  

Para realizar un pedido de compra en Odoo, sigue estos pasos:  

1. Ir al módulo de **Compras**.  
2. Acceder a **Productos de ventas**. 
   ![compra1](/site/img/compra0.png)
4. Hacer clic en **"Nuevo"** para crear un pedido de compra.  
5. Ingresar la información del proveedor, la moneda y la fecha de confirmación.  
6. Agregar los productos deseados, especificando cantidad y precio por unidad.  
7. Confirmar el pedido y revisar los detalles antes de su procesamiento.  

---

## 3. Pedido de compra: P00001  

**Detalles del pedido:**  

- **Proveedor**: PC Componentes - B73347494  
- **Moneda**: EUR  
- **Fecha de confirmación**: 07/02/2025 07:57:21  
- **Llegada prevista**: 07/02/2025 09:05:09  
- **Estado**: Pedir confirmación  

### Productos incluidos:  

- **[AIRPod4-ANC]** Apple AirPods 4 con Cancelación Activa  
  - Cantidad: 15  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 50€  

- **[AW300]** Xiaomi Outdoor Camera IP WiFi  
  - Cantidad: 10  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 40€  

- **[ACR-A3-R7-5700U-16-512-15]** Portátil Acer Aspire 3 15"  
  - Cantidad: 3  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 340€  

### Totales:  

- **Base imponible**: 2.170,00 €  
- **IVA (21%)**: 455,70 €  
- **Total**: 2.625,70 €  

![compra1](/site/img/compra3.png)

---

## 4. Recepción de productos (WH/IN/00001)  

Una vez confirmado el pedido, los productos deben ser recibidos en el almacén.  

- **Recibir de**: PC Componentes  
- **Tipo de operación**: Electroshop S.L. Recepciones  
- **Fecha programada**: 10/02/2025 12:45:05  
- **Fecha límite**: 07/02/2025 09:00:09  
- **Documento de origen**: PS00001  

![compra1](/site/img/WH-IN-00001.png) 

---

## 5. Otro pedido de compra: P00003  

En este caso, realizamos un nuevo pedido con diferentes productos.  

**Detalles del pedido:**  

- **Proveedor**: PC Componentes - B73347494  
- **Moneda**: EUR  
- **Fecha de confirmación**: 07/02/2025 10:21:39  
- **Llegada prevista**: 07/02/2025 10:20:41  
- **Estado**: Pedir confirmación  

### Productos incluidos:  

- **[RJ45-CAT8-20M]** Cable de red RJ45 CAT8 U/FTP AWG 30  
  - Cantidad: 50  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 13€  
  - Impuesto: 21%  
  - Importe: 650,00€  

### Totales:  

- **Base imponible**: 650,00 €  
- **IVA (21%)**: 136,50 €  
- **Total**: 2.786,50 €  

  ![compra1](/site/img/compra4.png)

---

## 6. Recepción de productos (WH/IN/00002)  

Cuando los productos llegan a nuestro almacén, se realiza la recepción en Odoo.  

- **Recibir de**: PC Componentes  
- **Tipo de operación**: Electroshop S.L. Recepciones  

![compra1](/site/img/WH-IN-00001.png) 

---

## 7. Captura de productos con nueva cantidad de stock  

Después de completar la recepción de productos, el stock de la empresa se actualiza automáticamente en Odoo.  
 
Stock de **Cable de red RJ45 CAT8 U/FTP AWG 30**  

![compra1](/site/img/compra5.png)

Stock de **Xiaomi Outdoor Camera IP WiF**  

![compra1](/site/img/compra6.png)

Stock de **Apple AirPods 4 con Cancelación Activa**  

![compra1](/site/img/compra7.png)

Stock de **Portátil ACER 3 15**

![compra1](/site/img/compra8.png)  



---

## 8. Recursos Adicionales  

Si deseas profundizar en la gestión de compras en Odoo, aquí tienes algunos tutoriales útiles:  

- [ODOO Compras | Crear un pedido de compras sin realizar una solicitud de compra previa](https://www.youtube.com/watch?v=GepL1n_iAm8)  
- [ODOO Compras | Entrada total de mercancía en Odoo](https://www.youtube.com/watch?v=B9H3Ere0Scg)  
- [ODOO Compras | Cómo crear una solicitud de presupuesto](https://www.youtube.com/watch?v=JaqXeini4gY)  
- [ODOO Compras | Cómo imprimir una solicitud de compra](https://www.youtube.com/watch?v=yZr_knHGLKQ)  

---

### ✅ Conclusión  

La gestión de compras en Odoo permite un control eficiente del inventario, asegurando que la empresa siempre tenga productos disponibles para la venta. Mediante la correcta ejecución de pedidos y recepciones, garantizamos un flujo de trabajo organizado y optimizado.  

Este proceso es fundamental para mejorar la logística y la administración de recursos dentro de la compañía. 
