# Financial LLM Taxonomy for InstructLab Fine-Tuning

Overview

This repository contains a taxonomy-driven dataset designed for fine-tuning large language models (LLMs) using InstructLab on OpenShift AI. The goal is to enhance financial AI models by:

✅ Improving domain-specific knowledge (e.g., EBITDA, net income, P/E ratios)<br>
✅ Ensuring compliance-safe responses for investment-related queries<br>
✅ Refining retrieval-augmented generation (RAG) outputs for financial assistants

## Repository Structure

```
financial-llm-taxonomy/
│── knowledge/
│   ├── financial_terms.yaml         # Defines key financial terminology
│   ├── regulatory_guidance.yaml     # Ensures model adheres to financial regulations
│── skills/
│   ├── summarization.yaml           # Fine-tunes model for summarizing financial data
│   ├── compliance_safe_responses.yaml # Prevents hallucinated investment advice
│── tests/
│   ├── validation_questions.yaml    # Test cases for model evaluation
│── config.yaml                      # Taxonomy structure configuration
│── README.md                        # This document
```

## Using This Taxonomy with InstructLab on OpenShift AI

Placeholder

## More Resources

📌 [Red Hat OpenShift AI][rhoai-overview]<br>
📌 [Getting Started with InstructLab][ilab-blog]<br>
📌 [InstructLab GitHub][ilab-gh]

[rhoai-overview]: https://www.redhat.com/en/resources/openshift-ai-overview
[ilab-blog]: https://developers.redhat.com/blog/2024/06/12/getting-started-instructlab-generative-ai-model-tuning
[ilab-gh]: https://github.com/instructlab/instructlab