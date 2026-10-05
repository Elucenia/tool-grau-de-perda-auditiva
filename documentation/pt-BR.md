<!-- ELUCENIA technical documentation · grau-de-perda-auditiva · pt-BR · no clinical/professional/rights approval -->

# Média tonal e grau de perda auditiva (OMS 2021)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/grau-de-perda-auditiva)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### OD · 500 Hz

`od500`

dB NA · intervalo: -10–120

### OD · 1.000 Hz

`od1k`

dB NA · intervalo: -10–120

### OD · 2.000 Hz

`od2k`

dB NA · intervalo: -10–120

### OD · 4.000 Hz

`od4k`

dB NA · intervalo: -10–120

### OE · 500 Hz

`oe500`

dB NA · intervalo: -10–120

### OE · 1.000 Hz

`oe1k`

dB NA · intervalo: -10–120

### OE · 2.000 Hz

`oe2k`

dB NA · intervalo: -10–120

### OE · 4.000 Hz

`oe4k`

dB NA · intervalo: -10–120

## Edição do método

WHO 2021 World Reporton Hearing:PTA 4 frequências 500/1000/2000/4000 melhororelha; PTA 3 separada

## Fórmula documentada

Média quadritonal (OMS) = média dos limiares por via aérea em 500, 1.000, 2.000 e 4.000 Hz. Média tritonal = média de 500, 1.000 e 2.000 Hz (usada em classificações tradicionais, como a de Lloyd e Kaplan).

O grau da OMS é definido pela média quadritonal da melhor orelha.

## Limites e população

A classificação OMS 2021 aqui usa a média de 500, 1000, 2000 e 4000 Hz no melhor ouvido e seus graus para adultos; a média de três frequências exibida separadamente não deve ser confundida com esse método. Os limiares devem vir de audiometria adequada e usar dB HL, também chamado dB NA. O grau numérico não descreve sozinho capacidade de comunicação, contexto ou necessidade de reabilitação; a própria OMS ressalta essa limitação. Perda unilateral e aplicação pediátrica exigem interpretação específica e não devem ser presumidas a partir do total adulto.

## Referências

- [Chadha S, Kamenov K, Cieza A. The world report on hearing, 2021. Bull World Health Organ, 2021.](https://doi.org/10.2471/BLT.21.285643)

- [Organização Mundial da Saúde. World report on hearing, 2021.](https://www.who.int/publications/i/item/9789240020481)

- [WHO2021,WorldReportOnHearing,ISBN978-92-4-002048-1,primary-content mirror](https://soundhearing2030.org/pdf/World%20report%20on%20hearing.pdf)

- [WHO2021 official archive](https://iris.who.int/bitstream/handle/10665/339913/9789240020481-eng.pdf)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
