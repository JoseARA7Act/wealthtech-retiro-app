# WealthTech Retiro — la app

Repositorio de **desarrollo** del producto: qué construir, por qué y qué falta resolver. La
investigación —evidencia, fuentes, piloto A/B— vive en el repositorio hermano
[`wealthtech-retiro`](https://github.com/JoseARA7Act/wealthtech-retiro).

## El producto en tres líneas

Una app para personas migrantes en EE. UU. que envían remesas a México. Cada envío puede apartar
una parte pequeña, en automático, para el ahorro de retiro de quien envía o de quien recibe. El
ahorro tiene una bolsa de emergencia y una de retiro, y se invierte según la edad.

## Qué leer, en orden

| Archivo | Qué es |
| --- | --- |
| [`CONTEXTO.md`](CONTEXTO.md) | el problema, los usuarios, el mercado y la idea de José |
| [`ESPECIFICACION.md`](ESPECIFICACION.md) | el MVP: flujos de usuario y requisitos numerados |
| [`DECISIONES.md`](DECISIONES.md) | lo que decidió José y lo que recomienda la evidencia, separado |
| [`PREGUNTAS_ABIERTAS.md`](PREGUNTAS_ABIERTAS.md) | lo que bloquea construir, y a quién preguntarlo |
| [`METRICAS.md`](METRICAS.md) | qué medir desde el primer día |
| [`ARQUITECTURA.md`](ARQUITECTURA.md) | una propuesta de componentes, sin verificar |
| [`CONOCIMIENTO.md`](CONOCIMIENTO.md) | lo que dice cada fuente leída, útil para diseñar |

## Cómo marcamos lo que sabemos

- **Con fuente y página:** viene de una fuente leída; la referencia completa está en
  [`FUENTES.md`](https://github.com/JoseARA7Act/wealthtech-retiro/blob/main/FUENTES.md) del
  repositorio de investigación.
- ***Conocimiento general, sin verificar*:** viene del conocimiento general del asistente, no de
  una fuente leída. Sirve para orientar, no para decidir; antes de construir sobre ello, hay que
  confirmarlo.
- **Decisión de José:** está en `DECISIONES.md`, con sus palabras.

## Cómo trabajamos

- Una rama por tarea y un pull request antes de unir a `main`.
- José aprueba los cambios a `DECISIONES.md`.
- **Nada de secretos:** ninguna llave, token o contraseña en el repositorio; `.env` está excluido.
- Nada de dinero real hasta que el socio regulado y el piloto estén definidos.
- **No se promete ganarle al mercado.** La estrategia creada se muestra con sus cifras de riesgo.
