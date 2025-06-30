# ABCI: Automated Building Code Interpreter

## Abstract

South Korean authorities handle over 2,000 inquiries daily about building code violations. Interpreting these complex, frequently updated codes is challenging, even for legal experts. Prior studies using large language models (LLMs) with retrieval-augmented generation (RAG) have struggled with context loss due to data segmentation. This study proposes three automated building code interpreter (ABCI) models—Original, Inferred, and Filtered—that leverage long-context window (LCW) LLMs as the base model.

On 171 challenging legal interpretative question-answering (LIQA) cases, ABCI-Filtered achieved **63.2% accuracy**, outperforming the RAG baseline approach (56.1%), state-of-the-art LLMs like Claude 3.7 (60.2%), as well as ABCI-Inferred (60.8%) and ABCI-Original (56.7%). Notably, unlike prior methods that require fine-tuning, ABCI-Filtered outperformed previous methods using only zero-shot reasoning. In an additional experiment using a relatively straightforward building code QA dataset, ABCI-Filtered and Inferred outperformed the other methods (79.6% and 80.0%, respectively), confirming the difficulty of the initial task using the LIQA dataset.

---

## Repository Contents

This repository will include:

- Code for the **ABCI models** (Original, Inferred, Filtered) *(To be released)*
- Code for **testing and benchmarking** other state-of-the-art (SOTA) models (SOTA_comparison.ipynb)
- Links to related resources:
  - [Baseline RAG Paper](https://www.auri.re.kr/publication/view.es?mid=a20504000000&publication_type=eng_research&publication_id=2044)
  - **LIQA Dataset**
    - [Example cases from the LIQA Dataset](http://www.siranews.co.kr/news/articleView.html?idxno=1498)
    - The full dataset is now available in the `Dataset` folder.
        <br>**Usage**: This dataset is available for **public interest use only**.  
        > **Copyright ©** Korea Institute of Registered Architects (대한건축사협회)  
  - [BEQA Dataset](https://archi.inup.co.kr/cbt/new_pattern_list.jsp?s_item_id=4&type=1)

---

## Timeline & Updates

- 📄 The conference paper will be presented at **ISARC 2025**, and the journal paper is currently under review.
- 🛠️ **Codebase will be publicly available by the end of June**

Stay tuned for updates!

---

## Citation

> Please consider citing our work once the official paper is released. BibTeX will be provided here.

---

Thank you for your interest! Contributions and feedback are welcome once the code is live.)
