<!-- ELUCENIA technical documentation · grau-de-perda-auditiva · de · no clinical/professional/rights approval -->

# Reintondurchschnitt und Grad des Hörverlusts (WHO 2021)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/grau-de-perda-auditiva)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Rechtes Ohr · 500 Hz

`od500`

dB HL · Bereich: -10–120

### Rechtes Ohr · 1.000 Hz

`od1k`

dB HL · Bereich: -10–120

### Rechtes Ohr · 2.000 Hz

`od2k`

dB HL · Bereich: -10–120

### Rechtes Ohr · 4.000 Hz

`od4k`

dB HL · Bereich: -10–120

### Linkes Ohr · 500 Hz

`oe500`

dB HL · Bereich: -10–120

### Linkes Ohr · 1.000 Hz

`oe1k`

dB HL · Bereich: -10–120

### Linkes Ohr · 2.000 Hz

`oe2k`

dB HL · Bereich: -10–120

### Linkes Ohr · 4.000 Hz

`oe4k`

dB HL · Bereich: -10–120

## Fassung der Methode

WHO 2021 World Report on Hearing: PTA 4 Frequenzen 500/1000/2000/4000, besseres Ohr; PTA 3 separat

## Dokumentierte Formel

Vierfrequenzmittelwert (WHO) = mittlere Luftleitungsschwellen bei 500, 1.000, 2.000 und 4.000 Hz. Dreifrequenzmittelwert = Mittelwert bei 500, 1.000 und 2.000 Hz (traditionelle Klassifikationen wie Lloyd und Kaplan).

Der WHO-Grad wird durch den Vierfrequenzmittelwert des besseren Ohrs definiert.

## Grenzen und Population

Die hier verwendete WHO-Klassifikation von 2021 nutzt den Mittelwert von 500, 1000, 2000 und 4000 Hz im besseren Ohr und die Schweregrade für Erwachsene; der separat angezeigte Mittelwert aus drei Frequenzen darf nicht mit dieser Methode verwechselt werden. Die Schwellen müssen aus einer geeigneten Audiometrie stammen und in dB HL, auch dB NA genannt, angegeben werden. Der numerische Schweregrad allein beschreibt weder Kommunikationsfähigkeit noch Kontext oder Rehabilitationsbedarf; die WHO selbst weist auf diese Einschränkung hin. Einseitiger Hörverlust und pädiatrische Anwendung erfordern eine spezifische Interpretation und dürfen nicht aus der Gesamteinstufung für Erwachsene abgeleitet werden.

## Referenzen

- [Chadha S, Kamenov K, Cieza A. The world report on hearing, 2021. Bull World Health Organ, 2021.](https://doi.org/10.2471/BLT.21.285643)

- [Organização Mundial da Saúde. World report on hearing, 2021.](https://www.who.int/publications/i/item/9789240020481)

- [WHO2021,WorldReportOnHearing,ISBN978-92-4-002048-1,primary-content mirror](https://soundhearing2030.org/pdf/World%20report%20on%20hearing.pdf)

- [WHO2021 official archive](https://iris.who.int/bitstream/handle/10665/339913/9789240020481-eng.pdf)

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

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Grad nach dem besseren Ohr (WHO 2021): leichte Hörminderung

| Ergebnisdetails | |
| --- | --- |
| Rechtes Ohr (Vierfrequenztöne) | 27,5 dB · leichte Hörminderung |
| Linkes Ohr (Vierfrequenztöne) | 37,5 dB · mäßige Hörminderung |
| Dreifrequenz-Mittelwert (500, 1k, 2k) rechtes Ohr / linkes Ohr | 25,0 / 35,0 dB |


### 2

Grad nach dem besseren Ohr (WHO 2021): normales Hörvermögen

| Ergebnisdetails | |
| --- | --- |
| Rechtes Ohr (Vierfrequenztöne) | 10,0 dB · normales Hörvermögen |
| Linkes Ohr (Vierfrequenztöne) | 10,0 dB · normales Hörvermögen |
| Dreifrequenz-Mittelwert (500, 1k, 2k) rechtes Ohr / linkes Ohr | 10,0 / 10,0 dB |


### 3

Einseitige Hörminderung (besseres Ohr < 20 dB und schlechteres ≥ 35 dB)

| Ergebnisdetails | |
| --- | --- |
| Rechtes Ohr (Vierfrequenztöne) | 13,8 dB · normales Hörvermögen |
| Linkes Ohr (Vierfrequenztöne) | 48,8 dB · mäßige Hörminderung |
| Dreifrequenz-Mittelwert (500, 1k, 2k) rechtes Ohr / linkes Ohr | 11,7 / 45,0 dB |


### 4

Grad nach dem besseren Ohr (WHO 2021): schwere Hörminderung

| Ergebnisdetails | |
| --- | --- |
| Rechtes Ohr (Vierfrequenztöne) | 77,5 dB · schwere Hörminderung |
| Linkes Ohr (Vierfrequenztöne) | 87,5 dB · hochgradige Hörminderung |
| Dreifrequenz-Mittelwert (500, 1k, 2k) rechtes Ohr / linkes Ohr | 75,0 / 85,0 dB |


### 5

Grad nach dem besseren Ohr (WHO 2021): mäßige Hörminderung

| Ergebnisdetails | |
| --- | --- |
| Rechtes Ohr (Vierfrequenztöne) | 35,0 dB · mäßige Hörminderung |
| Linkes Ohr (Vierfrequenztöne) | 40,0 dB · mäßige Hörminderung |
| Dreifrequenz-Mittelwert (500, 1k, 2k) rechtes Ohr / linkes Ohr | 35,0 / 40,0 dB |

