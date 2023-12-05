# GPT-0
Generative Pre-trained Transformer (GPT-0)

+ Character-Level Language Model

+ n-Digit Numbers Math Model

```mermaid
flowchart TD
    A[Input Tokens] --> B[Token & Positional Embeddings]
    B --> C[Dropout]
    C --> D{Transformer Blocks}
    D --> E[Final Layer Normalization]
    E --> F[Linear Head for Logits]
    F --> G[Loss Calculation]
    F --> H[Token Generation]
```
