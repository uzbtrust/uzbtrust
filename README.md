### Dostonbek Abdurakhmonov

NLP and applied ML, based in Uzbekistan. I build things end-to-end — data, models, and the product wrapped around them — mostly for low-resource languages and safety-sensitive domains.

**Currently:** hybrid neural/rule-based systems for Uzbek NLP, and clinically-oriented ML with explicit fairness and calibration checks.

---

#### Projects

**[UZ-ByT5 — Uzbek Morpheme Analyzer](https://github.com/uzbtrust/uzbek-morpheme-analyzer)**
A hybrid system that segments Uzbek words into root/derivational/lexical/syntactic morphemes, restores dictionary forms, and explains each part. Fine-tuned ByT5 with a deterministic rule-based fallback for anything the model gets wrong.
`Python` · `Transformers` · `Streamlit` · [model](https://huggingface.co/uzbtrust/uzbek-morpheme-byt5) · [paper](https://github.com/uzbtrust/uzbek-morpheme-analyzer/blob/main/paper/Uzbek_Morfema_ByT5.pdf)

**[TriageGeist](https://github.com/uzbtrust/triagegeist)**
A 4-model emergency severity index (ESI) ensemble evaluated for clinical safety: split conformal prediction, asymmetric under-triage cost, and a fairness audit across sex, language, age, and site on 80,000 patients.
`Bio_ClinicalBERT` · `Conformal prediction` · `Fairness auditing`

**[Uzbek Operator RAG](https://github.com/uzbtrust/uzbek-operator-rag)**
A retrieval-augmented generation pipeline for an Uzbek telecom operator chatbot: custom BPE tokenizer, a BERT-style transformer pretrained with MLM + SimCSE, and a hybrid retriever, with no LangChain or LlamaIndex in the stack.
`PyTorch` · `Transformers` · `FAISS`

**[Uzbek Operator NER](https://github.com/uzbtrust/uzbek-operator-ner)**
The information-extraction half of the same chatbot: a BiLSTM-CRF sequence tagger for English and Russian with custom domain entities.
`PyTorch` · `BiLSTM-CRF`

---

#### Writing

- [From Scratch: Multilingual BiLSTM-CRF NER and Hybrid RAG for an Uzbek Telecom Chatbot](https://zenodo.org/records/19451409)

---

[LinkedIn](https://www.linkedin.com/in/dostonbek-abdurakhmonov/) · [Telegram](https://t.me/uzbtrust) · [Email](mailto:uzbekuzdev@gmail.com)
