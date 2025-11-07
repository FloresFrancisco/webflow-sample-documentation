# 🧩 Detalles funcionales por módulo

## 1. Catálogo
- **Descripción:** muestra productos con paginación y filtros.
- **Acciones clave:** búsqueda, filtrado, añadir al carrito.
- **Dependencias:** API `/products`, componente `FilterBar`.

## 2. Carrito de compras
- **Descripción:** mantiene productos seleccionados por sesión.
- **Acciones:** modificar cantidad, eliminar, aplicar cupones.
- **Dependencias:** API `/cart`, sesión del usuario.

## 3. Checkout
- **Descripción:** flujo de pago y confirmación.
- **Integraciones:** PayPal, Stripe, SendGrid (correo de confirmación).

## 4. Panel admin
- **Acceso:** solo usuarios con rol `admin`.
- **Funciones:** CRUD de productos, usuarios y pedidos.
