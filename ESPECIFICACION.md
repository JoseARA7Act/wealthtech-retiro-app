# Especificación del MVP

Cada requisito dice de dónde sale: una fuente con página, una decisión de José
([`DECISIONES.md`](DECISIONES.md)) o *conocimiento general, sin verificar*. Los que dependen de una
pregunta abierta lo dicen.

## Flujo 1: registro

- **R1.1** Registro con los datos mínimos y la CURP de quien será titular de la cuenta de retiro.
  *Por qué:* la CURP basta para tener cuenta en el SAR (CONSAR 2020, p. 2).
- **R1.2** Cada paso extra cuesta usuarios: el registro debe caber en una sola pantalla o en muy
  pocas. GanAhorro no escaló, en parte, por un registro complejo en AforeMóvil (Tuesta & Bhardwaj
  2023, cap. 16, pp. 502–503); en una empresa chilena, el 46 % dijo querer ahorrar y solo el 26 % lo
  formalizó (Azuara et al. 2021, pp. 26–27).
- **R1.3** Verificación de identidad (KYC) a través del socio regulado. *Conocimiento general, sin
  verificar:* un servicio de remesas y uno de ahorro piden KYC; el detalle lo define el socio.

## Flujo 2: enviar una remesa con ahorro

- **R2.1** En la pantalla de envío, el ahorro aparece **prendido por omisión** con un porcentaje
  pequeño, y se quita con un toque. *Por qué:* el débito automático ligado a un ingreso es lo que
  más ahorro genera (Azuara et al. 2021, pp. 8, 22); la referencia comparable es 1–2 % y detenible
  cuando se quiera (Tuesta & Bhardwaj 2023, cap. 24, p. 731).
- **R2.2** El porcentaje por omisión es un **parámetro**, no un valor fijo: el piloto compara al
  menos dos tamaños. *Por qué:* tomar por omisión dinero ya destinado falló en Italia y en Chile
  (Tuesta & Bhardwaj 2023, cap. 18, p. 529; Azuara et al. 2021, p. 24). El 10 % de la idea original
  queda como uno de los brazos a probar.
- **R2.3** El envío no se retrasa ni pide un paso más por el ahorro. *Por qué:* la rapidez es el
  factor más importante al elegir cómo enviar (Cervantes González 2018, p. 57).
- **R2.4** Se puede operar de noche y en fin de semana (Serrano Herrera & Fernández de Castro,
  pp. 33–34).
- **R2.5** El receptor puede cobrar como cobra hoy, también en efectivo; no se le exige cuenta
  bancaria (Cervantes González 2018, pp. 56–57).

## Flujo 3: elegir la cuenta del ahorro

- **R3.1** Se pregunta si el ahorro va a la cuenta de quien envía o de quien recibe (decisión de
  José).
- **R3.2** *Depende de una pregunta abierta:* si la regulación mexicana permite que un tercero
  deposite en la cuenta de otro. Algunos países lo limitan por lavado de activos (Azuara et al.
  2021, p. 45). Mientras no se confirme, la opción «cuenta de quien recibe» queda detrás de una
  bandera.
- **R3.3** Guardar la cuenta elegida como dato: el piloto la **mide**.

## Flujo 4: dos bolsas

- **R4.1** Cada aporte llena primero una **bolsa de emergencia** hasta una meta, y luego la **bolsa
  de retiro**. *Por qué:* es el diseño *Sidecar* que describe el BID (Azuara et al. 2021, p. 55); en
  Ghana cada aporte se dividía entre corto plazo y retiro (Guven 2019, p. 39).
- **R4.2** La bolsa de emergencia se retira sin castigo; la de retiro sigue las reglas de la Afore.
  *Por qué:* con liquidez total la gente retira casi todo: 81 % en Cabify (Azuara et al. 2021,
  p. 134); Mazima, en Uganda, se volvió ahorro de corto plazo (Guven 2019, p. 45).
- **R4.3** *Depende de una pregunta abierta:* si la subcuenta voluntaria de corto plazo de cada
  Afore (Azuara et al. 2021, p. 56) sirve como bolsa de emergencia, o si va fuera de la Afore.
- Esto reemplaza los «contratos inteligentes para retiro total por imprevistos» de la idea
  original; ver [`DECISIONES.md`](DECISIONES.md).

## Flujo 5: ver el saldo

- **R5.1** Saldo de cada bolsa, quién lo custodia y cuánto se aportó, siempre a la vista. *Por
  qué:* la desconfianza —«dudas de que el ahorro llegue a buen fin»— y la desinformación son las
  causas de fondo de no aportar (Tuesta & Bhardwaj 2023, cap. 24, pp. 721, 723).
- **R5.2** Una explicación corta y clara de qué es la Afore y qué pasa con el dinero. Yastás falló
  porque los tenderos no entendían el SAR (Azuara et al. 2021, p. 41).

## Flujo 6: la proyección «cuánto tendría»

- **R6.1** Se muestra un **rango** con sus supuestos, no una cifra (Klugman, Panjer & Willmot 2019,
  cap. 19, pp. 485, 493–496).
- **R6.2** Descuenta la comisión de la Afore: hasta 0,53 % anual sobre el saldo en 2027 (CONSAR
  2026, p. 1).

## Flujo 7: dónde se invierte

- **R7.1** Opción por omisión según la edad. Si el ahorro va a la Afore, las SIEFORE ya reparten por
  edad (Cerdas 2025, p. 9). Si va fuera, una cartera de ciclo de vida: la de Cerdas (2025, p. 15) es
  una plantilla, no evidencia.
- **R7.2** Opciones: S&P 500; cartera por edad; **la estrategia creada**, con su aviso de riesgo y sus
  cifras del Backtest Engine junto al S&P 500; renta fija. Nunca la promesa de ganarle al mercado
  (decisión de José).
- **R7.3** Las cifras de la estrategia que se muestren vienen del Backtest Engine, nunca de la app.
- **R7.4** *Depende de una pregunta abierta:* moneda (dólares o pesos) y stablecoins.

## Flujo 8: recordatorios

- **R8.1** Recordatorios solo para quien ya aporta, con una meta mensual y un enlace para aportar
  ahí mismo. *Por qué:* en México los SMS no tuvieron efecto y los push solo subieron el ahorro de
  quien ya ahorraba (Azuara et al. 2021, pp. 37–38, 122–124); las metas mensuales fueron lo único
  constante (p. 34).
- **R8.2** No usar recordatorios para captar nuevos ahorradores.

## Fuera del MVP

- Microseguros, vivienda, tandas.
- Dinero real, hasta tener un socio regulado.
