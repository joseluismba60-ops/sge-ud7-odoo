# Documentación del Ciclo Comercial Completo — PhoneLink Repair & Parts S.L.

## 1. Diagrama de Flujo del Proceso
`Presupuesto (Comercial)` ➔ `Pedido Confirmado (Resp. Ventas)` ➔ `Albarán de Entrega (Almacén)` ➔ `Factura y Registro de Pago (Administración)`

## 2. Matriz de Trazabilidad y Roles Aplicados

| Etapa | Usuario Responsable | Rol Aplicado | Documento Generado | Estado Final |
| :--- | :--- | :--- | :--- | :--- |
| **1. Propuesta Comercial** | José Luis Mba | Comercial Junior | Presupuesto (`S00001`) | Enviado |
| **2. Aprobación de Venta** | Laura Gómez | Responsable Ventas | Pedido de Venta (`S00001`) | Pedido de venta |
| **3. Salida de Material** | Laura Gómez | Responsable Ventas | Albarán (`WH/OUT/00001`) | Realizado |
| **4. Emisión de Factura** | Carlos Ruiz | Adm. Facturación | Factura Oficial (`INV/2026/00001`) | Publicado |
| **5. Cobro en Tesorería** | Carlos Ruiz | Adm. Facturación | Registro de Pago (Banco/Caja) | Pagado |

## 3. Justificación Técnica y Principio de Mínimo Privilegio
* **Segregación de Funciones:** El comercial junior puede crear ofertas, pero requiere la autorización de la responsable de ventas para bloquear precios y confirmar pedidos.
* **Protección Contable:** El módulo de facturación y cobro está restringido a la administración, evitando que el personal de ventas modifique estados de pago o acceda al balance de la empresa.