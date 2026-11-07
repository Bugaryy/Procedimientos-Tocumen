# ✈️ Vuelo ATC 3D · Tocumen (MPTO)

**Simulador web 3D de procedimientos IFR del Aeropuerto Internacional de Tocumen, para aprender a leer las cartas del AIP Panamá.**

Creado por **Derek Cuan · "Delta Charlie"** — [github.com/Bugaryy](https://github.com/Bugaryy)

> Herramienta educativa. No usar para operaciones reales: consulte siempre el AIP y los NOTAM vigentes.

---

## ¿Qué es?

Vuelo ATC 3D recrea en 3D los procedimientos publicados en el **AIP Panamá, AD 2.1-MPTO**, y los vuela con un modelo de vuelo que respeta altitudes, velocidades y virajes. Está pensado para estudiantes de control de tránsito aéreo y para instructores: cada simulación indica **en qué página del AIP** (y del PDF) está la carta que se está volando.

## Funciones

- **Fases de vuelo:** en ruta, llegada (STAR), aproximación inicial, intermedia y final, aproximación frustrada, esperas y circuito de tránsito.
- **Todos los procedimientos del AD 2.24:**
  - 8 aproximaciones: ILS CAT I 03R, ILS Y 03R, VOR/DME 21L, VOR/DME 03L, RNP 03R, RNP 03L, RNP 21R (LNAV) y RNP Z 21R (AR) con sus 10 transiciones
  - 20 llegadas: SIRIL, VUMAN, ISOKO, OSUPA, MEVID y LODOP
  - 12 salidas: SIMAN, DABEL, EGETA, DANDA, REMAL y ANGUD
  - las esperas publicadas en las cartas
- **Buscar AIP:** busca por nombre, punto, pista o número de página (AD 2.1-xx o página del PDF). Puedes marcar varios procedimientos, verlos juntos en el mapa o simular uno.
- **Aprender:** explica paso a paso cada tramo, el papel de cada punto (IAF, IF, FAF, MAPt…) y dónde está en la carta. Incluye un modo instructor que pausa la simulación en los puntos clave.
- **Escenario 3D:** relieve de Panamá, ortofoto de Tocumen, modelo del aeródromo, CTR/ATZ y los obstáculos del AD 2.10.
- **Cámaras:** libre (orbital), persecución, cabina, torre y vista superior. Al tocar el avión, la cámara lo sigue.
- **Radar, perfil vertical y radio:** pantalla tipo radar, perfil de descenso con la DA/MDA y registro de comunicaciones.
- Funciona en computadora y en celular.

## Uso

Abre `index.html` en cualquier navegador moderno. Todo va en un solo archivo y no requiere instalación ni servidor.


## Fuentes

- **AIP Panamá · AD 2.1-MPTO** (AIS Panamá): cartas IAC, SID y STAR, tablas de codificación, AD 2.10, AD 2.22 y AD 2.24.
- **Meteo ATC 3D**, del mismo autor: relieve, ortofoto y modelo del aeródromo.
- [Three.js](https://threejs.org) r160 (MIT) · [world-atlas](https://github.com/topojson/world-atlas) (ISC) / Natural Earth.

## Licencia

© 2026 **Derek Cuan (Delta Charlie)**. Todos los derechos reservados.
Se permite usarlo en el navegador para estudio personal y en clases. Para copiarlo, modificarlo o redistribuirlo hace falta permiso del autor. Ver [LICENSE](LICENSE).

---

<sub>Hecho en Panamá 🇵🇦 por Delta Charlie · [github.com/Bugaryy](https://github.com/Bugaryy)</sub>
