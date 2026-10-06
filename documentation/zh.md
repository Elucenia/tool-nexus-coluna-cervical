<!-- ELUCENIA technical documentation · nexus-coluna-cervical · zh · no clinical/professional/rights approval -->

# NEXUS 标准（颈椎）

[条件、来源与许可](https://elucenia.org/zh/tools/nexus-coluna-cervical)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 颈椎后正中线压痛

`dor`

### 局灶性神经功能缺损

`deficit`

### 意识水平改变

`alerta`

### 中毒或醉态证据

`intox`

### 分散注意力的疼痛性损伤（如长骨骨折、大面积烧伤）

`distrativa`

## 方法版本

NEXUS/Hoffman 2000：5项低风险标准；原始颈椎规则

## 已记录的公式

可免除影像检查，当 全部 标准满足：无后正中线压痛、无局灶神经缺损、意识正常、无中毒、无分散注意的疼痛性损伤。任一异常提示影像检查。

## 限制与适用人群

NEXUS 2000规则在钝性创伤后接受颈椎X线检查的患者中开展研究。低概率分类要求五项标准同时满足；研究报告了未被该规则识别的损伤，因此阴性结果并不能确定不存在损伤。年龄、排除条件和亚组应用须在完整方案中核对。

## 参考文献

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

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

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

低风险：无需进行颈椎影像学检查

五项低风险标准均已满足。


### 2

需进行颈椎影像学检查

在影像学评估前保持脊柱制动。


### 3

需进行颈椎影像学检查

在影像学评估前保持脊柱制动。

