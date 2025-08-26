
DINAMITA POS (v1.0) — 2025-08-26 03:02

Este ZIP contiene una versión funcional y sencilla de Dinamita POS en HTML/CSS/JS (sin servidor).
Guarda los datos en el navegador (localStorage). Ideal para pruebas en PC o celular.

Módulos incluidos:
- Dashboard (KPIs)
- Ventas (carrito, IVA, pagos divididos, cliente opcional)
- Inventario (CRUD, imagen de producto, exportar CSV)
- Clientes (CRUD)
- Membresías (tipos, fechas automáticas, estado: activa/próxima/vencida)
- Cafetería (vista de catálogo por categoría)
- Historial de ventas (filtros, ticket, exportar CSV)
- Configuración (IVA, mensaje de ticket, logo)
- Ticket 58mm (impresión)

Cómo usar:
1) Abrir index.html en Chrome/Edge (recomendado).
2) Ir a "Configuración" para ajustar IVA, logo y mensaje del ticket.
3) Cargar productos en "Inventario" (o usar los de ejemplo).
4) Realizar ventas en "Ventas". Se generará el ticket y quedará en Historial.
5) Imprimir ticket desde "Ticket 58mm" (usa @media print con ancho 58mm).
6) Exportar/Importar respaldo JSON desde la barra superior.

Notas:
- No requiere internet ni instalación.
- Los datos se guardan por navegador/dispositivo.
- Para "limpiar" todo, borrar el almacenamiento local de la página (localStorage).

Créditos: Diseño y desarrollo base para Dinamita Gym.
