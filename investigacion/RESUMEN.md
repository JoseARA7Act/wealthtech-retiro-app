# Resumen y recomendaciones

*2026-11-12. Lo que dice la investigación leída hasta hoy sobre el producto, y lo que sugiere
hacer. Cada punto tiene su fuente en [`EVIDENCIA.md`](EVIDENCIA.md) y [`FUENTES.md`](FUENTES.md).
Son recomendaciones de diseño desde la evidencia; las decisiones son de José y van en
[`PRODUCTO.md`](PRODUCTO.md).*

## En una frase

El canal remesa → Afore ya existe en México y nadie lo usa: el producto gana si convierte cada envío
en un débito automático pequeño, fácil de entender y con una parte disponible para emergencias, no si
recuerda ahorrar o promete ganarle al mercado.

## Lo que ya sabemos

1. **El canal no es lo nuevo.** U-Link (2018) ya mandaba dinero de EE. UU. a la Afore sin comisión
   extra, y AforeMóvil acepta a mexicanos en el extranjero; no hay cifras de uso (Tuesta & Bhardwaj
   2023, cap. 12, pp. 381–382).
2. **Casi nadie ahorra de forma voluntaria:** el 6,8 % de las cuentas del SAR (Azuara et al. 2021,
   p. 12). La remesa casi no se ahorra hoy: va a manutención, salud y educación (Cervantes González
   2018, p. 62).
3. **Lo que funciona es apartar el ahorro de un ingreso, en automático.** Cabify Perú: 18 % se
   inscribió a un débito automático y solo 3,3 % se salió; pero de todos los invitados, solo el 4 %
   ahorró de verdad (Azuara et al. 2021, pp. 26, 28).
4. **Los recordatorios no convierten a nadie en México.** Los SMS a cuentahabientes del SAR no
   tuvieron efecto; los push de AforeMóvil subieron 16 % el ahorro de quien ya ahorraba, y nada en
   quien no (Azuara et al. 2021, pp. 37–38, 122–124).
5. **El dinero con destino ya decidido se defiende.** Italia (TFR) y Chile (devolución de impuestos)
   fracasaron al tomar por omisión un dinero que la gente ya tenía planeado (Tuesta & Bhardwaj 2023,
   cap. 18, p. 529; Azuara et al. 2021, p. 24). Para la familia, la remesa es ese dinero.
6. **Quien distribuye tiene que entender el producto.** Yastás falló porque los tenderos no
   entendían el SAR (Azuara et al. 2021, p. 41); GanAhorro, por el registro en AforeMóvil y porque
   las Afores no lo promovieron (Tuesta & Bhardwaj 2023, cap. 16, pp. 502–503).
7. **Sin escala, una micropensión muere aunque la gente aporte al principio.** Mbao (Kenia): −34 %
   de activos en un año, por falta de escala y una administración débil (Guven 2019, p. 37). México
   ya tiene el administrador central: PROCESAR y las Afores (Azuara et al. 2021, pp. 46–47).
8. **La liquidez, con medida.** El BID pide una parte disponible para emergencias (Azuara et al.
   2021, pp. 10, 54); Ghana dividía cada aporte en dos cuentas (Guven 2019, p. 39); con liquidez
   total, los conductores de Cabify retiraron el 81 % (Azuara et al. 2021, p. 134), y Mazima
   (Uganda) se volvió ahorro de corto plazo (Guven 2019, p. 45).
9. **El costo a vencer:** la Afore cobra hasta 0,53 % al año sobre el saldo en 2027 (CONSAR 2026,
   p. 1); depositar por AforeMóvil no tiene comisión (Azuara et al. 2021, p. 47).
10. **Ganarle al mercado no está probado.** La estrategia propia queda debajo del mercado y del
    S&P 500 por riesgo, con una caída máxima de −63.96 % (ver *Ganarle al mercado*).

## Recomendaciones

1. **Diseñar el ahorro como un débito automático sobre cada envío**, prendido en el momento del
   envío, con un toque para quitarlo. Es lo único con evidencia de que mueve el ahorro (puntos 3 y 4).
2. **Bajar el 10 % por omisión, o probarlo contra uno pequeño.** La evidencia comparable es de 1–2 %
   y detenible cuando se quiera (Tuesta & Bhardwaj 2023, cap. 24, p. 731), y dos casos muestran que
   tomar el dinero ya destinado falla (punto 5). El brazo B del piloto debería comparar dos tamaños.
3. **Medir si la familia deja de recibir por la app.** Es el riesgo principal de un aporte por
   omisión sobre la remesa, y ya está en las medidas del piloto.
4. **Dos bolsas en cada aporte:** una de emergencia, que se llena primero, y una de retiro. Es el
   diseño *Sidecar* que describe el BID (Azuara et al. 2021, p. 55) y el de Ghana; reemplaza a los
   contratos inteligentes de retiro total, que repiten el caso Mazima.
5. **Montarse sobre el riel que existe** —AforeMóvil o PROCESAR— en vez de construir el depósito. La
   tarea del producto es traer volumen, no administrar (punto 7).
6. **Que la explicación sea parte del producto.** Ver el saldo, saber quién lo custodia y entender
   qué es la Afore: la desconfianza y la desinformación son las causas de fondo (Tuesta & Bhardwaj
   2023, cap. 24, pp. 721, 723), y Yastás falló por no explicar.
7. **No usar recordatorios para captar, solo para subir el monto** de quien ya aporta, con metas
   mensuales (Azuara et al. 2021, p. 34).
8. **Usar la estrategia creada, sin prometer que le gana al mercado.** Parte del hackathon es
   desarrollar una estrategia que busque exceso de retorno, y el producto la usará. Lo que la
   evidencia pide es cómo: mostrarla al lado de su rival simple, el S&P 500, con sus cifras de riesgo
   del Backtest Engine (la estrategia actual: Sharpe 0.507 frente a 0.574 de SPY, caída máxima
   −63.96 %), y no llevarla a dinero real antes de una prueba escrita de antemano. Para un ahorro de
   retiro la caída pesa: la directiva principal es sobrevivir (Paleologo 2021, cap. 2, p. 22).
9. **Usar una cartera según la edad** como opción por omisión, si el ahorro vive fuera de la Afore:
   la de Cerdas (2025, p. 15) es una plantilla, no evidencia; dentro de la Afore, las SIEFORE ya lo
   hacen por edad.
10. **Comparar la vara realista:** 18 % de inscripción y 4 % que ahorra de verdad (Cabify), no la
    disposición declarada de 20–23 %.

## Lo que hay que resolver antes del demo

- **Si un migrante puede depositar en la cuenta Afore de su familia.** Algunos países lo limitan por
  lavado de activos (Azuara et al. 2021, p. 45). CONSAR y la ley del SAR.
- **En qué moneda recibe la Afore** y quién carga la conversión: la decisión de ahorrar en dólares
  depende de esto.
- **Qué permite Banxico con stablecoins** para una fintech.
- **Qué retiros parciales permite la ley** a las aportaciones voluntarias, y si la subcuenta de
  corto plazo de cada Afore sirve como la bolsa de emergencia (Azuara et al. 2021, p. 56).
