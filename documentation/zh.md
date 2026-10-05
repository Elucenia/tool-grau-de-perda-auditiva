<!-- ELUCENIA technical documentation · grau-de-perda-auditiva · zh · no clinical/professional/rights approval -->

# 纯音平均阈值与听力损失等级（WHO 2021）

[条件、来源与许可](https://elucenia.org/zh/tools/grau-de-perda-auditiva)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 右耳 · 500 Hz

`od500`

dB HL · 范围: -10–120

### 右耳 · 1000 Hz

`od1k`

dB HL · 范围: -10–120

### 右耳 · 2000 Hz

`od2k`

dB HL · 范围: -10–120

### 右耳 · 4000 Hz

`od4k`

dB HL · 范围: -10–120

### 左耳 · 500 Hz

`oe500`

dB HL · 范围: -10–120

### 左耳 · 1000 Hz

`oe1k`

dB HL · 范围: -10–120

### 左耳 · 2000 Hz

`oe2k`

dB HL · 范围: -10–120

### 左耳 · 4000 Hz

`oe4k`

dB HL · 范围: -10–120

## 方法版本

WHO 2021 World Report on Hearing：PTA 4频率500/1000/2000/4000，较好耳；3频PTA单列

## 已记录的公式

四频平均（WHO）=500、1000、2000和4000 Hz的气导听阈平均。三频平均=500、1000和2000 Hz的平均（用于Lloyd和Kaplan等传统分类）。

WHO分级取较好耳的四频平均。

## 限制与适用人群

此处的WHO 2021分类采用较好耳500、1000、2000和4000 Hz的平均值及成人等级；单独显示的三频平均值不能与该方法混淆。阈值须来自适当听力测定，使用dB HL，也称dB NA。数字等级不能单独描述沟通能力、环境或康复需求；WHO本身也指出此局限。单侧听力损失和儿童应用需专门解释，不能从成人总值直接推定。

## 参考文献

- [Chadha S, Kamenov K, Cieza A. The world report on hearing, 2021. Bull World Health Organ, 2021.](https://doi.org/10.2471/BLT.21.285643)

- [Organização Mundial da Saúde. World report on hearing, 2021.](https://www.who.int/publications/i/item/9789240020481)

- [WHO2021,WorldReportOnHearing,ISBN978-92-4-002048-1,primary-content mirror](https://soundhearing2030.org/pdf/World%20report%20on%20hearing.pdf)

- [WHO2021 official archive](https://iris.who.int/bitstream/handle/10665/339913/9789240020481-eng.pdf)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
