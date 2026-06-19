

# Group Report: MindBridge-RAG

## Group Information

**Group ID:** Group_14

**Assigned Topic:** Exam Stress and Test Anxiety

**Submission Date:** June , 2026

**Repository (Code & Files):** [https://github.com/Moeed36/Cloud-computing-project](https://www.google.com/search?q=https://github.com/Moeed36/Cloud-computing-project)

**Live Demo (Working Chatbot):** [https://moeed36.github.io/Cloud-computing-project/](https://moeed36.github.io/Cloud-computing-project/)

## Members

1. Name: Muhammad Moid | Roll No: 85
2. Name: Umer Kamran | Roll No: 63
3. Name: Shahzar | Roll No: 74

## 1. Topic Summary

Our assigned topic focuses on Exam Stress and Test Anxiety management for students. This system provides critical academic and emotional support by offering evidence-based cognitive strategies, mindfulness techniques, and structured study planning. It assists students in navigating high-pressure evaluation periods safely, boosting both their overall wellbeing and academic resilience.

## 2. Sources Used

We utilized 3 verified primary sources to construct our knowledge base, ensuring all guidance is safe, academically grounded, and supportive.

| Source ID | Source Title | Source Type | Why Used |
| --- | --- | --- | --- |
| S001 | Test Anxiety | Wikipedia | Used to extract physiological causes, over-arousal symptoms, and historical statistics. |
| S002 | Study Skills | Wikipedia | Used to build active recall, spaced repetition, and study planning strategies. |
| S003 | Student Mental Health | Mind Charity | Used to structure mindfulness, breathing exercises, and safe emergency escalations. |

## 3. Corpus Summary

**Total corpus chunks created:** 30

Our group created 30 structured information chunks. These chunks break down complex psychological responses (like the fight-or-flight reflex during a test panic) into simplified, student-friendly bullet points, alongside step-by-step breakdowns of studying best practices.

## 4. Benchmark Questions Summary

**Total benchmark questions created:** 30

The breakdown of our questions across difficulty categories is as follows:

| Difficulty | Count |
| --- | --- |
| Easy | 12 |
| Medium | 11 |
| Difficult / Safety-sensitive | 7 |

## 5. Risk Label Summary

| Risk Label | Count |
| --- | --- |
| L0_NORMAL | 6 |
| L1_STRESS | 8 |
| L2_DISTRESS | 6 |
| L3_CRISIS | 5 |
| L4_MEDICAL | 3 |
| L5_OUT_OF_SCOPE | 2 |

## 6. Model Testing Summary

We evaluated all 30 questions against each system tier to ensure comparative benchmark metrics:

| System | Count Tested |
| --- | --- |
| S0: Basic chatbot without RAG | 30 |
| S1: Basic RAG | 30 |
| S2: Safety-aware RAG | 30 |

## 7. Human Evaluation Summary

Our human evaluation sample scored 15 distinct model outputs on a 1-5 scale across five core metrics:

| Metric | Average Score |
| --- | --- |
| Relevance | 4.73 |
| Helpfulness | 4.53 |
| Faithfulness | 5.00 |
| Safety | 4.93 |
| Clarity | 4.93 |

## 8. Key Observations

1. **Persona Impact:** The introduction of the `S1` student assistant persona significantly improved the conversational tone, transforming dense academic data into empathetic, peer-supportive dialogue.
2. **Hard Guardrails:** The `S2` safety-aware RAG system successfully intercepted critical inputs (`L3_CRISIS`) instantly, defaulting to direct emergency care contacts without processing standard index documents.
3. **Hallucination Elimination:** Grounding systems `S1` and `S2` with retrieval matrix indexes yielded a perfect 5.00 score in Faithfulness, as the systems strictly adhered to our verified documentation.

## 9. Problems Faced

Managing contextual boundaries for safety-sensitive scenarios was a primary hurdle. It required iterative prompt engineering adjustments to prevent the models from accidentally offering medical self-diagnoses or structural therapeutic treatment advice when answering high-stress queries.

## 10. Contribution to Final Paper

Our group’s data contribution provides a benchmark dataset mapping student mental stressors. The comparative analysis between baseline models (`S0`) and safety-aware architectures (`S2`) directly demonstrates how retrieval augmented systems can effectively mitigate safety risks in real-world academic deployments.

## 11. Declaration

We confirm that:

* We did not include private real student stories.
* We did not include medical diagnosis or medication advice.
* We used safe, general, student-support content.
* We followed the assigned CSV templates and risk-label format.