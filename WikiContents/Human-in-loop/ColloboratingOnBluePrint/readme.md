### 🎨 Colloborating with NGO Program Owner on the Blueprint Design for Wiki

Phase 1 processes your unstructured text library through a 5-pass  compilation sequence.

## 🛠️ NGO Program Owners can shape the Wiki with Human in the Loop 

###  NGO Program Owners can shape the Wiki structure (topics wise organization or trimester wise organization) and control the depth/focus by tunning the number of topics in Wiki 

An NGO Administrator can control how precisely the chatbot route answers by tuning the **Thematic Topic Count Limits** inside the Phase 1 pipeline . 

By instructing the LLM Wiki compiler to enforce tighter or broader grouping rules during the initial planning passes, you explicitly change the data breakdown inside the final `master_taxonomy_blueprint.json` contract.

### 🎛️ How Admin Configuration Changes the Blueprint

By modifying the parameters inside the **`INSTRUCTIONs`** framework, you directly impact how the LLM  Wiki splits and organizes overlapping topics like trimesters and clinical risk states:

#### 📉 Setting Broad Topics (Min: 10 / Max: 25)
* **Admin Directive:** *"Propose an initial balanced directory taxonomy of 10 to 25 distinct, master topics."*
* **Blueprint Result:** The pipeline compiles info into fewer, larger markdown guides. General nutrition and severe anemia collapse into a single file path.
* **Routing Effect:** Low-Resolution Routing. The system easily routes to general categories, but risks mixing routine advice with high-risk clinical indicators.
* [Organize as 21 topic Wiki](https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/WikiContents/Human-in-loop/ColloboratingOnBluePrint/20%2Btopics/master_taxonomy_blueprint%20(5).json)

#### 📈 Setting High-Resolution Topics (Min: 20 / Max: 45)
* **Admin Directive:** *"Propose an initial balanced directory taxonomy of 20 to 45 distinct, master topics."*
* **Blueprint Result:** The engine separates overlapping concepts. Routine lifestyle trackers are split cleanly away from emergency danger signs.
* **Routing Effect:** High-Resolution Routing. The Stage 1 router can instantly choose between a safe, routine document and an acute clinical emergency node.
* [Reorganize a 27 topic Wiki](https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/WikiContents/Human-in-loop/ColloboratingOnBluePrint/30%2Btopics/pass_1d_hardened_boundaries%20(3).txt)

---


### 🎛️ Human in the loop: Colloborating with the AI on the Mental Model to the create the desired Blueprint


```text
[Raw Files + NGO Program Director Guidance]
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


### 🧬 NGO Program directors can shape the how the topics are organized in the Wiki by providing this guidance to AI

```python
WikiTEMPLATE_Guidance = """

CRITICAL BUSINESS USE CASE CONTEXT & THEMATIC BOUNDARY LOCKS: 
The downstream application is a conversational WhatsApp Chatbot designed to provide authoritative public health awareness and medical advice to pregnant mothers and caregivers in local urban slum communities in Mumbai in India. Users naturally frame questions based on specific timelines (their current trimester or their child's exact age) or critical symptoms. Some users frame questions asking for information about government schemes or facilities provided by govt.

To maximize downstream question-answering routing utility and achieve perfect isolation for GPT-4o attention layers, you must actively organize these topic boundaries strictly into a balanced directory taxonomy of minimum 10 and maximum 25 distinct, mutually exclusive topic containers. Follow these specialized layout mandates:

1. CHRONOLOGICAL MATERNAL TRACKING: Group nutritional interventions, diagnostic schedules, and routine field advice explicitly by milestone windows (e.g., 'nutritional_interventions_for_trimester1_mothers', 'screening_protocols_for_trimester3_mothers').

2. PEDIATRIC DEVELOPMENT HORIZONS: Categorize infant care, complementary feeding rules, and monitoring timelines by age boundaries (e.g., 'nutritional_interventions_for_children_below_6months', 'immunization_schedules_6_to_12_months').

3. ACUTE CLINICAL TRIGGERS: Isolate severe danger signs or critical emergency workflows into high-density, specialized files (e.g., 'advice_for_trimester1_mothers_with_severe_anemia', 'emergency_water_chlorination_ratios') so that urgent, high-risk queries route instantly to targeted, error-free files.

4. GOVERNMENT SOCIAL PROTECTION AND CASH BENEFIT SCHEMES: Isolate administrative financial aid rules into dedicated files mapping specific government social protection schemes (e.g., eligibility requirements, income/  restrictions, required documentation checklists).
"""
```

 

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
