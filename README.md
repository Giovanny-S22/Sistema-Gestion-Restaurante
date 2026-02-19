# Sistema de Gestión para Restaurante

## Descripción
Sistema diseñado para gestionar pedidos, facturación, inventario y cierre diario de ventas en un restaurante.

## Funcionalidades
- Registro de pedidos
- Visualización en pantalla de cocina
- Generación de facturas
- Cierre diario de caja
- Control de inventario

## Equipo
- Giovanny Charfuelan Silva
- Francisco Pantoja Estrada
- Carlos Daniel Otalora
- Luis Orlando Victoria

# Arquitectura del Sistema de Gestión de Restaurantes

---

## 📥 Entradas (Inputs)

### ¿Qué datos recibe el sistema?

- tipo de servicio
- codigo del servicio seleccionado
- datos del proveedor
- registros devoluciones o cancelaciones


### ¿Quién los ingresa?

- mesero
- cajero
- encargado
- administrador

 
### Tipo de datos

- codigos
- valores decimales
- fechas programadas

## ⚙️ Procesos (Throughput)

###Lo que hace el sistema

- asigna numero unico
- cambia el estado del pedido
- regista entradas y salidas
- controla descueto y promociones


###Lo que Calcula

- subtotal del producto
- descuentos aplicados
- costo total del pedido
- consumo promedio de ingredientes

###Lo que Guarda

- historial de cambios de pedido
- registro de provedores
- control de devoluciones
- estadistica de consumo

  ## 📤 Salidas (Outputs)

- comprobate de orden conestado actualizado
- reporte de consumo de ingredientes
- reponte de provedores
- resumen de promociones aplicadas


 
