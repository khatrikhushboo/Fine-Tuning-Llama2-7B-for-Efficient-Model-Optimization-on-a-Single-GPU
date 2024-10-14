This repository is intended as a minimal example to load Llama 2 models and run inference, which is based on the offical implementation of [llama](https://github.com/meta-llama/llama) inference from Facebook.
The modifications made are as follows:

* Remove dependencies on the `fairscale` and `fire` packages.
* Remove chat completion feature.
* Reorganize the code structure of the generation feature. Now `Generation` class is the base class of the llama model.
* Remove `logit` related features from `Generation` class.

## Quick Start
Install `torch` and `sentencepiece` packages.

Change `model_path` and `tokenizer_path` in `inference.py`

```
python inference.py
```
