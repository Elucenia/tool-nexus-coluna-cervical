<!-- ELUCENIA technical documentation · nexus-coluna-cervical · it · no clinical/professional/rights approval -->

# Criteri NEXUS (rachide cervicale)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/nexus-coluna-cervical)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Dolorabilità sulla linea mediana posteriore del rachide cervicale

`dor`

### Deficit neurologico focale

`deficit`

### Alterazione del livello di coscienza

`alerta`

### Evidenza di intossicazione

`intox`

### Lesione dolorosa distraente (ad es., frattura di osso lungo, ustione estesa)

`distrativa`

## Edizione del metodo

NEXUS/Hoffman 2000: 5 criteri a basso rischio; regola cervicale originale

## Formula documentata

L’imaging può essere omesso quando tutti i criteri sono soddisfatti: niente dolorabilità mediana posteriore, deficit focale, intossicazione o lesione dolorosa distraente; coscienza normale. Qualsiasi reperto positivo indica imaging.

## Limiti e popolazione

La regola NEXUS 2000 è stata studiata in pazienti sottoposti a radiografia cervicale dopo trauma chiuso. La classificazione di bassa probabilità richiede tutti e cinque i criteri contemporaneamente; lo studio ha riportato lesioni non identificate dalla regola, quindi un risultato negativo non garantisce l’assenza di lesioni. Età, esclusioni e applicazione nei sottogruppi devono essere verificate nel protocollo completo.

## Riferimenti

- [Hoffman JR et al. Validity of a set of clinical criteria to rule out injury to the cervical spine in patients with blunt trauma. N Engl J Med, 2000.](https://doi.org/10.1056/NEJM200007133430203)

- [Stiell IG et al. The Canadian C-Spine Rule versus the NEXUS low-risk criteria in patients with trauma. N Engl J Med, 2003.](https://doi.org/10.1056/NEJMoa031375)

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
