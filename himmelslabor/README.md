# Himmelslabor

Physik, Mathematik und Erdkunde: Erde, Mond, Sonne und Planeten in echten Größen und Abständen, für jeden Zeitpunkt von 2000 bis 2050. Alles wird im Gerät berechnet – keine Daten aus dem Internet.

- **Live:** zeigt genau den jetzigen Stand und läuft mit der Uhr mit (Datum und Uhrzeit mit Sekunden).
- **Reise & Ansicht:** per Knopf und Entfernungsregler zu Erde, Mond, Sonne, Planeten, ISS und Voyager fliegen; Blick vom Mond zur Erde, Fernrohr-Blick von der Erde zu Mond und Sonne; Zeit in Echtzeit, beschleunigt oder rückwärts.
- **Finsternisse 2000–2050:** alle Sonnen- und Mondfinsternisse mit Typ, Dauer, Pfadbreite, Kernschattenpfad auf der Karte, Bedeckung für den eigenen Ort; Ansicht aus dem All (wandernder Schatten, Schattenkegel) und von der Erde (Korona, roter Mond).
- **Tag, Monat, Jahr:** Sterntag und Sonnentag, siderischer und synodischer Monat (Zeiger-Demos), Zeitgleichung und Analemma, Präzession, ΔT.
- **Jahreszeiten:** Termine 2000–2050, Perihel/Aphel, Tageslänge und Mittagshöhe für wählbare Orte.
- **Gezeiten:** Flutberge (überhöht), Spring- und Nippflut, Gezeitenbeschleunigung von Mond und Sonne.
- **Satelliten & Sonden:** ISS, Hubble, GPS, geostationär (Kepler III), Voyager 1 und 2 mit Lichtlaufzeit (Voyager 1 am 18.11.2026 einen Lichttag entfernt).
- **Mondmission:** Startgeschwindigkeit durch die Erddrehung, numerisch berechneter Flug mit Swing-by und freier Rückkehr (Artemis II nachfliegen), Einbremsen am Mond, Mini-Spiel weiche Landung, Ausblick Artemis III/IV.
- **Drei Körper:** Mondbahn um die Sonne, Lagrange-Punkte mit Testteilchen, Achter-Choreografie, Chaos (Burraus 3-4-5-Problem).
- **Wie genau?** Genauigkeit aller Rechnungen mit Vergleichswerten (NASA, Meeus).

- **Live-Adresse:** https://schulapplikationen.github.io/physik-apps/himmelslabor/
- **QR-Code für die Klasse:** `qr_himmelslabor.png`
- **Aktuelle Version:** `index.html` (Stand 2026-11-09, Fassung 02)
- **Versionen:** Ordner `versionen/` – jede Fassung als `JJJJ-MM-TT_NN_himmelslabor.html`, die neueste ist identisch mit `index.html`.

Rechenverfahren: Mond nach ELP-2000/82 (Meeus), Sonne nach VSOP87 (gekürzt), Planeten nach JPL-Keplerelementen (Standish, 1800–2050), Finsternisse aus der Schattengeometrie mit abgeplatteter Erde.
Mondkarte: NASA Scientific Visualization Studio, CGI Moon Kit (LRO). Ländergrenzen: Natural Earth (gemeinfrei). Zeichnen mit d3-geo (ISC-Lizenz) und WebGL.

Datenschutz: Die App läuft komplett im Browser, sendet nichts und lädt nichts nach.

Erstellung unterstützt von Claude.
