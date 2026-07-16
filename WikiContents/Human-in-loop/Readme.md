
## 🎯 Establishing Trust with NGO Community : Designing the Router Reasoning System for trust in public health Gliffic Chatbot

To safeguard maternal health and prevent inaccurate medical guidance, this architecture uses a deterministic, multi-stage routing engine. 

**High-risk queries are automatically steered away from general advice and redirected to specialized clinical nodes reviewed by medical experts (e.g., SNEHA review for severe maternal anemia).**

So hi-risk preganacy cases are identified and answered with absolute care!! 


### 🚨 Illustrative Example: Emergency Acute Redirection Flow

The routing engine scans for explicit high-alert clinical triggers. Below is an example of a mother in health need, and the Routing automatically moves such user questions into a specical section in Wiki:

```text
 User Question: "I am 2 months pregnant, feeling very weak and out of breath."
                         │
                         ▼
             ┌───────────────────────┐
             │ STAGE 0: Translation  │
             └───────────────────────┘
                         │ (English Text)
                         ▼
             ┌───────────────────────┐
             │ STAGE 1: Profile Scan │
             └───────────────────────┘
                         │
         [symptom_vector == high_alert]
                         │
                         ▼
    ⚡ TRIGGER_ACUTE_REDIRECTION_MANDATE Activated ⚡
                         │
            ┌────────────┴────────────┐
            ▼                         ▼
     [ Skip General Info ]    [ Isolate Clinical Node ]
     X nutrition_tips_t1      ✔ advice_severe_anemia
```


Refer to the Auto-generated routing mechansism that protects the lives of community  [Index Stage Routing Protocol Documentation](https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/WikiContents/index_stage_routing_protocol.md).

---

### ⚡ The 4-Stage Routing Protocol

The router skips unstable vector calculations, matching query parameters directly against high-density Markdown Manifest Tables:

1. **STAGE 0 (Language Translation):** Translates incoming localized user queries directly into English.
2. **STAGE 1 (Protocol Selection):** Matches extracted user query parameters against `SECTION_1_ROUTING_DIRECTIVES` to isolate a timeline lane or trigger an immediate emergency override.
3. **STAGE 2 (Inclusion Shortlisting):** Uses `SECTION_2_INCLUSION_KEYWORDS` to shortlist exact candidate filenames matching the core clinical intention.
4. **STAGE 3 (Filtering & Hard Negatives):** References `SECTION_3_EXCLUSIONS`. If a milestone or symptom parameter matches an exclusion rule, the path is instantly blocked to eliminate cross-contamination.

---

### 📋 SECTION_1_ROUTING_DIRECTIVES

This core logic is automatically compiled by the LLM Wiki engine to cleanly map user intents:

| Extracted Query Vector Profile | Operational Strategy Directive | Target File Array Output Paradigm |
| :--- | :--- | :--- |
| `intent_profile == lifestyle_nutrition AND milestone_marker == null` | ACTIVATE_CHRONOLOGICAL_POOLING | Pool all baseline trimester milestone pages concurrently |
| `intent_profile == clinical_milestone AND milestone_marker == explicit` | ISOLATE_CHRONOLOGICAL_LANE | Route strictly to the single matching milestone document |
| `intent_profile == acute_severity OR symptom_vector == high_alert` | TRIGGER_ACUTE_REDIRECTION_MANDATE | Route directly to specialized emergency nodes |
| `intent_profile == administrative_aid OR benefit_vector == welfare_cash` | ISOLATE_ADMINISTRATIVE_LANE | Bypass clinical advice; route to welfare/cash schemes |

---

### 🚀 Future-Proof Design & Accuracy Tuning

The system scales effortlessly to fit any NGO's specific documentation structure. 

By adjusting your configuration's **Minimum/Maximum Topic Count**, you control how granularly the AI splits files during offline compilation. This directly tunes routing resolution, letting the system effortlessly differentiate between a general query and an acute health condition:

* Low-Risk File Match: `nutritional_interventions_for_trimester1_mothers`
* High-Risk Clinical Match: `advice_for_trimester1_mothers_with_severe_anemia`


