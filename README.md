# Trading-Strategy
Este repositorio contiene una estrategia de trading diseñada para operar en el mercado Forex, enfocándose específicamente en el par EUR/USD. La estrategia está optimizada para marcos temporales de corto plazo (5, 10 y 15 minutos), ideal para traders intradía.

## Componentes Principales:

Medias Móviles (Moving Averages): Se utilizan medias móviles exponenciales (EMA) de diferentes períodos para identificar tendencias y posibles puntos de entrada o salida. Las cruces de medias y su alineación en función del precio juegan un papel clave en la confirmación de tendencias.

Smart Money Concept (SMC): La estrategia sigue los principios del smart money, que se enfoca en identificar áreas donde los grandes operadores financieros (bancos, instituciones) entran al mercado. Se busca la manipulación del precio, las zonas de desequilibrio y el comportamiento institucional para optimizar entradas y salidas.

Swings de Liquidez: Los swings de liquidez se utilizan para identificar niveles clave donde se acumulan órdenes de stop-loss (por ejemplo, por encima de máximos o por debajo de mínimos significativos). La estrategia se apalanca en estos puntos de liquidez para detectar falsos rompimientos y aprovechar los movimientos impulsivos.

Volumen: El volumen es un factor crucial en la confirmación de movimientos y patrones de precio. Se implementan herramientas de análisis de volumen para identificar divergencias y confirmar la validez de las rupturas y retrocesos.

## Objetivo:

El objetivo de la estrategia es identificar oportunidades de alta probabilidad en los puntos clave de intersección entre las sesiones de Nueva York y Londres, momentos en los que la volatilidad tiende a aumentar, proporcionando mejores oportunidades para operaciones en corto plazo.

## Implementación:

La estrategia está programada utilizando PineScript en la plataforma de TradingView, lo que permite la automatización de las señales de entrada y salida. Además, se incluyen ejemplos de backtesting para evaluar la efectividad de la estrategia en diferentes condiciones de mercado.

Este repositorio es ideal para traders que buscan explotar las ineficiencias del mercado Forex a través de una combinación de análisis técnico y principios institucionales.
