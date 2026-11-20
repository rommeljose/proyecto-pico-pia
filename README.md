# Proyecto Pico-Pia

Estaciones sismológicas de bajo costo para el estado Sucre (Venezuela), y su
primer prototipo funcionando en banco de pruebas.

**Página del proyecto:** https://rommeljose.github.io/proyecto-pico-pia/

Este repositorio reúne la información pública del proyecto y sus avances.

## Qué hay

| Fichero | Qué es |
|---|---|
| `index.html` | La página: por qué hacen falta estaciones locales, el prototipo y su registro, créditos y fotos |
| `datos.json` | Muestra real de 12 h de registro del prototipo (20 de noviembre de 2026) |
| `img/` | Fotos del prototipo |

## Estado

- **Funcionando:** registro continuo y automático, miniSEED, servicios FDSN y
  SeedLink, recuperación sola tras cortes de luz, acceso remoto cifrado.
- **En construcción:** la publicación automática de la traza en esta página cada
  2 minutos. Mientras tanto, la página muestra un registro de muestra.
- **Falta:** sincronización por GPS con PPS, un sensor calibrado y un sitio
  adecuado (planta baja, suelo firme).

Los detalles técnicos de la tarjeta y del conversor están en
[pico-pi-imx7d](https://github.com/rommeljose/pico-pi-imx7d).

## Avances

- **2026-11-20** — Primera versión pública de la página.

## Responsable

Licenciado Físico Rommel Contreras.

## Licencia

Textos, fotos y datos: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es).
Código de la página: MIT.
