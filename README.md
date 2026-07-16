# LLMWiki-NGO-Humaninloop


An implementation of Andrej Karpathy's vision of an **LLM Wiki**: a multi-stage compilation pipeline that treats raw source materials as uncompiled code. This system pre-computes context graphs, structures strict data exclusions, and formats high-density relational text graphs to maximize the performance of downstream LLM attention weights.

## 🌟 Social Sector Use Case & Scope
This specific repository is optimized as a core knowledge engine for a **Gliffic WhatsApp Chatbot**. It provides authoritative public health awareness and  guidance to pregnant mothers and caregivers across  communities in Mumbai, India. 


## ⚡ The Wiki creates index that is optimized for high accuracy Router Reasoning  during Gliffic QA 

To protect maternal health outcomes, the Stage-1 Router skips unstable vector proximity calculations entirely, relying on direct token matches with high-density Markdown Manifest Tables:

1.  **STAGE 0 (Language Translation):** Translates incoming localized user queries directly into English.
2.  **STAGE 1 (Protocol Selection):** Matches extracted query profile signatures directly against `SECTION_1_ROUTING_DIRECTIVES` to isolate chronological lanes or enforce an acute redirection mandate.
3.  **STAGE 2 (Inclusion Shortlisting):** Uses `SECTION_2_INCLUSION_KEYWORDS` to shortlist candidate filenames matching core clinical intentions.
4.  **STAGE 3 (Filtering / Hard Negatives):** References `SECTION_3_EXCLUSIONS`. If an invalid milestone parameter matches an exclusion bound, the path is instantly canceled to eliminate false-positive medical contamination.


## 🏗️ Multi-Pass Compilation Pipeline


[ Raw Source Files ]
         │
         ▼
┌────────────────────────────────────────────────────────┐
│ PHASE 1: Structural Synthesis                          │
│ ├─ Pass 1A: Semantic Discovery                         │
│ ├─ Pass 1B: Topology Design                            │
│ ├─ Pass 1C: Query Alignment                            │
│ ├─ Pass 1D: Boundary Hardening                         │
│ └─ Pass 1E: Matrix Schema Locking                      │
└────────────────────────────────────────────────────────┘
         │
         ▼ [MasterTaxonomyBlueprint JSON Contract]
┌────────────────────────────────────────────────────────┐
│ PHASE 2: Guardrailed Extraction & Module Building      │
│ ├─ Pass 2A: Audit Cascade                              │
│ ├─ Pass 2B: Linter Sanity Check                        │
│ └─ Pass 2: Verbatim Materialization                    │
└────────────────────────────────────────────────────────┘
         │
         ▼ [Materialized wiki/ folder markdown nodes]
┌────────────────────────────────────────────────────────┐
│ PHASE 3: Hierarchical Semantic Indexing                │
│ ├─ Pass 3A: Tier-1 Cataloging (index.md)               │
│ └─ Pass 3B: Detailed Matrix Compilation (manifests)    │
└────────────────────────────────────────────────────────┘
         │
         ▼ [index_detailed.md Relational Tables]
┌────────────────────────────────────────────────────────┐
│ PHASE 4: Integrity Graph Sealing                       │
│ └─ Pass 4: Pure-Python Graph Auditor Gate              │
└────────────────────────────────────────────────────────┘
         │
         ▼
[ Verified Runtime-Exportable Knowledge Engine Vault ]


 ## 🔍 Detailed Phase Breakdown

### Phase 1: Structural Synthesis
Establishes system parameters, data configurations, and folder rules.
*   **Pass 1A (Semantic Discovery):** Scrapes text globally to gather raw checklists, configurations, and isolated health metrics into an unrefined inventory list.
*   **Pass 1B (Topology Design):** Clusters the inventory into 10 to 25 distinct, mutually exclusive directory themes to completely avoid generic document structures.
*   **Pass 1C (Query Alignment):** Warps and reshapes directory boundaries around real-world user intent distribution logs (such as Gliffic questions) to match critical information demand.
*   **Pass 1D (Boundary Hardening):** Mitigates node overlap errors by establishing strict narrative laws defining exactly what data is forbidden inside each file.
*   **Pass 1E (Matrix Schema Locking):** Locks the directory roadmap and files into a verified Pydantic blueprint JSON contract.

### Phase 2: Guardrailed Extraction & Module Building
Validates the structural maps and builds high-integrity individual markdown files.
*   **Pass 2A (Audit Cascade):** Minimizes source documentation omissions by iteratively reviewing the blueprint layout against the original raw materials.
*   **Pass 2B (Linter Sanity Check):** Runs a local, zero-API Python validator to check for filename typos or missing definitions before launching expensive generation loops.
*   **Pass 2 (Verbatim Materialization):** Feeds isolated source text into the model to construct structured, tabular, and code-bounded markdown documents.

### Phase 3: Hierarchical Semantic Indexing
Assembles the application-level data routing infrastructure.
*   **Pass 3A (Tier-1 Cataloging):** Compiles the markdown nodes into a lightweight master roadmap index (`index.md`).
*   **Pass 3B (Detailed Matrix Compilation):** Generates `index_detailed.md` featuring explicit Markdown Manifest Tables capturing target user profiles, valid milestones, symptom variables, and strict invalidation boundaries.

### Phase 4: Integrity Graph Sealing
Secures graph consistency and path connections prior to production export.
*   **Pass 4 (Link Validation Linter):** Evaluates markdown syntax using parsing loops to check if every hyperlink points to a real file on disk, blocks generation on orphaned nodes, and packages the verified engine into a ZIP file for production.

