<!-- ELUCENIA technical documentation · grau-de-perda-auditiva · it · no clinical/professional/rights approval -->

# Media tonale e grado di perdita uditiva (OMS 2021)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/grau-de-perda-auditiva)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Orecchio destro · 500 Hz

`od500`

dB HL · intervallo: -10–120

### Orecchio destro · 1.000 Hz

`od1k`

dB HL · intervallo: -10–120

### Orecchio destro · 2.000 Hz

`od2k`

dB HL · intervallo: -10–120

### Orecchio destro · 4.000 Hz

`od4k`

dB HL · intervallo: -10–120

### Orecchio sinistro · 500 Hz

`oe500`

dB HL · intervallo: -10–120

### Orecchio sinistro · 1.000 Hz

`oe1k`

dB HL · intervallo: -10–120

### Orecchio sinistro · 2.000 Hz

`oe2k`

dB HL · intervallo: -10–120

### Orecchio sinistro · 4.000 Hz

`oe4k`

dB HL · intervallo: -10–120

## Edizione del metodo

WHO 2021 World Report on Hearing: PTA 4 frequenze 500/1000/2000/4000, orecchio migliore; PTA 3 separata

## Formula documentata

Media a quattro frequenze (OMS) = media delle soglie per via aerea a 500, 1.000, 2.000 e 4.000 Hz. Media a tre frequenze = media a 500, 1.000 e 2.000 Hz (classificazioni tradizionali, come Lloyd e Kaplan).

Il grado OMS si definisce dalla media a quattro frequenze dell’orecchio migliore.

## Limiti e popolazione

La classificazione OMS del 2021 qui utilizza la media di 500, 1000, 2000 e 4000 Hz nell’orecchio migliore e i relativi gradi per adulti; la media di tre frequenze mostrata separatamente non deve essere confusa con questo metodo. Le soglie devono provenire da un’audiometria adeguata ed essere espresse in dB HL, detti anche dB NA. Il grado numerico non descrive da solo la capacità di comunicazione, il contesto o la necessità di riabilitazione; la stessa OMS sottolinea questo limite. La perdita unilaterale e l’applicazione pediatrica richiedono un’interpretazione specifica e non devono essere presunte dal totale per adulti.

## Riferimenti

- [Chadha S, Kamenov K, Cieza A. The world report on hearing, 2021. Bull World Health Organ, 2021.](https://doi.org/10.2471/BLT.21.285643)

- [Organização Mundial da Saúde. World report on hearing, 2021.](https://www.who.int/publications/i/item/9789240020481)

- [WHO2021,WorldReportOnHearing,ISBN978-92-4-002048-1,primary-content mirror](https://soundhearing2030.org/pdf/World%20report%20on%20hearing.pdf)

- [WHO2021 official archive](https://iris.who.int/bitstream/handle/10665/339913/9789240020481-eng.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Grado in base all’orecchio migliore (OMS 2021): perdita uditiva lieve

| Dettagli del risultato | |
| --- | --- |
| Orecchio destro (quattro frequenze) | 27,5 dB · perdita uditiva lieve |
| Orecchio sinistro (quattro frequenze) | 37,5 dB · perdita uditiva moderata |
| Media trifrequenziale (500, 1k, 2k) OD / OE | 25,0 / 35,0 dB |


### 2

Grado in base all’orecchio migliore (OMS 2021): udito normale

| Dettagli del risultato | |
| --- | --- |
| Orecchio destro (quattro frequenze) | 10,0 dB · udito normale |
| Orecchio sinistro (quattro frequenze) | 10,0 dB · udito normale |
| Media trifrequenziale (500, 1k, 2k) OD / OE | 10,0 / 10,0 dB |


### 3

Perdita uditiva unilaterale (orecchio migliore < 20 dB e peggiore ≥ 35 dB)

| Dettagli del risultato | |
| --- | --- |
| Orecchio destro (quattro frequenze) | 13,8 dB · udito normale |
| Orecchio sinistro (quattro frequenze) | 48,8 dB · perdita uditiva moderata |
| Media trifrequenziale (500, 1k, 2k) OD / OE | 11,7 / 45,0 dB |


### 4

Grado in base all’orecchio migliore (OMS 2021): perdita uditiva grave

| Dettagli del risultato | |
| --- | --- |
| Orecchio destro (quattro frequenze) | 77,5 dB · perdita uditiva grave |
| Orecchio sinistro (quattro frequenze) | 87,5 dB · perdita uditiva profonda |
| Media trifrequenziale (500, 1k, 2k) OD / OE | 75,0 / 85,0 dB |


### 5

Grado in base all’orecchio migliore (OMS 2021): perdita uditiva moderata

| Dettagli del risultato | |
| --- | --- |
| Orecchio destro (quattro frequenze) | 35,0 dB · perdita uditiva moderata |
| Orecchio sinistro (quattro frequenze) | 40,0 dB · perdita uditiva moderata |
| Media trifrequenziale (500, 1k, 2k) OD / OE | 35,0 / 40,0 dB |

