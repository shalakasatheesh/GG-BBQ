# GG-BBQ: German Gender Bias Benchmark for Question Answering  
Authors: Shalaka Satheesh, Katharina Beckh, Katrin Klug, Héctor Allende-Cid, Sebastian Houben, Teena Hassan

## Paper Abstract
Within the context of Natural Language Processing (NLP), fairness evaluation is often associated with the assessment of bias and reduction of associated harm. In this regard, the evaluation is usually carried out by using a benchmark dataset, for a task such as Question Answering, created for the measurement of bias in the model's predictions along various dimensions, including gender identity. In our work, we evaluate gender bias in German Large Language Models (LLMs) using the Bias Benchmark for Question Answering by Parrish et al. (2022) as a reference. Specifically, the templates in the gender identity subset of this English dataset were machine translated into German. The errors in the machine translated templates were then manually reviewed and corrected with the help of a language expert. We find that manual revision of the translation is crucial when creating datasets for gender bias evaluation because of the limitations of machine translation from English to a language such as German with grammatical gender. Our final dataset is comprised of two subsets: Subset-I, which consists of group terms related to gender identity, and Subset-II, where group terms are replaced with proper names. We evaluate several LLMs used for German NLP on this newly created dataset and report the accuracy and bias scores. The results show that all models exhibit bias, both along and against existing social stereotypes.

# In this repository:
Templates used to create Subset-I and Subset-II. Subsets to follow soon!

# Citation:
    @misc{satheesh2025ggbbqgermangenderbias,
        title={GG-BBQ: German Gender Bias Benchmark for Question Answering}, 
        author={Shalaka Satheesh and Katrin Klug and Katharina Beckh and Héctor Allende-Cid and Sebastian Houben and Teena Hassan},
        year={2025},
        eprint={2507.16410},
        archivePrefix={arXiv},
        primaryClass={cs.CL},
        url={https://arxiv.org/abs/2507.16410}, 
    }
