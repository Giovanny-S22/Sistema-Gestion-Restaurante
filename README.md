# Sistema de Gestión para Restaurante
# Arquitectura del Sistema de Gestión de Restaurante

## 📥 Entradas

El sistema recibe los siguientes datos:

  Nombre del cliente.
- Número de mesa.
- Platos seleccionados.
- Cantidad de cada plato.
- Método de pago.
- Datos del empleado (usuario y rol).
- Información del inventario.
- Fecha y hora de la transacción.

# ¿Quién los ingresa?

- Mesero:
-   Ingresa los pedidos, número de mesa.
- Cajero:
-   Registra el método de pago, confirma la transacción.
- Administrador:
-   Registra el menú, precios, roles de empleados.

# ¿Son números, texto o archivos?
- Texto:
-   nombre del cliente, nombre de platos.
- Números:
-   cantidades, precios, número de mesa.
- Fechas:
-registro de ventas:

# ⚙️ Procesos

# ¿Qué hace el sistema con esos datos?

- Valida que la información esté completa.
- Disponibilidad en el inventario.
- Registra los pedidos.
- Calcula la venta.
- Aplica impuestos si corresponde.
- Controla el acceso.

# ¿Valida?

Sí. Verifica que:
- Los datos estén completos.
- El producto exista en el menú.
- La cantidad solicitada esté disponible.
- El usuario tenga permisos según su rol.

# ¿Calcula?

Sí. El sistema:
- Calcula subtotales.
- Calcula totales finales.
- Genera reportes diarios de ventas.

# ¿Guarda?

Sí. Almacena:
- Pedidos.
- Ventas.
- Pagos.
- Movimientos de inventario.
- - Información de empleados.

---
# 📤 Salidas

# ¿Qué obtiene el usuario?

- Factura comprobante de pago.
- Pedido comnfirmado.
- Total pagado.

# ¿Qué genera el sistema?

- Reporte de ventas.
- Estado del inventario.
- Historial.
- Cierre de caja.

# ¿Permite tomar decisiones?

Sí. Permite al administrador:
- Analizar ventas diarias.
- Identificar productos más vendidos.
- Controlar inventario.
- - Evaluar el rendimiento del negocio.

---

# 👥 Usuarios

# ¿Quién usa el sistema?

- Administrador.
- Mesero.
- Cajero.

# ¿Todos hacen lo mismo?

No. Cada usuario tiene funciones específicas:

- **Administrador:** Gestiona menú, empleados y reportes.
- **Mesero:** Registra pedidos.
- **Cajero:** Registra pagos y genera facturas.

# ¿Hay permisos?

Sí. El sistema controla el acceso según el rol del usuario para evitar modificaciones no autorizadas.

---


