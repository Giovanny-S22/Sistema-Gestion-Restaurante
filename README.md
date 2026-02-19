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
-Pedidos de los clientes (platos, cantidades, número de mesa)

-Datos del inventario (productos, cantidades disponibles, proveedor)

-Información de ventas (total, método de pago, fecha)

-Datos de usuarios (nombre, rol, contraseña)

-Actualización de precios y menú
### ¿Qué datos recibe el sistema?

-Pedidos de los clientes (platos, cantidades, número de mesa)

-Datos del inventario (productos, cantidades disponibles, proveedor)

-Información de ventas (total, método de pago, fecha)

-Datos de usuarios (nombre, rol, contraseña)

-Actualización de precios y menú
### ¿Quién los ingresa?

-Meseros → Registran pedidos

-Cajero → Registra pagos

-Administrador → Gestiona inventario, precios y usuarios
 
### Tipo de datos

 -Texto (nombre de productos, nombres de usuarios)

-Números (precios, cantidades, totales)

-Fechas y horas

Opciones seleccionables (rol, método de pago
 
## ⚙️ Procesos (Throughput)

###Lo que hace el sistema

-Registra y almacena pedidos en la base de datos

-Verifica disponibilidad de productos en inventario

-Controla el acceso según el rol del usuario

-Actualiza automáticamente el inventario después de cada venta

-Genera reportes administrativos
###Lo que Calcula
-Total de la cuenta por pedido

-Impuestos (si aplica)

-Ventas diarias, semanales y mensuales

-Productos más vendidos

-Ganancias totales



###Lo que Guarda

-

## 📤 Salidas (Outputs)

- 
- 
- 

---

## 👥 Usuarios y Roles

- **Administrador:**
  - 
  - 

- **Usuario:**
  - 
  - 

---

## 📊 Información Manejada

- 
- 
- 
