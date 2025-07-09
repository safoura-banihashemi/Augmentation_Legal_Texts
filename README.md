# Legal Text Augmentation
This project aims to enhance the dataset of the Court of Justice of the European Union (CJEU) on fiscal state aid, focusing on improving low-frequency classes for classification tasks. We apply two augmentation strategies:  

1. **Combination of WordNet and GloVe embedding**
2. **Agent-Based Methods using Large Language Models (LLMs)** 

You can access the full project description and methodology [here](https://github.com/safoura-banihashemi/Augmentation_Legal_Texts/blob/main/Augmentation_legal_text.pdf).

## Dataset

We use the **Demosthenes corpus**, which consists of 2,535 English language legal text segments extracted from CJEU decisions on fiscal state aid. All texts are professionally annotated for multi-label legal classification.

@inproceedings{grundler2022detecting,
  title={Detecting Arguments in CJEU Decisions on Fiscal State Aid},
  author={Grundler, Giulia and Santin, Piera and Galassi, Andrea and Galli, Federico and Godano, Francesco and Lagioia, Francesca and Palmieri, Elena and Ruggeri, Federico and Sartor, Giovanni and Torroni, Paolo},
  booktitle={Proceedings of the 9th Workshop on Argument Mining},
  pages={143--157},
  year={2022},
  url={https://aclanthology.org/2022.argmining-1.14/}
}
