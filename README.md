## NanoGPT Implementation

This repository provides an implementation of the NanoGPT model for language modeling, following Andrej Karpathy's guide from his YouTube tutorial.

### Overview

NanoGPT is a minimal GPT-like language model that can predict the next token in a sequence of text indefinitely. This implementation is based on the reference text it was trained on, aiming to mimic the style and content of the input data.

### Prerequisites

- Python 3.6+
- PyTorch 1.7+

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nanogpt.git
   ```
2. Install dependencies:
   ```bash
   pip install torch
   ```

### Usage

Run the `nanogpt.py` script to train the model and generate text

files `input.txt` and `names.txt` are given for example. First is Sheakespeare's works and second is human names
 
```bash
python nanogpt.py 
```

### Contents

- `nanogpt.py`: The main script that contains the model definition, training, and text generation logic.

