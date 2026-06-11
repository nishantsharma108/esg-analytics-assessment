# ESG Analytics Assessment

## Overview

This repository contains evidence files for the Data in the Cloud Assessment 3 practical tasks for GreenCorp Australia. The assessment work focuses on using AI and cloud-based tools to support ESG issue triage, ESG reporting standards analysis, and evidence-based reporting.

## Organisation Context

- Organisation: GreenCorp Australia
- Chatbot name: EcoAssist
- Q3 LLM used: Claude Sonnet
- Q3 comparison tool: Hugging Face Zero-Shot Text Classification
- Q4 tool used: Google NotebookLM
- NotebookLM notebook name: ESG Reporting Standards Analysis

## Repository Structure

```text
esg-analytics-assessment/
├── README.md
├── Q3_LLM_Triage/
│   ├── revised_prompt_template.txt
│   ├── message1_water_leak_output.json
│   ├── message2_recycling_output.json
│   ├── message3_supplier_output.json
│   ├── huggingface_message1_screenshot.png
│   ├── huggingface_message2_screenshot.png
│   └── huggingface_message3_screenshot.png
└── Q4_NotebookLM/
    ├── experiment_log.md
    ├── notebooklm_qa_screenshot.png
    ├── notebooklm_summary_screenshot.png
    ├── notebooklm_audio_screenshot.png
    ├── notebooklm_guide_screenshot.png
    └── notebooklm_synthesis_screenshot.png
```

## Q3: LLM ESG Triage

Q3 tested whether a large language model could classify employee-submitted ESG, sustainability, facilities, procurement, and governance messages into structured triage outputs.

The Q3 folder includes:

- revised_prompt_template.txt
- message1_water_leak_output.json
- message2_recycling_output.json
- message3_supplier_output.json
- Hugging Face zero-shot classifier screenshots

The LLM outputs were compared against Hugging Face zero-shot classification results using the following candidate labels:

```text
ENERGY, WATER, WASTE, FACILITIES, PROCUREMENT, ACCESSIBILITY, GOVERNANCE, WELLBEING, OTHER
```

## Q4: NotebookLM ESG Reporting Standards Analysis

Q4 tested Google NotebookLM as an AI-assisted research tool for analysing ESG reporting standards. The notebook was named **ESG Reporting Standards Analysis** and included uploaded ESG reporting source documents.

The Q4 folder includes:

- experiment_log.md
- source-grounded Q&A screenshot
- source guide / document summary screenshot
- Audio Overview screenshot
- Notebook Guide / Reports screenshot
- cross-document synthesis screenshot

