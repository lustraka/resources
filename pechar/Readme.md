# CoEDiT: Budget-to-Network Episode

> 'CoEDiT' = **Co**mmitment-driven **E**nterprise **Di**gital **T**win
>
> 'pechar' = **Pe**rformance and **Cha**rging research **R**esources

**A demonstrative instance of CoEDiT translating financial traces into ontologically grounded commitment structures.** For details refer to [**CoEDiT_PoEM.pdf**](CoEDiT_PoEM.pdf).

## Overview
This repository contains data and modeling artifacts for CoEDiT—a commitment-driven enterprise digital twin. It reframes budget spreadsheets as commitment networks through a reflexive modeling loop grounded in ontology and semantics.

## FAIR Artifacts

| File | Description | Format | Standards |
|-|-|-|-|
| [`Input_bYYe.csv`](Input_bYYe.csv) | Fictionalized budget entries | CSV | EU IR 2019/317 |
| [`Input_bYYe_Vocabulary.ttl`](Input_bYYe_Vocabulary.ttl) | Controlled vocabulary for entity recognition | RDF/Turtle | SKOS, schema, fUFO |
| [`Output_bYYe.ttl`](Output_bYYe.ttl) | An RDF knowledge graph representing inferred institutional commitments | RDF/Turtle | SKOS, schema, fUFO |
| [`PoEM_bYYe_deliversTo.png`](PoEM_bYYe_deliversTo.png) | Inferred coordination network | PNG | n/a |
| [`CoEDiT_Budget_Demo.ipynb`](CoEDiT_Budget_Demo.ipynb)<br>(see [html here](CoEDiT_Budget_Demo.html)) | Python heuristics & visualization | Jupyter Notebook | pandas, rdflib |

## How to Reuse

These artifacts can be reused for modeling exercises, institutional diagnostics, or FAIR-aligned semantic transformation of enterprise data:
- Query `Output_bYYe.ttl` via SPARQL or validate using SHACL.
- Adapt `CoEDiT_Budget_Demo.ipynb` to derive and visualize coordination patterns from custom data.
- Reuse custom prefixes (e.g., `pecha:`, `ses:`) to semantically reference legal instruments via the [European Legislation Identifier (ELI)](https://eur-lex.europa.eu/eli-register/about.html), enabling machine-actionable alignment between institutional data and regulatory frameworks.

## Related Standards

- [EU IR 2019/317](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019R0317): Performance and charging regulation
- [SKOS](https://www.w3.org/TR/skos-reference/), [schema.org](https://schema.org/), [gUFO](https://purl.org/nemo/gufo)

## Reference

```bibtex
@misc{straka2025pechar,
  author = {Straka, Lubomír},
  title = {Toward Commitment-Driven Enterprise Digital Twins: Budget-to-Network Episode},
  year = {2025},
  url = {https://lustraka.github.io/resources/pechar/}
}
```

----

All resources are available under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Updated 2025-07-01.
