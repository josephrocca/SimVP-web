[SimVP video prediction](https://github.com/chengtan9907/SimVPv2) using [ONNX's Wasm runtime](https://github.com/microsoft/onnxruntime/tree/main/js/web). You can use the notebook linked below to train your own video prediction model that runs in real-time in the browser. SimVP is really impressive given how fast it runs - see the results that compare to other methods [in the paper](https://arxiv.org/abs/2211.12509).

## Demos:

Note that these examples are probably under-trained. They're just proof-of-concepts to get the whole pipeline (from training to browser inference) working properly.

 * Various models (color): https://josephrocca.github.io/SimVP-web/demo/simple.html
 * Same as above, but infinite/recursive generation: https://josephrocca.github.io/SimVP-web/demo/simple-infinite.html
 * Moving MNIST (greyscale): https://josephrocca.github.io/SimVP-web/demo/mmnist.html

## Training and Conversion:

* Moving MNIST: https://colab.research.google.com/gist/josephrocca/80c4a9814621d228dfb3d262a26a0806
* Train using your own custom video dataset: https://colab.research.google.com/gist/josephrocca/7be01186b14e07b5d54e80c245a35570

## Pre-trained & Converted Models:

* https://huggingface.co/rocca/simvp-web

## Diffusion Experiments:

* https://colab.research.google.com/gist/josephrocca/eccbb3e5ff92b8326d7e2627827b6323/simvp2-diffusion.ipynb
* https://josephrocca.github.io/SimVP-web/demo/diffusion.html

---


https://user-images.githubusercontent.com/1167575/205601342-e10d328b-3b6a-45f3-927b-4f77140559a8.mp4

