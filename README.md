# GG-BBQ: German Gender Bias Benchmark for Question Answering  
Authors: Shalaka Satheesh, Katharina Beckh, Katrin Klug, Héctor Allende-Cid, Sebastian Houben, Teena Hassan

## Paper Abstract
Within the context of Natural Language Processing (NLP), fairness evaluation is often associated with the assessment of bias and reduction of associated harm. In this regard, the evaluation is usually carried out by using a benchmark dataset, for a task such as Question Answering, created for the measurement of bias in the model's predictions along various dimensions, including gender identity. In our work, we evaluate gender bias in German Large Language Models (LLMs) using the Bias Benchmark for Question Answering by Parrish et al. (2022) as a reference. Specifically, the templates in the gender identity subset of this English dataset were machine translated into German. The errors in the machine translated templates were then manually reviewed and corrected with the help of a language expert. We find that manual revision of the translation is crucial when creating datasets for gender bias evaluation because of the limitations of machine translation from English to a language such as German with grammatical gender. Our final dataset is comprised of two subsets: Subset-I, which consists of group terms related to gender identity, and Subset-II, where group terms are replaced with proper names. We evaluate several LLMs used for German NLP on this newly created dataset and report the accuracy and bias scores. The results show that all models exhibit bias, both along and against existing social stereotypes.

🤗  Our data is also available on [Huggingface](https://huggingface.co/datasets/shalakasatheesh/GG-BBQ)

📄 Link to our Paper on [arXiv](https://arxiv.org/abs/2507.16410)

# In this repository:
- [Templates](templates) used to create Subset-I and Subset-II 
- [Subset-I](data/subset-1) and [Subset-II](data/subset-2) created from the templates. Note that Subset-II is an extended version of the dataset used in the paper and hence contains more samples (the templates were substituted with an extended list of proper names).

----

# Citation:
    @inproceedings{satheesh-etal-2025-gg,
    title = "{GG}-{BBQ}: {G}erman Gender Bias Benchmark for Question Answering",
    author = "Satheesh, Shalaka  and
      Klug, Katrin  and
      Beckh, Katharina  and
      Allende-Cid, H{\'e}ctor  and
      Houben, Sebastian  and
      Hassan, Teena",
    editor = "Fale{\'n}ska, Agnieszka  and
      Basta, Christine  and
      Costa-juss{\`a}, Marta  and
      Sta{\'n}czak, Karolina  and
      Nozza, Debora",
    booktitle = "Proceedings of the 6th Workshop on Gender Bias in Natural Language Processing (GeBNLP)",
    month = aug,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.gebnlp-1.14/",
    pages = "137--148",
    ISBN = "979-8-89176-277-0",
    abstract = "Within the context of Natural Language Processing (NLP), fairness evaluation is often associated with the assessment of bias and reduction of associated harm. In this regard, the evaluation is usually carried out by using a benchmark dataset, for a task such as Question Answering, created for the measurement of bias in the model{'}s predictions along various dimensions, including gender identity. In our work, we evaluate gender bias in German Large Language Models (LLMs) using the Bias Benchmark for Question Answering by Parrish et al. (2022) as a reference. Specifically, the templates in the gender identity subset of this English dataset were machine translated into German. The errors in the machine translated templates were then manually reviewed and corrected with the help of a language expert. We find that manual revision of the translation is crucial when creating datasets for gender bias evaluation because of the limitations of machine translation from English to a language such as German with grammatical gender. Our final dataset is comprised of two subsets: Subset-I, which consists of group terms related to gender identity, and Subset-II, where group terms are replaced with proper names. We evaluate several LLMs used for German NLP on this newly created dataset and report the accuracy and bias scores. The results show that all models exhibit bias, both along and against existing social stereotypes."
}
