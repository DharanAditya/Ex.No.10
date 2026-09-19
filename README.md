# EX.NO.10 – CONTENT CREATION USING PROMPT PATTERNS

**Name:** Dharan Aditya S 

**Register Number:** 212223040035

## AIM

To demonstrate how different prompting techniques can be used with ChatGPT to create structured content such as reports, articles and case studies, and to study how prompt refinement improves the quality, accuracy and organization of the generated content.

---

## PROMPT PATTERNS USED

* **Query Decomposition:** Breaking a complex topic into smaller tasks.
* **Decision Making:** Asking the AI to select the best option.
* **Answer Engineering:** Specifying the required format and structure.
* **Fact Check List:** Asking the AI to identify information that needs verification.
* **Tail Generation:** Extending existing content logically.
* **Menu Actions:** Providing multiple possible actions or directions.
* **Semantic Filter:** Controlling tone, style, relevance and content.

---

# TEST CASE 1 – ARTICLE ON CLIMATE CHANGE

## 1. Basic Prompt

```text id="x1q7ma"
Write an article about climate change.
```

### Output

```text id="k8v3pd"
Climate change refers to long-term changes in Earth's temperature
and weather patterns. Human activities such as burning fossil fuels
and deforestation contribute significantly to global warming.
Climate change affects ecosystems, agriculture and human life.
```

---

## 2. Query Decomposition Prompt

```text id="p4n6yt"
Write an article about climate change by covering:
1. Meaning of climate change
2. Major causes
3. Environmental effects
4. Effects on society
5. Possible solutions
6. Conclusion
```

### Output

The generated article contained separate sections for the causes, effects, solutions and conclusion, making the content more organized and easier to understand.

---

## 3. Answer Engineering + Semantic Filter

```text id="r9w2kc"
Write a 700-word educational article on climate change.

Structure it with:
- Introduction
- Causes
- Environmental impacts
- Social impacts
- Solutions
- Conclusion

Use a formal and educational tone. Use simple language,
avoid unnecessary repetition, and clearly distinguish
established facts from general suggestions.
```

### Observation

The refined prompt produced a more structured, readable and focused article compared with the basic prompt.

---

## 4. Fact Check List

```text id="m5d8qa"
Review the climate change article and create a fact-check list.
Identify statements that require verification and mention the
type of reliable source that should be consulted.
```

### Observation

The AI identified factual claims that should be verified using reliable scientific or institutional sources before publication.

---

# TEST CASE 2 – BUSINESS CASE STUDY

## Topic: Successful Digital Payment Application

## 1. Basic Prompt

```text id="v7k2le"
Write a case study about a successful digital payment application.
```

### Output

A general case study describing the application, its users, benefits and business growth was generated.

---

## 2. Query Decomposition

```text id="q3c9nf"
Create a business case study about a digital payment application.
Divide the case study into:
1. Background
2. Problem
3. Proposed solution
4. Implementation
5. Benefits
6. Challenges
7. Conclusion
```

### Observation

Breaking the topic into smaller sections produced a more complete and logically organized case study.

---

## 3. Decision-Making Prompt

```text id="z6h1rx"
For a digital payment application, choose the most important
business improvement among:
A. Faster transactions
B. Better security
C. Customer support
D. Marketing

Select one option and explain why it should be prioritized.
```

### Output

The AI selected **better security** as an important priority because protecting user transactions and personal information is essential for maintaining trust in a digital payment system.

---

## 4. Tail Generation

```text id="t2p8ws"
Continue the case study by adding a section on future improvements.
Discuss security enhancement, user experience, scalability and
new technological features while maintaining the same formal tone.
```

### Observation

Tail generation extended the case study while maintaining continuity with the previous sections.

---

## 5. Menu Actions + Semantic Filter

```text id="a4m7yx"
Choose the next section for the case study:

1. Future Improvements
2. Business Challenges
3. Customer Experience

Select the most relevant option and write the section in a
professional business-report style using concise and practical
language.
```

### Observation

The model selected a suitable direction and generated content according to the specified professional style.

---

# PROMPT REFINEMENT WORKFLOW

```text id="n5r8cd"
Topic Selection
      ↓
Basic Prompt
      ↓
Query Decomposition
      ↓
Decision Making
      ↓
Answer Engineering
      ↓
Fact Checking
      ↓
Tail Generation
      ↓
Semantic Filtering
      ↓
Final Content
```

---

# OUTPUT EVALUATION

### Coherence

The refined prompts produced logically connected sections with better organization.

### Creativity

Additional prompt instructions helped generate more relevant ideas and examples.

### Accuracy

Fact-checking prompts helped identify information that should be verified before using the content.

### Tone and Style

Semantic filtering allowed the content to be generated in formal, educational and professional styles.

### Overall Observation

Advanced prompting produced more structured and useful content than a simple one-line prompt.

---

# DELIVERABLES

1. First draft generated using a basic prompt.
2. Refined content generated using advanced prompt patterns.
3. Different prompt versions and corresponding outputs.
4. Final structured content.
5. Comparison and evaluation of the generated outputs.

---

## CONCLUSION

The experiment demonstrated that different prompt patterns can significantly improve AI-generated content. **Query decomposition, decision making, answer engineering, fact checking, tail generation, menu actions and semantic filtering** helped produce content that was more structured, relevant, coherent and suitable for specific purposes.

## RESULT

Content for two different scenarios was successfully generated and refined using multiple prompting techniques. The experiment showed that **well-designed prompts provide better control over the structure, quality, tone and usefulness of AI-generated content**.
