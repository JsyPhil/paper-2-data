# Paper 2 Data - An example of how to extract information from legal contracts using Artificial Intelligence

This repository contains the code, data and associated files used in the Medium article ["Paper 2 Data - An example of how to extract information from legal contracts using Artificial Intelligence"](https://medium.com/p/476fedd55592/).

All code, libraries and software used in the example are open source and free to use under their respective licenses. These include, but not limited to: [Transformers](https://huggingface.co) (inc BERT, T5, DeBERTa and RoBERTa), [spaCy](https://spacy.io) and [Doccano](https://github.com/doccano/doccano).

Note that some notebooks require Transformer models be downloaded and available on the local machine.

Notebooks will require various libraries and models to be downloaded.

Code which either trains or fine-tunes certain models will require an up-to-date Nvidia GPU and an installation of CUDA.

Notebook no.5 '5 F5-P2D-NER-CUAD-v1-Inference' uses a fine-tuned model. This can be recreated using notebook no.4 '4 F3-P2D-NER-CUAD-v1-Fine-Tune-Transformer'. Unfortunately given the size of these models, they can not be made available on this GitHub repository.

The PDF contracts used in the demonstration are primarily taken from the [Contract Understanding Atticus Dataset (CUAD)](https://www.atticusprojectai.org) with attribution accordingly.

The presentation utilises information from various sources of associated research. Attribution can be found accordingly in the presentation.

The authors of this repo make all original code, document annotations and data available under the GNU General Public License v3.0.
