<!-- ELUCENIA technical documentation · grau-de-perda-auditiva · es · no clinical/professional/rights approval -->

# Promedio tonal y grado de pérdida auditiva (OMS 2021)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/grau-de-perda-auditiva)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Oído derecho · 500 Hz

`od500`

dB HL · intervalo: -10–120

### Oído derecho · 1.000 Hz

`od1k`

dB HL · intervalo: -10–120

### Oído derecho · 2.000 Hz

`od2k`

dB HL · intervalo: -10–120

### Oído derecho · 4.000 Hz

`od4k`

dB HL · intervalo: -10–120

### Oído izquierdo · 500 Hz

`oe500`

dB HL · intervalo: -10–120

### Oído izquierdo · 1.000 Hz

`oe1k`

dB HL · intervalo: -10–120

### Oído izquierdo · 2.000 Hz

`oe2k`

dB HL · intervalo: -10–120

### Oído izquierdo · 4.000 Hz

`oe4k`

dB HL · intervalo: -10–120

## Edición del método

WHO 2021 World Report on Hearing: PTA 4 frecuencias 500/1000/2000/4000, mejor oído; PTA 3 separada

## Fórmula documentada

Media cuadritonal (OMS) = media de umbrales por vía aérea a 500, 1.000, 2.000 y 4.000 Hz. Media tritonal = media de 500, 1.000 y 2.000 Hz (usada en clasificaciones tradicionales, como Lloyd y Kaplan).

El grado OMS se define por la media cuadritonal del mejor oído.

## Límites y población

La clasificación OMS de 2021 aquí utiliza la media de 500, 1000, 2000 y 4000 Hz en el mejor oído y sus grados para adultos; la media de tres frecuencias mostrada por separado no debe confundirse con este método. Los umbrales deben proceder de una audiometría adecuada y expresarse en dB HL, también llamados dB NA. El grado numérico no describe por sí solo la capacidad de comunicación, el contexto o la necesidad de rehabilitación; la propia OMS señala esta limitación. La pérdida unilateral y la aplicación pediátrica requieren una interpretación específica y no deben presumirse a partir del total adulto.

## Referencias

- [Chadha S, Kamenov K, Cieza A. The world report on hearing, 2021. Bull World Health Organ, 2021.](https://doi.org/10.2471/BLT.21.285643)

- [Organização Mundial da Saúde. World report on hearing, 2021.](https://www.who.int/publications/i/item/9789240020481)

- [WHO2021,WorldReportOnHearing,ISBN978-92-4-002048-1,primary-content mirror](https://soundhearing2030.org/pdf/World%20report%20on%20hearing.pdf)

- [WHO2021 official archive](https://iris.who.int/bitstream/handle/10665/339913/9789240020481-eng.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
