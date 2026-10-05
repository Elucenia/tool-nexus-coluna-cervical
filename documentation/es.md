<!-- ELUCENIA technical documentation · nexus-coluna-cervical · es · no clinical/professional/rights approval -->

# Criterios NEXUS (columna cervical)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/nexus-coluna-cervical)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Dolor a la palpación en la línea media posterior de la columna cervical

`dor`

### Déficit neurológico focal

`deficit`

### Alteración del nivel de conciencia

`alerta`

### Evidencia de intoxicación

`intox`

### Lesión dolorosa que distrae (p. ej., fractura de hueso largo, quemadura extensa)

`distrativa`

## Edición del método

NEXUS/Hoffman 2000: 5 criterios de bajo riesgo; regla cervical original

## Fórmula documentada

La imagen puede omitirse cuando todos los criterios se cumplen: sin dolor posterior en línea media, déficit focal, intoxicación ni lesión distractora; conciencia normal. Cualquier hallazgo positivo indica imagen.

## Límites y población

La regla NEXUS 2000 se estudió en pacientes sometidos a radiografía cervical tras traumatismo cerrado. La clasificación de baja probabilidad exige los cinco criterios simultáneamente; el estudio informó lesiones no identificadas por la regla, por lo que un resultado negativo no garantiza la ausencia de lesión. La edad, las exclusiones y su aplicación en subgrupos deben comprobarse en el protocolo completo.

## Referencias

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

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
