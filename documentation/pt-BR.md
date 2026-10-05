<!-- ELUCENIA technical documentation · nexus-coluna-cervical · pt-BR · no clinical/professional/rights approval -->

# Critérios NEXUS (coluna cervical)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/nexus-coluna-cervical)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Dor à palpação na linha média posterior da coluna cervical

`dor`

### Déficit neurológico focal

`deficit`

### Alteração do nível de consciência

`alerta`

### Evidência de intoxicação

`intox`

### Lesão dolorosa que distrai (ex.: fratura de osso longo, queimadura extensa)

`distrativa`

## Edição do método

NEXUS/Hoffman 2000:5 critérios debaixo risco; regra cervical original

## Fórmula documentada

A imagem é dispensável quando todos os critérios são satisfeitos: sem dor na linha média posterior, sem déficit neurológico focal, nível de consciência normal, sem intoxicação e sem lesão dolorosa que distraia. Qualquer um presente indica imagem.

## Limites e população

A regra NEXUS 2000 foi estudada em pacientes submetidos a radiografia cervical após trauma fechado. A classificação de baixa probabilidade exige os cinco critérios simultaneamente; o estudo relatou lesões não identificadas pela regra, portanto resultado negativo não é certeza de ausência de lesão. Idade, exclusões e aplicação em subgrupos precisam de conferência no protocolo integral.

## Referências

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

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
