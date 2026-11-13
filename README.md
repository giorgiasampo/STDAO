# STDAO: A Socio-Technical Ontology of Decentralized Autonomous Organizations

**STDAO** is an OWL ontology for representing decentralized autonomous organizations (DAOs) as **socio-technical systems**. It connects blockchain-based infrastructure and software with governance arrangements, decision rights, participation, and organizational practices. STDAO provides a formal vocabulary for representing these distinctions and the relationships among them.

The ontology is inspired by the [Web3-DAO ontology](https://doi.org/10.1016/j.websem.2024.100830) by Valiente and Pavón (2024), but it is intended as a socio-technical representation of the phenomenon, explicitly representing interrelatedness between organizational, governance, and techical layers.

## Conceptual scope

STDAO distinguishes three interconnected layers:

| Layer | Focus | Illustrative concepts |
| --- | --- | --- |
| **Technical–Artefactual Layer** | Infrastructure and software through which DAO activities are implemented | Blockchains, blocks, smart contracts, tokens, token standards, wallets, transactions |
| **Governance–Intermediation Layer** | Rules and arrangements connecting technical capabilities to collective decision-making | Governance systems, proposals, voting schemes, delegation, decision rights, reputation, special-rights allocations |
| **Organizational–Manifestation Layer** | The organizational purposes, actors, and practices associated with a DAO | Organizations, members, teams, goals, participation, coordination |

Legal arrangements and security concerns are represented as cross-cutting aspects of a DAO rather than as a separate, self-contained organizational layer. **Layer memberships can overlap**: a concept may connect technical, governance, and organizational perspectives.

## Relationship to Web3-DAO

STDAO draws on Web3-DAO (Valiente & Pavón, 2024), which already formalizes DAO organizations, stakeholders, committees, agreements, proposals, voting, and technical artifacts. STDAO makes additional distinctions and connections explicit, especially between:

1. A DAO's technical instantiation and its organizational manifestation.
2. Token implementation, reputation, and governance authority.
3. Voting records, participation, incentives, and the distribution of influence.

## Ontology file and namespace

The primary ontology artifact is:

- [`SocioTechnicalOntology.rdf`](./SocioTechnicalOntology.rdf) — OWL ontology serialized in RDF/XML.

The ontology IRI and preferred namespace prefix are:

```turtle
# Ontology IRI: http://www.semanticweb.org/gisa/STDAO
@prefix St: <http://www.semanticweb.org/gisa/STDAO/> .
```

The version IRI, when declared, is recorded inside the RDF file. Local names are case-sensitive; examples in this README use the `St:` prefix for readability.

## Citation

If you use the ontology, please cite the **versioned repository release** you used and the accompanying STDAO publication once available. A release DOI and formal citation can be added here when assigned.

## Project team

Giorgia Sampò, Oliver Baumann, Marco Peressotti, and Markus Becker — University of Southern Denmark.
