# Formatos de Nexentia Gastro

Formatos de captura para clientes de Nexentia Gastro. Son páginas sin datos: lo que se anota se guarda solo en el teléfono de quien lo usa y sale únicamente cuando esa persona lo envía.

## Movimientos del día

`movimientos/` — ventas por forma de cobro, propinas, otros ingresos y gastos del día, en un solo reporte que se manda por WhatsApp o se descarga para Excel.

Se configura con el enlace, sin cambiar el archivo:

| Parámetro | Para qué | Ejemplo |
|---|---|---|
| `cliente` | Nombre del negocio | `El Hipopótamo Azul` |
| `personas` | Quién puede anotar | `Juan,Adrián,Ale` |
| `cobros` | Formas de cobro (por defecto: Efectivo, Tarjeta, Transferencia) | `Efectivo,Terminal Mercado Pago,Transferencia` |
| `cuentas` | Dónde entra o de dónde sale el dinero (por defecto: Caja, Banco) | `Caja,Mercado Pago` |
| `tel` | Número de WhatsApp al que llega el reporte (opcional) | `5217221234567` |
