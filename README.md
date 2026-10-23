# 👜 Control de Inventario & Ventas en Vivo (+ / -) — Totebags Event

Plataforma interactiva para control de costos base, precios de venta y registro táctil de ventas con pulsadores `+` y `-` en tiempo real.

---

## 🎛️ Módulos Integrados

### 1. 📦 Módulo de Inventario & Estructura de Costos
- **Catálogo Maestro:** Cantidades iniciales del lote (59 unidades), precio de compra, shipping y costo de bordado unitario.
- **Cálculo de Costo Total Unitario:** `Precio de Compra + Shipping + Bordado`.
- **Proyecciones del Run:** Inversión total requerida ($\text{RD\$ } 24,486.18$), facturación esperada ($\text{RD\$ } 127,410.00$) y beneficio máximo proyectado ($\text{RD\$ } 102,923.82$).

### 2. 🎯 Módulo de Ventas en Vivo (Pulsadores `+` / `-`)
- **Sin formularios ni botones de registro complejos:** Cada modelo de tote bag tiene su propio pulsador táctil `[-]` y `[+]`.
- **Total en inventario en el centro:** Muestra claramente `X vendidas / Y total en inventario` y las unidades restantes disponibles.
- **Cálculo de beneficio en tiempo real:** Cada vez que pulsas `+` al vender una tote bag, el sistema suma automáticamente el precio de venta cobrado, deduce el costo de fabricación y calcula el **beneficio neto real en mano**.
- **Control de límites:** El botón `+` se desactiva cuando se agota el stock inicial de ese modelo, y el botón `-` permite corregir si se presiona por error.
- **Botón "Reiniciar Ventas":** Permite regresar todos los contadores de venta a cero con un solo clic.

---

## 📥 Exportación a Google Sheets & Excel

- **Copiar para Google Sheets:** Copia el resumen de ventas en vivo en formato tabular. Abre cualquier hoja de Google Sheets y presiona <kbd>Ctrl + V</kbd>.
- **Descargar CSV:** Archivo `.csv` con codificación UTF-8 compatible con Google Drive y Excel.
- **Acceso directo sheets.new:** Abre una hoja nueva en blanco y deja los datos en el portapapeles listos para pegar.
