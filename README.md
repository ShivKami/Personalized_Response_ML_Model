# My Journey in Training a Language Model

This project is based on the excellent [Train Your Language Model](https://www.youtube.com/playlist?list=PLMSb3cZXtIfptKdr56uEdiM5pR6HDMoUX) course created by Imad Saddik. I was interested in understanding how Large Language Models (LLMs) are trained, especially from scratch, and decided to go through the course and apply the steps myself.

Along the way, I made some changes and adjustments based on my understanding and goals. This repository reflects my learning process and progress.

## What’s in this repository?

- `notebooks/`: Step-by-step Jupyter notebooks for training and fine-tuning.
- `Slides.odp`: Original presentation slides from the course.
- `data/`: Example data and templates for training.
- `transformer/`: Custom implementation of Transformer and LoRA modules.
- `minbpe/`: Tokenizer code adapted from [Karpathy's repo](https://github.com/karpathy/minbpe).

## Setup

To get started:

1. Install [Python](https://www.python.org/downloads/).
2. Install dependencies:
```bash
pip install -r requirements.txt
```
 
### Limitations  

The model doesn’t always give correct answers. If I try to discuss many different topics, it struggles. This is likely because both the model and the SFT dataset are small. Training on more data and using a larger model could improve the results. I might explore this in the future.

## Contributions

We welcome contributions! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

