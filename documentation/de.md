<!-- ELUCENIA technical documentation · nexus-coluna-cervical · de · no clinical/professional/rights approval -->

# NEXUS-Kriterien (Halswirbelsäule)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/nexus-coluna-cervical)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Druckschmerz über der hinteren Mittellinie der Halswirbelsäule

`dor`

### Fokales neurologisches Defizit

`deficit`

### Veränderte Bewusstseinslage

`alerta`

### Hinweise auf Intoxikation

`intox`

### Schmerzhafte ablenkende Verletzung (z. B. Röhrenknochenfraktur, großflächige Verbrennung)

`distrativa`

## Fassung der Methode

NEXUS/Hoffman 2000: 5 Niedrigrisikokriterien; originale HWS-Regel

## Dokumentierte Formel

Bildgebung kann entfallen, wenn alle Kriterien erfüllt sind: kein hinterer Mittelliniendruckschmerz, kein fokal-neurologisches Defizit, normales Bewusstsein, keine Intoxikation oder schmerzhafte ablenkende Verletzung. Ein positiver Befund erfordert Bildgebung.

## Grenzen und Population

Die NEXUS-Regel 2000 wurde bei Patienten mit Halswirbelsäulenröntgen nach stumpfem Trauma untersucht. Eine Einordnung als geringe Wahrscheinlichkeit erfordert alle fünf Kriterien gleichzeitig; die Studie berichtete von durch die Regel übersehenen Verletzungen, daher gewährleistet ein negatives Ergebnis keine Verletzungsfreiheit. Alter, Ausschlüsse und Anwendung in Untergruppen müssen im vollständigen Protokoll geprüft werden.

## Referenzen

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
