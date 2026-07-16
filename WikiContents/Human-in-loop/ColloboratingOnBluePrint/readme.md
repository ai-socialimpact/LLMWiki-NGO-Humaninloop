### 🎨 Colloborating with NGO Program Owner on the Blueprint Design for Wiki

Phase 1 processes your unstructured text library through a 5-pass  compilation sequence.

## 🛠️ NGO Program Owners can shape the Wiki with Human in the Loop, for ex, the no of topics

An NGO Administrator can control how precisely the chatbot route answers by tuning the **Thematic Topic Count Limits** inside the Phase 1 pipeline . 

By instructing the LLM Wiki compiler to enforce tighter or broader grouping rules during the initial planning passes, you explicitly change the data breakdown inside the final `master_taxonomy_blueprint.json` contract.


```text
[Raw Sources + Use Case Guidance]
               │
               ▼
┌────────────────────────────────────────────────────────┐
│ PHASE 1: Blueprint Compiler                            │
│ ├─ Pass 1A: Broad Semantic Discovery                   │
│ ├─ Pass 1B: Topology Matrix Selection (Sets Size!)     │
│ ├─ Pass 1C: Historical Demand Optimization             │
│ ├─ Pass 1D: Narrative Isolation Borders                │
│ └─ Pass 1E: Pydantic Contract Serialization            │
└────────────────────────────────────────────────────────┘
               │
               ▼
   [master_taxonomy_blueprint.json]
```

1. **Pass 1A (Semantic Discovery):** Scans files globally to harvest milligram parameters, raw health check frequencies, and clinical conditions into an unrefined catalog.
2. **Pass 1B (Topology Design):** Clusters the catalog items into a distinct number of topic files. **This is where the Admin configures the file density rules.**
3. **Pass 1C (Query Alignment):** Aligns and shapes these topics based on live community query logs (like Gliffic channels).
4. **Pass 1D (Boundary Hardening):** Sets clear narrative isolation boundaries and strict exclusion guidelines for every page.
5. **Pass 1E (Matrix Schema Locking):** Locks and encodes everything into a validated Pydantic dictionary contract.

---



### 🎛️ How Admin Configuration Changes the Blueprint

By modifying the parameters inside the **`INSTRUCTIONs`** framework, you directly impact how the LLM  Wiki splits and organizes overlapping topics like trimesters and clinical risk states:

#### 📉 Setting Broad Topics (Min: 5 / Max: 10)
* **Admin Directive:** *"Propose an initial balanced directory taxonomy of 5 to 10 distinct, master topics."*
* **Blueprint Result:** The pipeline compiles info into fewer, larger markdown guides. General nutrition and severe anemia collapse into a single file path.
* **Routing Effect:** Low-Resolution Routing. The system easily routes to general categories, but risks mixing routine advice with high-risk clinical indicators.

#### 📈 Setting High-Resolution Topics (Min: 10 / Max: 25)
* **Admin Directive:** *"Propose an initial balanced directory taxonomy of 10 to 25 distinct, master topics."*
* **Blueprint Result:** The engine separates overlapping concepts. Routine lifestyle trackers are split cleanly away from emergency danger signs.
* **Routing Effect:** High-Resolution Routing. The Stage 1 router can instantly choose between a safe, routine document and an acute clinical emergency node.

---

### 🧬 Sample Blueprint Target Resolution Output

Adjusting this setting alters the blueprint:

``` 
        {
            "topic_slug": "advice_for_trimester1_mothers",
        },
        {
            "topic_slug": "advice_for_trimester1_mothers_with_severe_anemia",
        }
```
