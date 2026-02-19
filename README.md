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

-Nombre del cliente  
-Numero de mesa  
-Platos seleccionados  
-Cantidad  
-Metodo de pago  
-Datos del empleado (tipo de usuario)

### ¿Quién los ingresa?

-Mesero:  
 -Ingresa los pedidos  
-Cajero:  
 -Registra los pagos  
-Administrador:  
 -Registra el menú  
 -Da roles a los empleados(mesero,cajero)
 
### Tipo de datos

 -Texto  
 -Números  
 -Fechas
 
## ⚙️ Procesos (Throughput)

### Lo que hace el sistema

-Registra pedidos  
-Calcula el total  
-Valida que los datos ingresados esten completos y haya inventario  
-Guarda la información  
-Genera Factura  
-Actualiza inventario

### Lo que Calcula

-Total a pagar  
-Cambio  
-Venta del dia

### Lo que Guarda

-Pedidos  
-Productos  
-Ventas  
-Inventario

## 📤 Salidas (Outputs)

### ¿Qué obtiene el usuario?

-Total a pagar   
-Factura  
-Confirmación de pedido

### ¿Qué genera el sistema?
-Reporte de Ventas  
-Lista de productos mas vendididos

### ¿Permite tomar decisiones?
-Si, ayuda a controlar ventas e inventario

## 👥 Usuarios y Roles

### ¿Quién usa el sistema?

-Administrador  
-Cajero  
-Mesero

### ¿Todos hacen lo mismo?

No, cada usuario tiene una funcion diferente

### ¿Hay permisos?

Si.  
-Administrador: Controla todo  
-Cajero: Procesa los pagos  
-Mesero: Registra pedidos

## 📊 Información Manejada
 ### ¿Qué datos son críticos?
-Ventas  
-Pagos  
-Inventario  
-Datos de empleados

### ¿Qué no se puede perder?
-Registro de ventas
-Información de pagos
