
# Sample output from the Wiki Question Answering 

---

## How the Wiki QA arrived at this answer?
https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/tree/main/WikiContents/Human-in-loop


## Sample output of Wiki QA system 

Here is the actual output 

https://github.com/ai-socialimpact/LLMWiki-NGO-Humaninloop/blob/main/WikiContents/Outputs/Version1/QASample.pdf
 
---

### 1. Immediate Care for Lower Abdominal Pain

* **User Query:** `pregnancy me pet k nichle hisse me dard kyun hota hai`

#### 💬 Verbatim   Answer
> "Pet ke nichle hisse me dard pregnancy ke dauran ek danger sign ho sakta hai. Ye severe abdominal pain kehlata hai aur iske liye turant doctor se sampark karna chahiye. [Source: Ante natal care document.md]"

#### ⚙️   Wiki Thinking
* **Translation:** User asks about the cause of lower abdominal pain during pregnancy.
* **Intent & Protocol:** Identified as an acute severity or high-alert symptom (`Symptoms/Emergencies`). This automatically triggers a `TRIGGER_ACUTE_REDIRECTION_MANDATE`.
* **File Selection:** System maps keywords to "severe abdominal pain" and "pregnancy emergency", bypassing standard pools to route directly to `maternal_danger_signs_and_emergencies.md`.

---

### 2. Diet Chart for 8 Months Pregnancy

* **User Query:** `8 months pregnancy diet chart do`

#### 💬 Verbatim   Answer
> "Aapko 8 mahine ki pregnancy mein kuch extra khana chahiye:
> - Har din 350 extra calories aur 18 grams protein lena zaroori hai. [Source: PNC nutrition and anemia.md]
> - Ek extra meal apne regular diet ke saath khayein. [Source: Essential Nutrients for A Pregnant Woman.md]
> - 4-5 chhoti meals aur healthy snacks din bhar mein lein. [Source: Essential Nutrients for A Pregnant Woman.md]
> - Iron aur Folic Acid ki goliya lena na bhulein. [Source: PNC nutrition and anemia.md]"

#### ⚙️  Wiki Thinking
* **Translation:** User requests an 8-month pregnancy diet plan.
* **Intent & Protocol:** Classified under `lifestyle_nutrition`. Because a milestone ("8 months / third trimester") is explicitly mentioned, the system activates chronological routing.
* **File Selection:** Shortlists and approves `maternal_care_trimester_3_and_birth_prep.md` with no negative exclusions applied.
