# LLM Wiki for Social Sector : Designing the engine for establishing Trust & Accuracy in Gliffic QA bot among NGO Community  


An implementation of Andrej Karpathy's vision of an **LLM Wiki**: a multi-stage compilation pipeline that treats raw source materials as uncompiled code. This system pre-computes context graphs, structures strict data exclusions, and formats high-density relational text graphs to maximize the performance of downstream LLM attention weights.

## 🌟 Social Sector Use Case & Scope
This specific repository is LLM Wiki  (builds on Karpathy vision of LLM Wiki,  but we design it for the Social Sector needs).  
1. Powerful Human in the loop optional controls: Enables NGO to take control on the structure of the Wiki and shape its creation (NGO program owners can guide how this AI should shape up the output contents of AI generated Wiki.)
2. The index is optimized for effective Wiki Router for the downstream Question Answering task around **Gliffic WhatsApp Chatbot**  .
3. Trust factor: For example, SNEHA's wiki index ensures questions from high-risk mothers are handling by with utmost care - allows routing to human vetted - hi-risk pregnancies section of LLM Wiki
4. Human in the Loop approval : The 3 pass mechamism first creates a mental model , then takes approval for NGO program owners before creating the Wiki. If the NGO program leaders wants to shape the Wiki in a different way, they can guide and shape the mental model until they get a satisfactory blueprint

## 🌟**What is Special: Building Trust with the NGO Communtiy ? How this design protects NGO community **

Illustrative example of How this LLM Wiki supports NGOs to build trust with end-users ( Scenario: How Gliffic QA bot responds to high risk pregnancy case)

[Illustration in LLM Wiki Design](https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/WikiContents/Human-in-loop/Readme.md) 

## 🚀 How it Works: This LLM Wiki is a textbook implemention of Karpathy's vision.. 

This framework treats raw documents as uncompiled source code, processing them into a structured digital library optimized directly for automated answering:

```text
[Raw Source Files] ──> Step 1: Blueprint Planning ──> Step 2: Fact Extraction ──> Step 3: Indexing ──> Step 4: LLM Wiki contents !
```

1. **Step 1: Blueprint Planning**  
   The system maps out a comprehensive mental model of the Wiki. It looks at the unique use case, configurations for topic count limits, and outputs a concrete architectural blueprint plan.
2. **Step 2: Fact Extraction**  
   The compilation engine sweeps through the source documentation to isolate key facts, metrics, and data parameters. It then materializes these details directly into clean markdown files based on structural configuration templates.
3. **Step 3: Creating the Search Index**  
   The pipeline generates structured table-of-contents files and high-density attribute manifest maps. This index allows the query router to instantly find the absolute best file to answer a user's question with total precision.

---

## 👥 Human-in-the-Loop : Allows NGO to control and shape the LLM Wiki structure 


* **Collaborative Blueprint Design:** The initial mental map and system boundaries are brainstormed and structured in active cooperation with NGO administrative managers to perfectly match community requirements.
* **Demand-Driven Content Matching:** Human interaction logs (such as localized chatbot question logs from platforms like Gliffic) are fed into the system. The system explicitly warps and customizes folder boundaries around the exact questions humans are asking.
* **Critical Clinical Content Review:** Specialized healthcare professionals (such as SNEHA team members) are actively assigned to manually audit and review high-risk medical pages—such as severe maternal anemia advice—ensuring absolute safety before the files are finalized.



## 💎 Core Benefits of the Multi-Pass Compilation Architecture based  LLM Wiki

| Dynamic Feature | Impact & Business Benefit for NGOs | Technical Idea | Deep Technical Summary |
| :--- | :--- | :--- | :--- |
| **1. Human readable Wiki Content  - No more a AI blackbox - Auto LLM Wiki creation** | **Reorganizes input** for users by organizing messy folders into neat, ready-to-read topic guides before going live. | Inversion of synthesis | Dissects overlapping source manuals offline into mutually exclusive topic containers optimized for transformer attention weights. |
| **2. ACCURACY - Designed for Accurate Gliffic QA bot experience** | **Guarantees near-perfect matching** of user questions to the right documents, stopping the chatbot from pulling random text chunks. | High-density manifest lookups | Replaces fuzzy vector distance calculations with structural token matching over native Markdown key-value attribute tables. |
| **3. TRUST - Protects NGO Communtiy** | **Blocks wrong medical advice instantly** by telling the chatbot exactly what topics are strictly forbidden in each section. | Hard negative context constraints | Encodes explicit invalidation boundaries into the index to reject mismatched file paths instantly, preventing cross-contamination. |
| **4. Can adapat to needs of NGO endusers question patterns** | **Shapes the library around real community needs** by tailoring folders directly to the exact questions users ask. | Demand-driven alignment | Restructures directory taxonomy scopes dynamically according to real-world user intent distribution logs. |
| **5. Quality** | **Prevents broken links ** by catching mistakes automatically before the project is deployed. |   automated linting | Runs a   validation script to audit filename linkages, catch orphaned nodes, and verify Pydantic blueprint conformity. |


## ⚡ Designed for High Accuracy Question Answering for NGOs QA bot: The Wiki creates index that is optimized for high accuracy Router Reasoning  during Gliffic QA 

To protect maternal health outcomes, the Stage-1 Router skips unstable vector proximity calculations entirely, relying on direct token matches with high-density Markdown Manifest Tables:

Refer to Automatically generated [Routing_Guidance](https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/WikiContents/index_stage_routing_protocol.md)

1.  **STAGE 0 (Language Translation):** Translates incoming localized user queries directly into English.
2.  **STAGE 1 (Protocol Selection):** Matches extracted query profile signatures directly against `SECTION_1_ROUTING_DIRECTIVES` to isolate chronological lanes or enforce an acute redirection mandate.
3.  **STAGE 2 (Inclusion Shortlisting):** Uses `SECTION_2_INCLUSION_KEYWORDS` to shortlist candidate filenames matching core clinical intentions.
4.  **STAGE 3 (Filtering / Hard Negatives):** References `SECTION_3_EXCLUSIONS`. If an invalid milestone parameter matches an exclusion bound, the path is instantly canceled to eliminate false-positive medical contamination.

## Source Code

[Github notebook](https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/Nand_Wiki_creation_v2s.ipynb)

[View in Colab](https://colab.research.google.com/github/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/Nand_Wiki_creation_v2s.ipynb)


## 🔍 How it works: The Design 

## 🏗️ Design of the LLM Wiki Creation System: A Multi-Pass Compilation Pipeline

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

## 🏗️ Design Diagram of the LLM Wiki Creation  

```text
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


```


## 🏗️ Sample Wiki Contents  
https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/tree/main/WikiContents/WikiContentVersions/WikiVer1/Contents

## 🏗️ Sample Wiki QA answers 
https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/tree/main/WikiContents/Outputs




