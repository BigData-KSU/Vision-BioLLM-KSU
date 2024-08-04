# BioLVLM-KSU #
**Large Vision Language Model for Visual Dialogue in Medical Imagery**
<img src="https://github.com/BigData-KSU/BioLVLM-KSU/assets/126481523/5985c11e-b388-4fcf-9f4a-d506c2b4810c" width="50%" height="50%" align="center" />
## Abstract ##
- :sparkles: In this project, we introduce VMed-Llama3, a vision-language model specifically designed for visual dialogue in the medical domain.
- :jigsaw: This model employs an encoder-decoder architecture, with a vision-based transformer as the encoder and a cutting-edge NLP-based transformer, Llama3, as the decoder. We train VMed-Llama3 through a three-step process: alignment, instruction-tuning, and fine-tuning on diverse downstream tasks related to medical dialogue datasets.
- :gear: During the alignment phase, we optimize a multi-layer perceptron (MLP) to synchronize the outputs of the vision encoder with the inputs of the language model decoder, ensuring seamless integration between the visual and textual components.
- :link: In the instruction-tuning phase, we further enhance the language understanding of medical datasets by fine-tuning it using the low-rank adaptation (LoRA) method with a instructional medical dataset.
- :blue_book: Finally, to tailor VMed-Llama3 to specific medical dialogue tasks, we employ the LoRA method for additional fine-tuning.
- :wrench: Another significant contribution of this work lies also in upgrading three datasets by elevating existing visual question datasets to dialogue context and incorporating informative summaries that succinctly capture the essence of each dialogue.
- :chart_with_upwards_trend:Experimental results demonstrate the capabilities of VMed-Llama3 compared to state-of-the-art methods, confirming its  potential to advance the field of medical visual dialogue.
-----
## Model ##

To write a code use ```

Example:
```
import torch
import cv2
```

