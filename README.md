# Conditional-Random-Fields-CRF
Custom CRF Class for Named Entity Recognition!

## Content
- Contains a CRF Util class for saving, loading and opening the input file;
- Contains a CRF Model class for training, predicting and changing parameters fo the CRF model from sklearn_crfsuite;
- The CRF model contains a set of ready to use internal features and options for adding external features;

<img src="./UML Diagram/Diagram Clean.png" alt="UML Diagram">

## Citation

```
@inproceedings{schneider-etal-2020-biobertpt,
    title = "{B}io{BERT}pt - A {P}ortuguese Neural Language Model for Clinical Named Entity Recognition",
    author = "Schneider, Elisa Terumi Rubel  and
      de Souza, Jo{\~a}o Vitor Andrioli  and
      Knafou, Julien  and
      Oliveira, Lucas Emanuel Silva e  and
      Copara, Jenny  and
      Gumiel, Yohan Bonescki  and
      Oliveira, Lucas Ferro Antunes de  and
      Paraiso, Emerson Cabrera  and
      Teodoro, Douglas  and
      Barra, Cl{\'a}udia Maria Cabral Moro",
    booktitle = "Proceedings of the 3rd Clinical Natural Language Processing Workshop",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.clinicalnlp-1.7",
    pages = "65--72",
    abstract = "With the growing number of electronic health record data, clinical NLP tasks have become increasingly relevant to unlock valuable information from unstructured clinical text. Although the performance of downstream NLP tasks, such as named-entity recognition (NER), in English corpus has recently improved by contextualised language models, less research is available for clinical texts in low resource languages. Our goal is to assess a deep contextual embedding model for Portuguese, so called BioBERTpt, to support clinical and biomedical NER. We transfer learned information encoded in a multilingual-BERT model to a corpora of clinical narratives and biomedical-scientific papers in Brazilian Portuguese. To evaluate the performance of BioBERTpt, we ran NER experiments on two annotated corpora containing clinical narratives and compared the results with existing BERT models. Our in-domain model outperformed the baseline model in F1-score by 2.72{\%}, achieving higher performance in 11 out of 13 assessed entities. We demonstrate that enriching contextual embedding models with domain literature can play an important role in improving performance for specific NLP tasks. The transfer learning process enhanced the Portuguese biomedical NER model by reducing the necessity of labeled data and the demand for retraining a whole new model.",
}
```
