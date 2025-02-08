#  GESTI√ìN DE UNA COMPRA - PEDIDOS A PROVEEDORES  

## Ì≥å Tabla de Contenido  

1. [Introducci√≥n](#1-introducci√≥n)  
2. [Creaci√≥n de un pedido de compra](#2-creaci√≥n-de-un-pedido-de-compra)  
3. [Pedido de compra: P00001](#3-pedido-de-compra-p00001)  
4. [Recepci√≥n de productos (WH/IN/00001)](#4-recepci√≥n-de-productos-whin00001)  
5. [Otro pedido de compra: P00003](#5-otro-pedido-de-compra-p00003)  
6. [Recepci√≥n de productos (S00009)](#6-recepci√≥n-de-productos-s00009)  
7. [Captura de productos con nueva cantidad de stock](#7-captura-de-productos-con-nueva-cantidad-de-stock)  
8. [Recursos adicionales](#8-recursos-adicionales)  

---

## 1. Introducci√≥n  

La gesti√≥n de compras en Odoo es un proceso clave para mantener un flujo de stock adecuado en la empresa. En este paso, aprenderemos a:  

- Crear pedidos de compra a proveedores.  
- Confirmar pedidos y calcular el total con impuestos.  
- Recibir productos en el almac√©n y verificar su stock.  

El prop√≥sito de este proceso es garantizar que nuestra empresa pueda abastecerse de los productos necesarios para su funcionamiento y posterior venta.  

Ì≥å *Aqu√≠ insertar captura de los productos antes de la compra*  

---

## 2. Creaci√≥n de un pedido de compra  

Para realizar un pedido de compra en Odoo, sigue estos pasos:  

1. Ir al m√≥dulo de **Compras**.  
2. Acceder a **Productos de ventas**.  
3. Hacer clic en **"Nuevo"** para crear un pedido de compra.  
4. Ingresar la informaci√≥n del proveedor, la moneda y la fecha de confirmaci√≥n.  
5. Agregar los productos deseados, especificando cantidad y precio por unidad.  
6. Confirmar el pedido y revisar los detalles antes de su procesamiento.  

---

## 3. Pedido de compra: P00001  

**Detalles del pedido:**  

- **Proveedor**: PC Componentes - B73347494  
- **Moneda**: EUR  
- **Fecha de confirmaci√≥n**: 07/02/2025 07:57:21  
- **Llegada prevista**: 07/02/2025 09:05:09  
- **Estado**: Pedir confirmaci√≥n  

### Productos incluidos:  

- **[AIRPod4-ANC]** Apple AirPods 4 con Cancelaci√≥n Activa  
  - Cantidad: 15  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 50‚Ç¨  

- **[AW300]** Xiaomi Outdoor Camera IP WiFi  
  - Cantidad: 10  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 40‚Ç¨  

- **[ACR-A3-R7-5700U-16-512-15]** Port√°til Acer Aspire 3 15"  
  - Cantidad: 3  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 340‚Ç¨  

### Totales:  

- **Base imponible**: 2.170,00 ‚Ç¨  
- **IVA (21%)**: 455,70 ‚Ç¨  
- **Total**: 2.625,70 ‚Ç¨  

Ì≥å *Aqu√≠ insertar captura del pedido de compra P00001*  

---

## 4. Recepci√≥n de productos (WH/IN/00001)  

Una vez confirmado el pedido, los productos deben ser recibidos en el almac√©n.  

- **Recibir de**: PC Componentes  
- **Tipo de operaci√≥n**: Electroshop S.L. Recepciones  
- **Fecha programada**: 10/02/2025 12:45:05  
- **Fecha l√≠mite**: 07/02/2025 09:00:09  
- **Documento de origen**: PS00001  

Ì≥å *Aqu√≠ insertar captura de la recepci√≥n de productos WH/IN/00001*  

---

## 5. Otro pedido de compra: P00003  

En este caso, realizamos un nuevo pedido con diferentes productos.  

**Detalles del pedido:**  

- **Proveedor**: PC Componentes - B73347494  
- **Moneda**: EUR  
- **Fecha de confirmaci√≥n**: 07/02/2025 10:21:39  
- **Llegada prevista**: 07/02/2025 10:20:41  
- **Estado**: Pedir confirmaci√≥n  

### Productos incluidos:  

- **[RJ45-CAT8-20M]** Cable de red RJ45 CAT8 U/FTP AWG 30  
  - Cantidad: 50  
  - Recibido: 0  
  - Facturado: 0  
  - Precio por unidad: 13‚Ç¨  
  - Impuesto: 21%  
  - Importe: 650,00‚Ç¨  

### Totales:  

- **Base imponible**: 650,00 ‚Ç¨  
- **IVA (21%)**: 136,50 ‚Ç¨  
- **Total**: 2.786,50 ‚Ç¨  

Ì≥å *Aqu√≠ insertar captura del pedido de compra P00003*  

---

## 6. Recepci√≥n de productos (S00009)  

Cuando los productos llegan a nuestro almac√©n, se realiza la recepci√≥n en Odoo.  

- **Recibir de**: PC Componentes  
- **Tipo de operaci√≥n**: Electroshop S.L. Recepciones  

Ì≥å *Aqu√≠ insertar captura de la recepci√≥n de productos S00009*  

---

## 7. Captura de productos con nueva cantidad de stock  

Despu√©s de completar la recepci√≥n de productos, el stock de la empresa se actualiza autom√°ticamente en Odoo.  

Ì≥å *Aqu√≠ insertar captura del stock actualizado*  

---

## 8. Recursos Adicionales  

Si deseas profundizar en la gesti√≥n de compras en Odoo, aqu√≠ tienes algunos tutoriales √∫tiles:  

- [Ì≥å ODOO Compras | Crear un pedido de compras sin realizar una solicitud de compra previa](https://www.youtube.com/watch?v=GepL1n_iAm8)  
- [Ì≥å ODOO Compras | Entrada total de mercanc√≠a en Odoo](https://www.youtube.com/watch?v=B9H3Ere0Scg)  
- [Ì≥å ODOO Compras | C√≥mo crear una solicitud de presupuesto](https://www.youtube.com/watch?v=JaqXeini4gY)  
- [Ì≥å ODOO Compras | C√≥mo imprimir una solicitud de compra](https://www.youtube.com/watch?v=yZr_knHGLKQ)  

---

### ‚úÖ Conclusi√≥n  

La gesti√≥n de compras en Odoo permite un control eficiente del inventario, asegurando que la empresa siempre tenga productos disponibles para la venta. Mediante la correcta ejecuci√≥n de pedidos y recepciones, garantizamos un flujo de trabajo organizado y optimizado.  

Este proceso es fundamental para mejorar la log√≠stica y la administraci√≥n de recursos dentro de la compa√±√≠a. Ì∫Ä  
