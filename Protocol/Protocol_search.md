# Literature search and screening protocol

**Survey:** *Emerging Threats and Countermeasures in Neuromorphic Systems: A Survey*  
**Type of record:** Supplementary literature-search audit  
**Review coverage:** 1 January 2014 – 30 June 2026  
**Documented search dates:** 7–10 November 2026

## 1\. Review scope and approach

This survey addresses security and privacy threats, defenses, and security-enabling mechanisms in neuromorphic computing. Its scope includes spiking neural networks (SNNs), in-memory/compute-in-memory architectures (IMC/CiM), and emerging-memory technologies when their properties are directly relevant to a neuromorphic security mechanism.

The literature was **curated iteratively** during manuscript preparation, and coverage was updated to publications available through **30 June 2026**. The search record below documents the query families and the verification activity undertaken on **7–10 November 2026**. It is not presented as a retrospectively fixed or preregistered systematic-review protocol. Earlier foundational publications may be cited for background without entering the period-limited review corpus.

## 2\. Query families

The search vocabulary was organized from the three keyword groups in Table 2 of the manuscript (*Fundamental*, *Scope*, and *Context*) into three Boolean families. These are the **normalized expressions retained in the audit log**, rather than independently archived, exact query-language strings for every database interface.

Q-EN:  Hardware-oriented threats

```
("neuromorphic computing" OR neuromorphic OR "spiking neural network*" OR SNN
 OR "in-memory computing" OR "compute-in-memory" OR memristor* OR ReRAM
 OR RRAM OR FeFET OR spintronic* OR crossbar*)
AND
("side-channel" OR "side channel" OR "power analysis" OR
 "electromagnetic leakage" OR "timing attack" OR "thermal attack" OR
 "fault injection" OR "hardware Trojan" OR RowHammer OR
 "model extraction" OR "reverse engineering")
```

&nbsp;

Q-SW:  Software-oriented threats and privacy

```
("neuromorphic computing" OR neuromorphic OR "spiking neural network*"
 OR SNN OR "event-driven")
AND
(adversarial OR backdoor* OR poison* OR "membership inference" OR
 "model inversion" OR privacy OR watermark* OR "model extraction"
 OR robustness)
```

&nbsp;

Q-EN:  Security-enabling mechanisms

```
("neuromorphic computing" OR neuromorphic OR "in-memory computing"
 OR "compute-in-memory" OR memristor* OR ReRAM OR RRAM OR FeFET
 OR spintronic*)
AND
("physical unclonable function" OR PUF OR
 "true random number generator" OR TRNG OR encryption OR
 "logic locking" OR authentication OR "secure computing" OR
 "hardware security")
```

3\. Recorded query executions

The earlier execution log contains three query-family results for each of eight sources (24 records in total). Values are **search-result hits, not unique publications**. The full text of each normalized expression, source, date, and recorded count is preserved in the accompanying spreadsheet and CSV.

| Database/source | Search date | Q-HW | Q-SW | Q-EN | Logged total |
| :---- | :---- | ----: | ----: | ----: | ----: |
| IEEE Xplore | 2026-11-09 | 211 | 133 | 133 | 477 |
| ACM Digital Library | 2026-11-09 | 339 | 226 | 95 | 660 |
| Nature Portfolio | 2026-11-10 | 109 | 46 | 75 | 230 |
| Scopus (Elsevier) | 2026-11-10 | 182 | 168 | 129 | 479 |
| SpringerLink | 2026-11-10 | 127 | 217 | 315 | 659 |
| Wiley Online Library | 2026-11-10 | 107 | 68 | 186 | 361 |
| IACR ePrint | 2026-11-10 | 20 | 18 | 17 | 55 |
| arXiv | 2026-11-10 | 7 | 6 | 5 | 18 |
| **Logged total** |  | **1,083** | **915** | **941** | **2,939** |

## 4\. Eligibility and screening

The review used the following selection procedure:

1. **Identification and consolidation:** gather search results, merge available exports, and consolidate duplicate records using DOIs and normalized titles when available.  
2. **Title and abstract review:** assess whether the study addresses a security/privacy threat, countermeasure, or enabling mechanism with direct relevance to neuromorphic computing, SNNs, IMC/CiM, or a transferable emerging-memory attack surface.  
3. **Full-text eligibility:** examine the technical mechanism, target substrate or model, and reported validation evidence of potentially relevant records.  
4. **Exclusion:** remove duplicates or superseded versions, non-research items, generic ANN/memory-security studies without substantive neuromorphic relevance, and preprints when an archival publication supersedes them.  
5. **Thematic classification:** group eligible studies under hardware-oriented threats, software-oriented threats, and security-enabling mechanisms. When a study spans multiple subjects, it may appear in multiple Figure 5 subsections.

The manuscript reports a final corpus of **137 eligible studies**: **49 hardware**, **45 software**, and **43 security enablers**. The accompanying audit is **not** a row-by-row register of those 137 final works; it records the search and screening method and summary counts instead.

### Selection for detailed discussion

Sections 4–6 and Tables 3–5 discuss a representative subset selected for distinct attack/defense mechanisms, close relevance to neuromorphic systems, cross-layer interactions, diversity of validation settings, and coverage of less represented security topics. Figure 5 is a thematic map, so its unique reference count is not intended to equal the full eligible corpus.

## 5\. How to interpret and reproduce this record

- Use `Query_Families` for the three complete normalized Boolean expressions. Also mixing with the keywords to extend the search.  
- Use `Execution_Log` for all 24 original source/family/date/count entries.  
- Use `Figure4_Source_Counts` and `Source_Reconciliation` to distinguish the current figure totals from the earlier query-family log.  
- Use `Screening_Rules`, `Verification_Checklist`, and `Data_Dictionary` for decisions, definitions, and known limitations.

&nbsp;