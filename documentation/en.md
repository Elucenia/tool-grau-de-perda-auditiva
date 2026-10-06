<!-- ELUCENIA technical documentation · grau-de-perda-auditiva · en · no clinical/professional/rights approval -->

# Pure-tone average and hearing loss grade (WHO 2021)

[conditions, sources and permissions](https://elucenia.org/en/tools/grau-de-perda-auditiva)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Right ear · 500 Hz

`od500`

dB HL · range: -10–120

### Right ear · 1,000 Hz

`od1k`

dB HL · range: -10–120

### Right ear · 2,000 Hz

`od2k`

dB HL · range: -10–120

### Right ear · 4,000 Hz

`od4k`

dB HL · range: -10–120

### Left ear · 500 Hz

`oe500`

dB HL · range: -10–120

### Left ear · 1,000 Hz

`oe1k`

dB HL · range: -10–120

### Left ear · 2,000 Hz

`oe2k`

dB HL · range: -10–120

### Left ear · 4,000 Hz

`oe4k`

dB HL · range: -10–120

## Method edition

WHO 2021 World Report on Hearing: PTA 4 frequencies 500/1000/2000/4000, better ear; PTA 3 separate

## Documented formula

Four-frequency average (WHO) = mean air-conduction thresholds at 500, 1,000, 2,000 and 4,000 Hz. Three-frequency average = mean at 500, 1,000 and 2,000 Hz (used in traditional classifications, such as Lloyd and Kaplan).

The WHO grade uses the four-frequency average of the better ear.

## Limits and population

The WHO 2021 classification here uses the average of 500, 1000, 2000 and 4000 Hz in the better ear and its adult grades; the three-frequency average displayed separately must not be confused with this method. Thresholds must come from appropriate audiometry and use dB HL, also called dB NA. The numerical grade alone does not describe communication ability, context or rehabilitation needs; WHO itself highlights this limitation. Unilateral hearing loss and pediatric application require specific interpretation and must not be assumed from the adult total.

## References

- [Chadha S, Kamenov K, Cieza A. The world report on hearing, 2021. Bull World Health Organ, 2021.](https://doi.org/10.2471/BLT.21.285643)

- [Organização Mundial da Saúde. World report on hearing, 2021.](https://www.who.int/publications/i/item/9789240020481)

- [WHO2021,WorldReportOnHearing,ISBN978-92-4-002048-1,primary-content mirror](https://soundhearing2030.org/pdf/World%20report%20on%20hearing.pdf)

- [WHO2021 official archive](https://iris.who.int/bitstream/handle/10665/339913/9789240020481-eng.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Degree by the better ear (WHO 2021): mild hearing loss

| Result details | |
| --- | --- |
| Right ear (four-frequency) | 27.5 dB · mild hearing loss |
| Left ear (four-frequency) | 37.5 dB · moderate hearing loss |
| Trifrequency average (500, 1k, 2k) RE / LE | 25.0 / 35.0 dB |


### 2

Degree by the better ear (WHO 2021): normal hearing

| Result details | |
| --- | --- |
| Right ear (four-frequency) | 10.0 dB · normal hearing |
| Left ear (four-frequency) | 10.0 dB · normal hearing |
| Trifrequency average (500, 1k, 2k) RE / LE | 10.0 / 10.0 dB |


### 3

Unilateral hearing loss (better ear < 20 dB and worse ≥ 35 dB)

| Result details | |
| --- | --- |
| Right ear (four-frequency) | 13.8 dB · normal hearing |
| Left ear (four-frequency) | 48.8 dB · moderate hearing loss |
| Trifrequency average (500, 1k, 2k) RE / LE | 11.7 / 45.0 dB |


### 4

Degree by the better ear (WHO 2021): severe hearing loss

| Result details | |
| --- | --- |
| Right ear (four-frequency) | 77.5 dB · severe hearing loss |
| Left ear (four-frequency) | 87.5 dB · profound hearing loss |
| Trifrequency average (500, 1k, 2k) RE / LE | 75.0 / 85.0 dB |


### 5

Degree by the better ear (WHO 2021): moderate hearing loss

| Result details | |
| --- | --- |
| Right ear (four-frequency) | 35.0 dB · moderate hearing loss |
| Left ear (four-frequency) | 40.0 dB · moderate hearing loss |
| Trifrequency average (500, 1k, 2k) RE / LE | 35.0 / 40.0 dB |

