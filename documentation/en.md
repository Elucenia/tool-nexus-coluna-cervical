<!-- ELUCENIA technical documentation · nexus-coluna-cervical · en · no clinical/professional/rights approval -->

# NEXUS criteria (cervical spine)

[conditions, sources and permissions](https://elucenia.org/en/tools/nexus-coluna-cervical)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Posterior midline cervical spine tenderness

`dor`

### Focal neurological deficit

`deficit`

### Altered level of consciousness

`alerta`

### Evidence of intoxication

`intox`

### Painful distracting injury (e.g., long-bone fracture, extensive burn)

`distrativa`

## Method edition

NEXUS/Hoffman 2000: 5 low-risk criteria; original cervical rule

## Documented formula

Imaging can be omitted when all criteria are met: no posterior midline tenderness, no focal neurological deficit, normal alertness, no intoxication and no painful distracting injury. Any positive finding indicates imaging.

## Limits and population

The NEXUS 2000 rule was studied in patients undergoing cervical radiography after blunt trauma. Low-probability classification requires all five criteria simultaneously; the study reported injuries missed by the rule, so a negative result is not certainty of no injury. Age, exclusions and subgroup application must be checked in the full protocol.

## References

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

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

Low risk: cervical spine imaging not required

All five low-risk criteria were met.


### 2

Cervical spine imaging indicated

Maintain spinal immobilization until imaging evaluation.


### 3

Cervical spine imaging indicated

Maintain spinal immobilization until imaging evaluation.

