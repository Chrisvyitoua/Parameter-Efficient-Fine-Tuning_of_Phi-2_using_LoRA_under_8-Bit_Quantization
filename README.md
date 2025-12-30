### Parameter-Efficient-Fine-Tuning_of_Phi-2_using_LoRA_under_8-Bit_Quantization

#### Overview

This project demonstrates how to fine-tune a Microsoft's Phi-2 model using Low-Rank Adaptation (LoRA) combined with 8-bit quantization (using bitsandbytes
) for memory-efficient training on consumer-grade GPUs.

#### Project Structure

```
├── Phi2_8_bit_LoRA_.ipynb    # Main notebook with full implementation (check it out)
├── phi2-8bit-finetuned/      # Saved LoRA adapter weights
│   ├── checkpoint-13/
│   ├── checkpoint-26/
│   ├── adapter_config.json
│   ├── adapter_model.safetensors
│   └── tokenizer files ...       
└── README.md
```

#### References

- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314)
- [LLM.int8(): 8-bit Matrix Multiplication for Transformers](https://arxiv.org/abs/2208.07339)
- [Phi-2 Language Model](https://huggingface.co/microsoft/phi-2)

---
