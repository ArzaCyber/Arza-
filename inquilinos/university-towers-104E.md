# University Towers 104 E (Paraguay) — Registro de pagos 2026

Fuente: planilla "Rent University Park e Infinity", filas 63–84. Actualizado: 12-oct-2026.
Renta mensual: Gs. 1.800.000, vence el día 5 de cada mes.
Criterio: cada pago se aplica al mes más antiguo pendiente (FIFO).

## Movimientos

| Fecha | Concepto | Renta | Pago | Saldo |
|---|---|---|---|---|
| 05-ene-26 | Alquiler enero | 1.800.000 | | 1.800.000 |
| 05-feb-26 | Alquiler febrero | 1.800.000 | | 3.600.000 |
| 23-feb-26 | A cuenta atrasados | | 2.000.000 | 1.600.000 |
| 27-feb-26 | Saldo enero y febrero | | 1.600.000 | 0 |
| 05-mar-26 | Alquiler marzo | 1.800.000 | | 1.800.000 |
| 05-abr-26 | Alquiler abril | 1.800.000 | | 3.600.000 |
| 24-abr-26 | Pago marzo | | 1.800.000 | 1.800.000 |
| 05-may-26 | Alquiler mayo | 1.800.000 | | 3.600.000 |
| 05-jun-26 | Alquiler junio | 1.800.000 | | 5.400.000 |
| 14-jun-26 | A cuenta atrasados | | 2.500.000 | 2.900.000 |
| 05-jul-26 | Alquiler julio | 1.800.000 | | 4.700.000 |
| 11-jul-26 | A cuenta atrasados | | 4.600.000 | 100.000 |
| 05-ago-26 | Alquiler agosto | 1.800.000 | | 1.900.000 |
| 05-sep-26 | Alquiler septiembre | 1.800.000 | | 3.700.000 |
| 05-oct-26 | Alquiler octubre | 1.800.000 | | 5.500.000 |
| 05-nov-26 | Alquiler noviembre (cobrado por adelantado) | 1.800.000 | | 7.300.000 |
| 08-oct-26 | Atrasados + noviembre | | 7.200.000 | 100.000 |
| 08-oct-26 | Interés por atraso | 120.000 | | 220.000 |

Pendiente: Gs. 220.000 (100.000 saldo de julio + 120.000 interés). Se comprometió a pagar a fin de octubre 2026.

## Días de atraso por mes

| Mes | Vence | Pagado completo | Días de atraso |
|---|---|---|---|
| Enero | 05-ene | 23-feb | 49 |
| Febrero | 05-feb | 27-feb | 22 |
| Marzo | 05-mar | 24-abr | 50 |
| Abril | 05-abr | 14-jun | 70 |
| Mayo | 05-may | 11-jul | 67 |
| Junio | 05-jun | 11-jul | 36 |
| Julio | 05-jul | 1.700.000 el 11-jul (6 días); 100.000 sigue pendiente | 6 / 99+ y contando |
| Agosto | 05-ago | 08-oct | 64 |
| Septiembre | 05-sep | 08-oct | 33 |
| Octubre | 05-oct | 08-oct | 3 |
| Noviembre | 05-nov | 08-oct | 0 (adelantado 28 días) |

Promedio ene–oct (pago principal de cada mes): ~40 días de atraso. 9 de 10 meses con más de 20 días.

## Correcciones a la planilla (columna F)

- F76 (julio) dice 67 → debería ser 6 (por 1,7 M; los 100.000 restantes siguen pendientes).
- F78 (agosto) dice 36 → debería ser 64.
- F79 (septiembre) dice 5 → debería ser 33.
- F80 (octubre) vacío → 3.
- F81 (noviembre) vacío → 0 (adelantado).

## Recálculo de intereses y saldo de julio (12-oct-2026)

Saldo de julio: rentas ene–nov 19.800.000 − pagos 19.700.000 = **Gs. 100.000** (correcto).

Base de cálculo: saldo deudor diario × días (interés simple, mes de 30 días).
- Período 11-jul → 08-oct: 188,9 M Gs·día (agosto 64 días, septiembre 33, octubre 3, los 100.000 de julio 89).
- Año completo 05-ene → 08-oct: 709,2 M Gs·día.

| Tasa mensual | Solo jul–oct | Todo el año |
|---|---|---|
| 1 % | 63.000 | 236.400 |
| 2 % | 125.900 | 472.800 |
| 3 % | 188.900 | 709.200 |

Los 120.000 cobrados equivalen a ≈1,9 % mensual sobre el atraso de jul–oct (no cubren los atrasos de ene–jun).
Interés de los 100.000 de julio al 2 %: 6.600 al 12-oct (99 días desde el 5-jul); 7.900 al 31-oct.
Total a fin de octubre al 2 % (solo jul–oct): 100.000 + 125.900 + 1.500 (100.000 del 8 al 31-oct) ≈ **Gs. 227.400**.
