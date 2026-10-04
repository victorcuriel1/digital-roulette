# Ruleta Digital

Proyecto de Diseño Lógico Digital basado en la construcción de una ruleta electrónica de 25 LEDs utilizando circuitos integrados y lógica digital.

Al accionar un pulsador, un temporizador NE555 genera una secuencia de pulsos que alimenta a contadores CD4017. Las salidas de los contadores se activan secuencialmente, produciendo el efecto visual de una ruleta.

## Componentes principales

- Temporizador NE555
- 3 contadores CD4017
- Compuertas AND 74LS08
- Transistores 2N3904
- 25 LEDs
- Resistencias y capacitores
- Pulsador

## Funcionamiento

El NE555 funciona como generador de pulsos de reloj.

Estos pulsos son enviados a los contadores CD4017, conectados en cascada mediante lógica combinacional, permitiendo ampliar progresivamente el circuito desde 9 hasta 25 salidas.

Flujo general del sistema:

`Pulsador → NE555 → Contadores CD4017 → Lógica AND → LEDs`

El circuito final utiliza tres contadores para controlar las 25 posiciones de la ruleta.

## Desarrollo

Durante el proyecto se realizaron tres etapas principales:

- Ruleta de 9 salidas con un contador.
- Ruleta de 17 salidas con dos contadores.
- Ruleta final de 25 salidas con tres contadores.

También se desarrolló una simulación adicional con visualizadores de 7 segmentos para indicar el número correspondiente al LED activo.

## Implementación

El circuito fue diseñado y simulado antes de realizar el montaje físico sobre protoboard.

También se desarrolló un diseño de PCB como parte del proceso de diseño electrónico.

## Documentación

El informe completo del proyecto está disponible aquí:

[Ver informe del proyecto](docs/Proyecto_RuletaDigital.pdf)

## Autores

- Victor Gabriel Curiel Gonzalez
- Ximena Lujan Quenhan Riveros

Universidad Nacional de Asunción  
Facultad de Ingeniería  
Ingeniería Mecatrónica

## Licencia

Este proyecto está distribuido bajo la licencia MIT.
