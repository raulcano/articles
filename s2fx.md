# S2FX: El Modelo S2F de Bitcoin con Activos Cruzados

NOTA: Este artículo es una traducción del texto original de PlanB - "[Bitcoin Stock-to-Flow Cross Asset Model](https://medium.com/@100trillionUSD/bitcoin-stock-to-flow-cross-asset-model-50d260feed12)"

---

*"Lo importante en ciencia no es tanto obtener nuevos datos como descubrir nuevas maneras de pensar sobre ellos" William Lawrence Bragg*

## Introducción

El modelo Stock-to-Flow (S2F) de bitcoin (BTC) fue [publicado en Marzo de 2019](https://medium.com/@100trillionUSD/modeling-bitcoins-value-with-scarcity-91fa0fc03e25) [1].

El modelo original BTC S2F es una fórmula basada en el S2F mensual y precio del BTC. Ya que los datos de muestra estaban indexados cronologicamente, es un modelo de serie temporal. Este modelo ha activado a analistas cuantitativos de todo el mundo. Muchos han verificado la relación no espúrea entre S2F y el precio de BTC [2][3][4][5].

![Modelo S2F actual](./images/s2fx-1.png "Modelo S2F actual")

*Modelo S2F actual*


Si no estáis familiarizados con el modelo S2F, recomiendo encarecidamente leer el artículo original, pues ahí se explica el trasfondo y la terminología.

En este artículo cimento la base del modelo S2F actual al quitar el factor tiempo y añadir otros activos (plata y oro) al modelo. A éste, lo llamo S2FX: el modelo S2F de Bitcoin con activos cruzados. S2FX permite la valoración de distintos activos como la plata, el otro y el BTC con una sola fórmula.

Primero, describiré el concepto de transiciones de fase, ya que, introduce una nueva manera de pensar sobre BTC y S2F. Esto explica porqué el modelo S2FX es importante.

Segundo, describiré el modelo S2FX, cómo funciona y qué significan los resultados.

## Transiciones de fase

Las transiciones de fase dan una perspectiva importante para entender el modelo S2FX. Durante las transiciones de fase, las cosas ganan propiedades totalmente diferentes. Las transiciones son frecuentemente discontinuas. Tres ejemplos de transiciones de fase son:
- Agua
- El dólar (USD)
- BTC

### Agua
El ejemplo clásico de transición de fase es el agua. El agua existe en cuatro fases distintas (estados): sólido, líquido, gas e ionizado. Todos son agua, pero en cada fase el agua tiene propiedades totalmente distintas.

![Transición fase del agua](./images/s2fx-2.png "Transición fase del agua")

### El dólar (USD)
Las transiciones de fase también están presentes en las finanzas. Por ejemplo, el dólar USD ha transicionado desde la moneda de oro (1 dólar = 371.25 granos de plata pura = 24 granos de oro), hacia papel respaldado por oro ("Pagable al portador en monedas de oro bajo demanda"), hacia papel no respaldado por nada ("Este billete es moneda legal para todas las deudas públicas y privadas"). Aunque lo sigamos llamando dólar USD, el dólar tiene propiedades totalmente diferentes en estas tres fases.

![Transición fase del dolar](./images/s2fx-3.png "Transición fase del dolar")

### BTC
Lo mismo es cierto para el BTC. Nic Carter y Hasu muestran en su estudio de 2018 cómo las narrativas sobre BTC han cambiado con el tiempo [6].

![Transición fase del BTC](./images/s2fx-4.png "Transición fase del BTC")
*[Cómo las mayores narrativas sobre Bitcoin han cambiado con el tiempo](https://medium.com/@nic__carter/visions-of-bitcoin-4b7b7cbcd24c)*

Estas narrativas sobre el BTC parecen bien continuas en la gráfica. Sin embargo, si combinamos las narrativas con los hitos financieros (y luego los datos de S2F y de precio), se tornan bien parecidas a fases con transiciones más abruptas:  

- "Prueba de concepto" -> Tras el "white paper" de Bitcoin [7]
- "Pagos" -> tras la paridad con el dólar USD (1BTC = 1USD)
- "Oro electrónico" -> tras el primer "halving", paridad casi completa con el oro (1BTC = 1 onza de oro)
- "Activo financiero" -> tras el segundo "halving" (hito de 1000 millones de USD en transacciones diarias, claridad legal en Japón y Australia, mercados de futuros en CME y Bakkt)

Estos tres ejemplos de transiciones de fase en el agua, el dólar USD y en BTC ofrecen una nueva perspectiva para BTC y S2F. Es importante pensar no sólo en términos de series temporales continuas sino también en fases con transiciones abruptas. Al desarrollar el modelo S2FX, veo BTC como un activo distinto en cada fase, con propiedades completamente distintas. El siguiente paso lógico es identificar y cuantificar las transiciones de fase de BTC.

## S2FX: el modelo S2F de BTC con activos cruzados


...










## Conclusión

En este artículo cimiento la base del modelo S2F actual quitando el factor tiempo y añadiendo otros activos (plata y oro) al modelo. A éste, lo llamo S2FX: el modelo S2F de Bitcoin con activos cruzados. S2FX permite la valoración de distintos activos como la plata, el otro y el BTC con una sola fórmula.

He explicado el concepto de transición de fase. Las transiciones de fase introducen una nueva manera de pensar sobre BTC y S2F, lo cual me llevó al S2FX.

La fórmula del modelo S2FX se ajusta perfectamente a los datos (99.7% R2).

El modelo S2FX estima un valor de mercado en la próxima fase/clúster (el S2F de BTC será 56 en 2020-2024) de $5.5 billones. Esto se traduce en un precio por BTC (con unos 19 millones de BTC en 2020-2024) de $288,000.

Solidificando los hechos conocidos del estudio original sobre S2F, el modelo S2FX ofrece una nueva forma de pensar acerca de BTC transitando hacia la quinta fase.

## Referencias

[1] [PlanB@100trillionUSD](https://twitter.com/100trillionUSD), [Modeling Bitcoin’s Value with Scarcity](https://medium.com/@100trillionUSD/modeling-bitcoins-value-with-scarcity-91fa0fc03e25), Mar 2019

[2] [Nick Emblow](https://twitter.com/btconometrics), [Falsifying Stock-to-Flow As a Model of Bitcoin Value](https://medium.com/swlh/falsifying-stock-to-flow-as-a-model-of-bitcoin-value-b2d9e61f68af), Aug 2019

[3] [Marcel Burger](https://twitter.com/BurgerCryptoAM), [Reviewing “Modelling Bitcoin’s Value with Scarcity”](https://medium.com/burgercrypto-com/reviewing-modelling-bitcoins-value-with-scarcity-part-ii-the-hunt-for-cointegration-66a8dcedd7ef), Sep 2019

[4] Mannuel Andersch, Is Bitcoin outshining gold?, Sep 2019

[5] Nick Emblow, Stock-to-Flow Influences on Bitcoin Price, Mar 2020

[6] Nic Carter, Hasu@Hasufl, Visions of Bitcoin — How major Bitcoin narratives changed over time, Jul 2018

[7] https://bitcoin.org/bitcoin.pdf — Satoshi Nakamoto, 2008

[8] [Jan Nieuwenhuijs, How Much Silver Is Above Ground?](https://twitter.com/JanGold_), Dec 2019