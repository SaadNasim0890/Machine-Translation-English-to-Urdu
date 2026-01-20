# Machine-Translation-English-to-Urdu

## English to Urdu Translation (Q2)
**Location:** `genai_q2.ipynb`

This section focuses on Neural Machine Translation (NMT) using a Sequence-to-Sequence (Seq2Seq) model with **LSTM** (Long Short-Term Memory) units.

- **Architecture:** Encoder-Decoder model with LSTM layers.
- **Task:** Translating English sentences into Urdu.
- **Dataset:** A parallel corpus of English and Urdu sentences (including a dummy dataset generation step for demonstration).
- **Process:**
  1.  **Preprocessing**: Text cleaning, tokenization, and padding.
  2.  **Training**: The model is trained to predict the next token in the Urdu sequence given the English input.
  3.  **Inference**: Uses the encoder to create a "thought vector" and the decoder to generate the translation word-by-word.

---
## Dependencies

To run the notebooks in this project, you will need the following Python libraries:

```bash
pip install tensorflow keras torch torchvision diffusers timm accelerate numpy matplotlib
```

*Note: Notebook uses TensorFlow/Keras*
