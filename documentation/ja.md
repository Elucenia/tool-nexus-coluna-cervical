<!-- ELUCENIA technical documentation · nexus-coluna-cervical · ja · no clinical/professional/rights approval -->

# NEXUS基準（頸椎）

[条件・出典・許諾](https://elucenia.org/ja/tools/nexus-coluna-cervical)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 頸椎後方正中部の圧痛

`dor`

### 局所神経脱落症状

`deficit`

### 意識レベルの変化

`alerta`

### 中毒の所見

`intox`

### 注意をそらす疼痛性損傷（例：長管骨骨折、広範囲熱傷）

`distrativa`

## 方法の版

NEXUS/Hoffman 2000：5低リスク基準、原著頸椎ルール

## 記載された計算式

画像検査を省略できる条件は、 すべて の基準を満たすこと：後方正中圧痛なし、局所神経脱落なし、意識正常、中毒なし、注意をそらす疼痛性外傷なし。いずれかの異常があれば画像検査です。

## 限界・対象集団

NEXUS 2000のルールは、鈍的外傷後に頸椎のX線撮影を受けた患者で研究されました。低い確率に分類するには、五つの基準をすべて同時に満たす必要があります。研究ではルールで検出されなかった損傷も報告されており、陰性結果は損傷がないことの確実な証明ではありません。年齢、除外条件、サブグループへの適用は、プロトコル全文で確認する必要があります。

## 参考文献

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

低リスク：頸椎画像検査は不要

5つの低リスク基準はすべて満たされました。


### 2

頸椎画像検査が適応

画像評価まで脊椎の固定を維持する。


### 3

頸椎画像検査が適応

画像評価まで脊椎の固定を維持する。

