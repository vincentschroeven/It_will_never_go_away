# It will never go away

Browserclip voor **Das Island – 07. It will never go away** (2:55).

Je drijft over een eiland in de stijl van Proteus: low-poly bloesembomen, de hele beeldvulling gedithered naar een klein pastelpalet, pixelwolken, en licht dat van ochtend naar nacht gaat. Alles loopt synchroon met het nummer.

Open `index.html` in een browser en druk op Play. Sleep om een beetje rond te kijken.

## Tijdlijn

| Tijd | Wat er gebeurt |
|---|---|
| 0:00 | Hoog in de lucht, boven het eiland |
| 0:28 | Duik naar beneden |
| 0:30–0:38 | Een school vissen die in de lucht zwemt en uiteenzwemt |
| 1:01–1:27 | Zomerwind: je wordt de lucht in geblazen met bloemblaadjes, het pad verschijnt; op 1:27 sta je op het pad |
| 1:40 | Je stijgt naar de sterren |
| 1:50 | Vanuit de hoogte naar beneden kijken |
| 1:52–1:59 | Terug zakken naar het pad |
| 2:00–2:30 | Storm met vuurvliegjes, je bent een speelbal van de wind |
| 2:30 | Alles valt stil; je drijft langzaam weg, het pad centraal, tussen de sterren en het eiland |

## Techniek

- Eén HTML-bestand, [three.js](https://threejs.org) r149 via jsDelivr
- Lage resolutie (1/3) met harde pixels, Bayer-dither naar een palet van 13 kleuren dat met de tijd meeschuift
- De tijdlijn staat bovenaan het script in `TL` (tijden in seconden)
- `song.mp3` stuurt alles aan via `audio.currentTime`
