# MILA: MULTILINGUAL INDIC LANGUAGE ARCHIVE
_A DATASET FOR EQUITABLE MULTILINGUAL LLMS_

### Metadata for Opensource Data: [MetaData](croissant-file/)
---

 ![Dataset Distribution](/readme-resources/compositional_analysis_with_english.png)

[MILA Neurips 2026 Submission](https://openreview.net/forum?id=FFWEtyB72h&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2026%2FEvaluations_and_Datasets_Track%2FAuthors%23your-submissions))

---

## Open Source Release

**We will Open Source the following:**

* **1 Trillion tokens** of high-quality pretraining data across **22 Scheduled Indian Languages**
* **300 Million image–text pairs** (spanning Indian languages, enabling Indic OCR and VLM development)
* **Indic Persona Hub (200 Million Indian virtual personas)**
* **India-centric parallel translated corpora** across **22 Scheduled Indian Languages**
* **Indic MMLU** benchmark covering 22 languages
* **Domain-specific Indian taxonomies**
* **High-quality web-crawled English**
* **Crawling and Scraping Pipelines**
* **First of its Kind Synthetic OCR Benchmark ISOB** across **22 Schedules Indian Languages**

**_A representative subset, reflecting the committed full open release, is available in this repository. Upon paper acceptance, the full dataset—together with proper legal licensing—will be released on GitHub and Hugging Face, in accordance with open-source best practices._**


---

## 📂 Repository Overview

This repository contains all resources, scripts, and datasets associated with our NeurIPS submission. Each major section of the paper has a corresponding folder in this repository, containing **training scripts, ablation study scripts, and detailed READMEs** to ensure **reproducibility**.

### 🎯 Main Sections

1. [**Data Acquisition**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/data-acquisition) 
2. [**Data Curation**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/data-curation) 
3. [**Data Organisation**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/data-organisation) 
4. [**Indic MMLU**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/indic-mmlu) 
5. [**OCR Pipeline**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/ocr-pipeline) 
6. [**ISOB**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/isob) 
7. [**Translation Pipeline**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/translation-pipeline) 
8. [**Rewriting & Data Distillation**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/rewriting-data-distillation) 
9. [**Final Experiment**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/final-experiment) 

---

### 🌐 Open Source Release

For reviewer access, a **representative subset** of the full open-source release is provided in the `opensource-release` folder. Upon **acceptance of the paper**, the complete datasets will be made publicly available with proper **metadata tagging** and under an **open-source license**.


**Available Open Source Subfolders:**

0. [**Open Source Release**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/opensource-release) – This folder contains all the below folders.
1. [**Indic MMLU**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/opensource-release/Indic%20MMLU) 
2. [**Image-Text Pairs**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/opensource-release/image-text-pairs) 
3. [**Indic Persona Hub**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/opensource-release/indic-personahub) 
4. [**ISOB-SMALL-HARD**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/opensource-release/isob-small-hard) 
5. [**Training Corpus**](https://github.com/anonymous-submitter0104/neurips-submission/tree/main/opensource-release/training-corpus) – Representative corpora for model training:

   * **Indian English**
   * **Parallel Corpus**
   * **Web Crawl**

Each of the above folders contains its own **README** detailing structure, format, and instructions for usage.

---

## Disclaimer

This repository is part of a research effort submitted to NeurIPS. 

Our objective is to **open-source large-scale Indian multilingual datasets** to strengthen the **open-source AI ecosystem** and promote **data sovereignty within the Indic AI community**.

All our pipelines are built entirely on **open-source models from Hugging Face**, ensuring full transparency and reproducibility. We **do not use any closed-source LLMs, VLMs, or proprietary AI systems** at any stage of data creation or processing — a deliberate choice to uphold **data sovereignty and ethical independence** in our work.

If required, we are open to publishing benchmark comparisons against **closed-source or proprietary systems**. However, we have consciously chosen **not to use** such systems in our workflow.

This decision stems from our **commitment to ethical data handling** and our **partnership agreements** with multiple data providers. Using closed or proprietary systems for tasks like OCR, translation, or data processing would involve transferring sensitive data to external servers—**beyond the scope of our agreements**, and hence, would be **ethically inappropriate**.

To uphold these standards, we have developed **fully open-source pipelines** that can be **deployed locally on GPU infrastructure**, ensuring both transparency and data integrity throughout the process.

We intend to release not only the **datasets** but also the **data preparation recipes** and the accompanying open-source code. By doing so, we hope to enable the community to reproduce, extend, and innovate upon our methods in a fully transparent and sovereign manner.


## ❤️ A Note from the Authors

This work represents a **fundamentally foundational step** in what we believe to be one of the most important and underexplored areas of modern AI / Generative AI — **data preparation for training large language models**. While often considered an auxiliary process, our extensive experiments and ablation studies reaffirm that **careful data preparation is not just a prerequisite but a cornerstone** for building performant and responsible LLMs.

Through our experience, we have come to realize that **data preparation for pretraining remains one of the most complex, least standardized, and least openly studied components** of the LLM pipeline. Despite being central to every foundation model’s success, **there exists no peer-reviewed framework or systematically validated body of work** in this space.

Our intent with this submission is to **broaden the conversation on what constitutes valuable and rigorous scientific contribution** in AI. By presenting this work in a **peer-reviewed, open-source setting**, we hope to **encourage transparency, reproducibility, and community validation**, and to inspire other research groups and top-tier labs to bring similar efforts into the open domain.

We firmly believe that **progress in generative AI should be built on openness, shared validation, and collective growth**. If this work helps spark even a small shift toward greater transparency in data processes and benchmarking, we would consider it a meaningful step forward — for the community, and for the collective progress of humanity in AI.








