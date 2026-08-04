### Dostonbek Abdurakhmonov

NLP and applied ML, based in Uzbekistan. I build things end-to-end — data, models, and the product wrapped around them — mostly for low-resource languages and safety-sensitive domains.

**Currently:** hybrid neural/rule-based systems for Uzbek NLP, and clinically-oriented ML with explicit fairness and calibration checks.

---

#### Projects

**[Smart Road](https://github.com/uzbtrust/smart-road)**
Grades asphalt through ASTM D6433 instead of counting defects: a YOLO11 detector over eight distress classes mapped onto the standard's taxonomy (mAP50 0.657 over 113,648 boxes), inverse perspective mapping to recover square metres on the road plane, and the deduct-value mathematics that turns densities into a Pavement Condition Index. The engine reproduces the worked example printed in the standard — 48.6 against a published 49.
`PyTorch` · `YOLO11` · `Streamlit` · [model](https://huggingface.co/uzbtrust/smart-road-pci-yolo11) · [dataset](https://www.kaggle.com/datasets/uzbtrust/smartroad-yolo)

**[UZ-ByT5 — Uzbek Morpheme Analyzer](https://github.com/uzbtrust/uzbek-morpheme-analyzer)**
A hybrid system that segments Uzbek words into root/derivational/lexical/syntactic morphemes, restores dictionary forms, and explains each part. Fine-tuned ByT5 with a deterministic rule-based fallback for anything the model gets wrong.
`Python` · `Transformers` · `Streamlit` · [model](https://huggingface.co/uzbtrust/uzbek-morpheme-byt5) · [paper](https://github.com/uzbtrust/uzbek-morpheme-analyzer/blob/main/paper/Uzbek_Morfema_ByT5.pdf)

**[TriageGeist](https://github.com/uzbtrust/triagegeist)**
A 4-model emergency severity index (ESI) ensemble evaluated for clinical safety: split conformal prediction, asymmetric under-triage cost, and a fairness audit across sex, language, age, and site on 80,000 patients.
`Bio_ClinicalBERT` · `Conformal prediction` · `Fairness auditing` · [demo](https://huggingface.co/spaces/uzbtrust/triagegeist)

**[Uzbek Operator RAG](https://github.com/uzbtrust/uzbek-operator-rag)**
A retrieval-augmented generation pipeline for an Uzbek telecom operator chatbot: custom BPE tokenizer, a BERT-style transformer pretrained with MLM + SimCSE, and a hybrid retriever, with no LangChain or LlamaIndex in the stack.
`PyTorch` · `Transformers` · `FAISS` · [model](https://huggingface.co/uzbtrust/uzbek-operator-rag)

**[Uzbek Operator NER](https://github.com/uzbtrust/uzbek-operator-ner)**
The information-extraction half of the same chatbot: a BiLSTM-CRF sequence tagger for English and Russian with custom domain entities.
`PyTorch` · `BiLSTM-CRF` · [model](https://huggingface.co/uzbtrust/uzbek-operator-ner)

**[Stenoz](https://github.com/uzbtrust/stenoz)**
A two-stage coronary stenosis detector for X-ray angiography: a U-Net trained directly on lesion masks (test F1 0.645, 95.7% lesion recall) paired with an interpretable geometric diameter-profiling layer, validated against a synthetic-injection ground truth.
`PyTorch` · `U-Net` · `Streamlit` · [model](https://huggingface.co/uzbtrust/stenoz-coronary-stenosis-unet) · [paper](https://github.com/uzbtrust/stenoz/blob/main/report/Stenoz_Ilmiy_Maqola.pdf)

---

#### Writing

- [From Scratch: Multilingual BiLSTM-CRF NER and Hybrid RAG for an Uzbek Telecom Chatbot](https://zenodo.org/records/19451409)

---

[LinkedIn](https://www.linkedin.com/in/dostonbek-abdurakhmonov/) · [Telegram](https://t.me/uzbtrust) · [Email](mailto:uzbekuzdev@gmail.com)
