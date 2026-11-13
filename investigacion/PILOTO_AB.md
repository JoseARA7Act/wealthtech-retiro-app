# Piloto A/B

*Diseño en palabras, 2026-11-03. Escrito antes de correrlo. Los cálculos —el efecto mínimo y el
tamaño de muestra— van en `demo/`, con una herramienta.*

## La pregunta

¿Qué versión del producto hace que más personas que envían remesas aparten dinero para su retiro, y
que lo sigan haciendo?

## Diseño

- **Unidad:** cada persona que envía, asignada al azar en su primer envío. La familia receptora queda
  en el mismo brazo, para no mezclar.
- **Brazos:** pocos, y cada uno cambia una sola cosa frente al control. Por decidir si son dos o
  tres.
  - **A, control:** la opción de apartar existe, apagada.
  - **B, por omisión:** el apartado viene prendido y se puede quitar.
  - **C, con match:** como A, más un pequeño complemento pagado con el ahorro en costos.
- **En todos los brazos** se pregunta en qué cuenta va el ahorro, la de quien envía o la de quien
  recibe: se **mide**, no se asigna.

## Medidas, fijadas antes

- Adopción: quién aparta algo en sus primeros envíos.
- Persistencia a 3 y 6 meses: Mbao (Kenia) perdió 34 % de sus miembros activos y 27 % de
  los aportes de 2015 a 2016 (Guven 2019, p. 37).
- Monto por envío y acumulado.
- Cuenta elegida.
- Retiros anticipados.
- Quién deja de enviar por la app.

## Éxito y fin, escritos antes

El efecto mínimo que importa y la muestra para verlo. Punto de partida: la disposición **declarada**
a aportar a una pensión, 20.3 % de los migrantes y 23.4 % de quienes envían remesas (Cervantes
González 2018, pp. 54–55). Es lo que la gente dice, no lo que hace; los pilotos previos muestran que
la distancia es grande (ver [`EVIDENCIA.md`](EVIDENCIA.md#por-qué-fallaron-los-intentos-previos)).

## Para leer el resultado

- «No rechazar no es aceptar»: un piloto chico que no encuentra efecto no prueba que no lo haya
  (Klugman, Panjer & Willmot 2019, cap. 10, pp. 242–244).
- Si se prueban suficientes variantes, una se verá bien aunque no lo sea (cap. 15, p. 389): pocos
  brazos, y todos contados, también los que fallan.
- Una población nueva tiene poca experiencia propia (cap. 16, pp. 408–409): leer con cautela antes
  de escalar.

## Riesgos

- Exigir cuenta bancaria en México deja fuera a la mayoría: el 95.1 % cobra en efectivo (Cervantes
  González 2018, pp. 56–57).
- La receptora también es usuaria: 58.4 % son mujeres (Serrano Herrera & Fernández de Castro,
  p. 24).
- Hay que operar en las noches y los fines de semana: el 48 % envía entre las 5 y las 11 pm
  (pp. 33–34).
- El dinero real solo pasa por un socio regulado, como en CONSAR-BID-Yastás (CONSAR 2020).
- **Una opción mientras falta la regulación:** un piloto de intención —la persona elige y se mide su
  elección, sin dinero real todavía—, con el depósito después.
