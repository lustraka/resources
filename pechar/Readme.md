# Reflexive Infrastructures for Commitment-Based Enterprise Digital Twins

> 'pechar' = **Pe**rformance and **Cha**rging research **R**esources

## 1. Epistemic Intent and Thematic Scope

This companion repository supports the proof-of-concept study titled  
**"Toward Commitment-Driven Enterprise Digital Twins: A Socio-Technical Approach to Reflexive Modeling in the Age of Digitalization"**  
by Lubomír Straka ([ORCID:0000-0003-0133-6780](https://orcid.org/0000-0003-0133-6780)).

It curates a set of modeling artifacts that exemplify how transactional data—originally designed for regulatory compliance—can be repurposed into semantic structures reflecting institutional commitments. The approach is grounded in dialectical modeling, combining conceptual abstraction with empirical traceability.

## 2. Methodological Maturity and Research Status

This repository presents [**CoEDiT_v0.7**](CoEDiT_v0.7.pdf), a pre-publication prototype released for departmental peer review.
It embodies the current culmination of our reflexive modeling loop, advancing through:

- **Conceptual Modeling** — ontological framing of commitments  
- **Data Mining** — transformation of regulatory traces into graph-based representations  
- **Reflexive Sensemaking** — interpretive inference of institutional relations  
- **Conceptual Refinement** — ontological consolidation using UFO and gUFO

The versioning roadmap is outlined below:

| Version     | Purpose                         | Status              |
|-------------|----------------------------------|---------------------|
| `v0.7`      | Departmental critical review     | _Current_           |
| `v0.8`      | Journal submission (peer review) | _To Be Decided_    |
| `v0.9`      | Accepted version for publication | _To Be Decided_     |
| `v1.0`      | Final archival version post-publication | _To Be Decided_     |

All materials align with the FAIR principles (Findable, Accessible, Interoperable, Reusable) and are ethically bounded as practice-informed, not generalizable.

## 3. Semantic Artifacts and Modeling Grammar

The following core artifacts are included:

Artifact | Description
-|-
[`CedtPocBYYe.csv`](CedtPocBYYe.csv)| *Constructed fiscal data aligned with EU IR317, serving as the empirical anchor.*
[`CedtPocVocab.ttl`](CedtPocVocab.ttl)| *Provisional RDF schema capturing early commitments and concepts.*
[`CedtPocBYYe.ttl`](CedtPocBYYe.ttl)| *Commitment-based enterprise knowledge graph — the principal semantic artifact emerging from this proof-of-concept.*
[`CedtPoc.ipynb`](CedtPoc.ipynb)| *Python notebook for semantic lifting, rule-based enrichment, and RDF graph construction.*

## 4. Provenance, Accessibility, and Reusability

- All resources are available under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
- Ontologies conform to [W3C RDF 1.1 Turtle](https://www.w3.org/TR/turtle/).
- Graph reasoning supports SPARQL 1.1 and OWL 2 DL.
- Please cite as:

```
@misc{straka2025coedit,
  author = {Straka, Lubomír},
  title = {Reflexive Infrastructures for Commitment-Based Enterprise Digital Twins},
  year = {2025},
  url = {https://lustraka.github.io/resources/pechar/}
}

----

Updated 2025-04-24