# 🛡️ Exploring Privacy Attacks on AI Models and Defense Strategies  
**Proposal**  
**Xiaohai Wang**  
**Master of Cybersecurity and Threat Intelligence**  
**Professor: Rozita Dara**  
**University of Guelph**  

---

## 🌟 Introduction  
Artificial intelligence (AI) is increasingly integrated into systems that handle sensitive personal data—such as healthcare, finance, and social platforms. However, AI models themselves are vulnerable to attacks that exploit or compromise privacy, posing a significant threat to both users and organizations.

Common attacks include:  
- **Data Poisoning**  
- **Adversarial Manipulation**  
- **Model Inversion**

These can undermine data confidentiality and model integrity. This project aims to explore these privacy attacks and develop robust defense strategies.

---

## 💡 Problem Statement / Motivation  
Modern AI systems are typically trained on massive datasets containing sensitive information. While these models offer superior predictive performance, they are also vulnerable to attacks that compromise data privacy and security.

For instance:  
- **Data Poisoning:** Bias or degrade AI performance, causing privacy leaks or unfair outcomes.  
- **Model Inversion:** Reveal sensitive training data.  
- **Membership Inference:** Determine whether a user’s data was part of the training dataset.

As AI adoption grows, so does the urgency to:  
1️⃣ Understand how these privacy attacks exploit AI vulnerabilities.  
2️⃣ Develop effective countermeasures to protect sensitive data and maintain trustworthiness.

---

## 🎯 Objectives  
1️⃣ **Analyze Privacy Attack Techniques**  
- Simulate attacks such as data poisoning, adversarial evasion, model inversion, and membership inference to evaluate their impact.

2️⃣ **Develop Detection and Mitigation Strategies**  
- Design robust defense mechanisms leveraging adversarial training, differential privacy, and other advanced techniques.

3️⃣ **Establish an Evaluation Framework**  
- Implement protocols to assess attack/defense effectiveness via quantitative and qualitative metrics (e.g., accuracy degradation, data exposure risk).

---

## 🛠️ Rough Methodology  
- **Literature Review:** Comprehensive study of privacy attack methods and their implications.  
- **Attack Simulation:** Develop Python-based implementations of attack types.  
- **Defense Implementation:** Incorporate differential privacy, adversarial training, and data sanitization techniques.  
- **Evaluation:** Systematic testing, measuring:  
  - Model performance before and after attacks  
  - Data exposure risk  
  - Effectiveness of defense mechanisms  

---

## 📊 Data  
We will use the **CDC Diabetes Health Indicators Dataset** from the Behavioral Risk Factor Surveillance System (BRFSS). It includes healthcare statistics and lifestyle survey information, focusing on diabetes diagnosis and pre-diabetic states.

**Key characteristics:**  
- **Dataset size:** 253,680 instances  
- **Features:** 21 categorical and integer variables (demographics, lab test results, survey answers)  
- **Target variable:**  
  - `0` — No diabetes / pregnancy-related  
  - `1` — Prediabetic  
  - `2` — Diabetic  

This dataset will support simulating privacy attacks and evaluating defense strategies. Due to its size and class imbalance, sampling techniques will be considered for efficient experimentation.

---

## ⚙️ Tools  
- **Python** (primary language)  
- **PyTorch / TensorFlow** (model development)  
- **Scikit-learn** (preprocessing/classical ML)  
- **Adversarial Robustness Toolbox (ART)** (attack/defense simulation)  
- **IDA Pro / Ghidra** (for binary-level security scenarios, if relevant)  

---

## 🔬 Experimental Settings  
- Use 2–3 ML models (e.g., CNNs, SVMs) as baselines.  
- Apply different attack methods sequentially to test vulnerabilities.  
- Evaluate performance degradation and quantify privacy risks.  
- Implement defense techniques and measure improvements in model robustness.  
- Conduct experiments on local GPUs or available university cluster resources.  

---

## 📈 Expected Outcomes  
- Comprehensive understanding of privacy attacks and their mechanisms.  
- Python-based tools to simulate and evaluate these attacks.  
- Report on the effectiveness and trade-offs of defense strategies.  
- Recommendations for best practices to safeguard sensitive personal data in AI systems.  

---
