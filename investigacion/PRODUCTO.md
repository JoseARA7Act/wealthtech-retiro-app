# El producto

*Borrador de trabajo, 2026-11-03. Punto de partida para el documento de producto, no el documento.*

## La idea, en palabras de José

> Mi borrador del plan principal es este, una quiero tener un producto de ahorro voluntario donde se utilice la estrategia creada para generar exceso de retorno ganándole al mercado, eso para cualquier usuario pueda acceder y también que sea accesible es decir que incluso se pueda agregar micro aportes, ahora también una problemática aparte que le dara el un plus es ademas de las personas que ya cotizan, es agregar también personas de la informalidad, por el momento nos centramos en las personas migrantes, es decir también la aplicación además de servir para el ahorro voluntario, servirá para el envió de remesas usando stable coins para reducir los costos de transacción, ahora cada vez que se mande dinero se va a tomar una pequeña comisión para que se invierta en el fondo del retiro de la persona, además de agregar la opción de ahorro voluntario, tipo no desea agregar un 10% del total del dinero enviado para su afore? y le ponemos cuanto ganaría si hace ese dinero mensualmente o semanalmente, tipo si sigue aportando podría tener hasta xxx cantidad de dinero para su retiro, eso para incentivar el ahorro. ahora también agregaremos contratos inteligentes por si necesitan sacar su afore en caso de cualquier imprevisto que el manual de afores contempla, ahora también supongo que se daría mas facilidad que el dinero que se quede de la comisión o del ahorro se quede en dólares, para una mejor integración de la estrategia, también se va a conectar dependiendo de la edad de la persona, ya sea por el momento 3 opciones Cripto es decir se mantiene el la stable coin establecida para ya no hacer el cambio, renta variable donde se aplicara nuestra estrategia o tambien la opción del S&P 500 y renta fija donde se aplicara bonos o Bonos de micro ahorró (M-savings bonds) o fibras o cualquier Fintech que ofrezca renta fija. Ahora para un futuro podemos agregar incentivos para motivar a las personas a ahorra voluntariamente para su afore, digamos incetivos de microaseguros Hipotecas y vivienda: Esquemas de crédito y ahorro (como el programa Pag-IBIG en Filipinas o Tu Vivienda en México), tandas o cualquier otra cosa

**Mercado:** México, con las Afores. **Universo invertible:** EE. UU. **Comparado contra:** las
Afores y el mercado de EE. UU.

## Las piezas

1. Ahorro voluntario, con micro aportes, para quien cotiza y para quien está en la informalidad,
   empezando por personas migrantes.
2. Remesas en stablecoins, con una pequeña comisión de cada envío que va al fondo de retiro.
3. Un empujón: «¿no desea agregar un 10 % del total enviado para su Afore?», con cuánto tendría si
   aporta cada mes o cada semana.
4. Contratos inteligentes para retiros por imprevistos, los que contempla la regulación de Afores.
5. El ahorro se queda en dólares.
6. Según la edad, tres opciones: cripto (la stablecoin), renta variable (la estrategia propia, o el
   S&P 500) y renta fija (bonos, M-savings bonds, fibras o una fintech).
7. A futuro: microseguros, hipoteca y vivienda (Pag-IBIG, Tu Vivienda), tandas.
8. Una opción que pregunta en qué cuenta va el ahorro: la de quien envía o la de quien recibe.

## Lo decidido (2026-11-03)

- **Dólares**, en palabras de José: «en dolares o pesos es mejor dolares». Ver la objeción en
  [`EVIDENCIA.md`](EVIDENCIA.md#dólares-o-pesos).
- **Elegir la cuenta:** «vamos a hacer que tenga una opción que pregunte en que cuanta quiere hacer
  el ahorro en el que envía el dinero o quien la revise» (leído como *quien la recibe*).

- **Estrategia creada, sin promesa** (2026-11-12), en palabras de José: «no podemos hacer la
  promesa pero si tnemos que usar una estrategia creada». Parte del hackathon es desarrollar una
  estrategia que genere exceso de retorno.

## Abierto

- **Si la estrategia creada le gana al mercado.** Hoy la estrategia propia no supera al mercado ni
  al S&P 500 por riesgo (ver [`EVIDENCIA.md`](EVIDENCIA.md#ganarle-al-mercado)). Se decide con una
  prueba escrita antes, con costos, y sus cifras vienen del Backtest Engine.
- **Moneda.** Si una Afore puede recibir y guardar dólares, o solo pesos, y quién carga la
  conversión. Por verificar con CONSAR.
- **Dónde se invierte el ahorro:** en la subcuenta de la Afore o en un vehículo aparte. De eso
  depende si la estrategia propia entra.
- **Aportaciones de terceros y retiros parciales:** qué permite la ley del SAR.
- **Stablecoins en México:** qué puede ofrecer una fintech con activos virtuales (Banxico, Ley
  Fintech).
- **Micro aportes:** con unos dólares no se compran 20 acciones enteras; hace falta un fondo común o
  acciones fraccionadas.
- **La proyección «podría tener hasta xxx»:** mostrar un rango con sus supuestos, no una sola cifra.
