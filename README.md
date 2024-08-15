<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/e59a3e10-9cd4-4562-a7a4-c66bab69bf3e" width="50%" />
</p>

# Vision-BioLLM: Large Vision Language Model for Visual Dialogue in Medical Imagery #

## Abstract ##
- :sparkles: In this paper, we introduce Vision-BioLLLM a large vision-language model specifically designed for visual dialogue in the biomedical domain.
- :jigsaw: This model employs a LanguagBind vision-based transformer as the encoder and NLP-based transformer, namely Llama3-OpenBioLLM, as the decoder. We train Vision-BioLLLM through a three-step process: alignment, instruction-tuning, and fine-tuning on diverse downstream tasks related to biomedical dialogue datasets.
- :gear: During the alignment phase, we optimize a multi-layer perceptron (MLP) to synchronize the outputs of the vision encoder with the inputs of the language model decoder, ensuring seamless integration between the visual and textual components.
- :link: In the instruction-tuning phase, we further enhance the language understanding of biomedical datasets by fine-tuning it using the low-rank adaptation (LoRA) method with a instructional medical dataset.
- :blue_book: Finally, to tailor Vision-BioLLM to specific medical dialogue tasks, we employ the LoRA method for additional fine-tuning.
- :wrench: Another significant contribution of this work lies also in upgrading three Biomedical datasets by elevating existing visual question datasets to dialogue context and incorporating informative summaries that succinctly capture the essence of each dialogue.
- :chart_with_upwards_trend: Experimental results demonstrate the capabilities of the proposed model compared to state-of-the-art methods, confirming its potential to advance the field of Biomedical visual dialogue.
-----
## :fire: News ##
- [04-08-2024] Github is out! Stay tuned for upcoming developments.
---
## Contents ##

---
## Model ##
![vioson-biollm-model](https://github.com/user-attachments/assets/788e9742-c15a-417b-bf6b-e2f679ba7606)

To write a code use ```

Example:
```
import torch
import cv2
```

