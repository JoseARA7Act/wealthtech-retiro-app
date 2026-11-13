# Arquitectura (propuesta)

*Todo este archivo es conocimiento general, sin verificar: una propuesta para empezar a construir,
no una decisión. Las integraciones dependen de las [preguntas abiertas](PREGUNTAS_ABIERTAS.md).*

## Componentes

| Componente | Qué hace | Depende de |
| --- | --- | --- |
| App móvil | registro, envío, elegir cuenta, saldo de dos bolsas, proyección, opciones de inversión | — |
| Servicio de envío | mueve la remesa EE. UU. → México con el socio regulado; stablecoin o riel tradicional | preguntas 3 y 6 |
| Motor de ahorro | calcula el aporte de cada envío, lo reparte entre bolsa de emergencia y bolsa de retiro según la meta | R2, R4 |
| Conexión con la Afore | deposita la bolsa de retiro en la cuenta elegida, por AforeMóvil o PROCESAR | preguntas 1, 4 y 5 |
| Bolsa de emergencia | dentro de la Afore (subcuenta de corto plazo) o fuera, con un socio | pregunta 4 |
| Proyección | simula muchos escenarios y muestra un rango, descontando comisiones | R6 |
| Inversión | asigna según la edad u opción elegida; la estrategia creada solo con sus cifras del Backtest Engine | R7, pregunta 2 |
| Registro de eventos | guarda lo que piden las métricas, con el brazo del piloto | `METRICAS.md` |

## Principios

- **No construir lo que ya existe:** el depósito y la custodia en México ya los dan las Afores y
  PROCESAR, con aportes desde USD 5,37 (PPA) y sin comisión por débito en AforeMóvil (Azuara et al.
  2021, pp. 42, 46–47). La app aporta volumen y facilidad, no administración.
- **El piloto sin dinero real primero:** registrar la elección de la persona antes de mover dinero
  mientras falte la regulación (ver `PILOTO_AB.md`).
- **Parámetros, no constantes:** el porcentaje por omisión, la meta de la bolsa de emergencia y los
  brazos del piloto se configuran sin cambiar código.
- **Secretos fuera del código:** llaves y tokens en variables de entorno, nunca en el repositorio.
