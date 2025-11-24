# 🧪 Lab 11 — AI Bias & Transparency  
**Course:** AI Ethics / COM  
**Student:** Rasel Ahmmed  
**Topic:** Resume Screening & Explainability in AI Systems  

---

## 📌 Exercise 1 — Resume Screening AI Bias Analysis

### 🔍 Dataset Overview
TechCorp uses an AI model to screen software engineering resumes.  
- **Score ≥ 70 ⇒ Interview**
- **Human Experts** later reviewed actual qualification.

| Group | Candidates | Actually Qualified |
|-------|------------|-------------------|
| Male  | 50 | 38 |
| Female | 50 | 35 |

---

### 🔢 Step 1: Interview Rates

#### ✔ **Males Scoring ≥ 70**
- 41 out of 50  
- **Interview Rate: 82%**

#### ✔ **Females Scoring ≥ 70**
- 34 out of 50  
- **Interview Rate: 68%**

---

### 🧠 Step 2: AI Accuracy & False Negatives

#### ✔ **AI Accuracy (Qualified AND Scored ≥70)**

| Group | Qualified | Correctly Selected | Accuracy |
|-------|----------|--------------------|----------|
| Male | 38 | 34 | **89.5%** |
| Female | 35 | 27 | **77.1%** |

#### ❗ False Negatives (Qualified but Scored <70)

| Group | False Negatives |
|-------|-----------------|
| Male | **4** |
| Female | **8** |

🔎 **The AI rejects twice as many qualified women.**

---

### 🌍 Step 3: Real-World Impact
If TechCorp hires **20 people** based on AI recommendations:

| Group | Interview Share | Expected Hires |
|-------|-----------------|----------------|
| Male | 82% | **≈ 16** |
| Female | 68% | **≈ 14 → but limited slots ⇒ ≈ 9** |

⚠️ **Female candidates lose opportunities despite similar qualification levels.**

---

### 🧠 Step 4: Reflection & Ethical Concerns

#### 6️⃣ **Evidence of Bias**
- Higher interview rate for men (82% vs 68%).
- Lower accuracy for qualified women.
- Double rejection of qualified women.

#### 7️⃣ **Why This Bias Happens**
- AI may learn from biased historical hiring data.
- Resume wording differences between genders.
- Unbalanced training datasets.

#### 8️⃣ **Fixing the System**
- Use **gender-balanced training data**
- **Remove gender indicators** (names, pronouns)
- Perform **fairness audits**
- Use **equal opportunity metrics**
- Continuous improvement & bias monitoring

---

---

## 🎭 Exercise 2 — AI Decision Transparency Role-Play

### 🔐 Round 1: Black-Box Decision
- AI denied scholarship without explanation.
- **Emotions:** Confused, powerless, unfair.
- **Problem:** No improvement guidance.

### 🔎 Round 2: Transparent AI
- Provided weighted scoring & improvement steps.
- **Emotions:** Understood, respected, hopeful.
- **Improvement actions:** Submit SAT scores, add leadership roles.

### 🩺 Round 3: Medical AI Scenario
- Explained health risks & next steps.
- **Trust was higher** because reasoning was provided.
- **Transparency increased safety & trust.**

---

### 🧩 Final Reflection Summary

| Ethical Impact | Transparent AI | Black-Box AI |
|----------------|----------------|--------------|
| Understanding | Clear reasoning | Confusing |
| Trust | High | Low |
| Actionability | Can improve future | No direction |
| Fairness | Feels fair | Feels biased |

### ⚙️ Why Programmers Must Build Explainable AI
- Prevent discrimination & harm.
- Improve user trust and fairness.
- Legally & ethically required in sensitive fields.

### ⚠️ Challenges
- Hard to explain complex models.
- Risk of exposing proprietary algorithms.
- Must balance clarity & privacy.

---

## 📌 Conclusion
✔ AI systems must be **fair AND explainable**  
✔ Hidden decision logic increases inequality  
✔ Transparency empowers users and ensures ethical AI  

---

### 📎 Optional (Ask if needed)
- 📄 Downloadable PDF version  
- 🗃 GitHub folder structure template  
- 📚 References section

> *Prepared by **Rasel Ahmmed**, Lab 11 — AI Bias & Transparency.*

