This project demonstrates how to build high-performance AI pipelines that are lightweight, cost-effective, and environmentally responsible.

**Features**

* **Parameter-Efficient Fine-Tuning (PEFT)** for lightweight model adaptation
* Supports techniques like **LoRA**, **Prefix Tuning**, **Adapters**, etc.
* **CodeCarbon integration** to track energy consumption & CO₂ emissions
* Clear, modular fine-tuning pipeline
* Evaluation & inference steps
* Reproducible and hardware-agnostic
* Designed for sustainable and responsible AI workflows


**Requirements**

* Python 3.9+
* Hugging Face Transformers
* PEFT
* CodeCarbon
* Accelerate / PyTorch
* notebook / Jupyter environment


**Workflow Overview**

1. **Load a pretrained model**
2. **Wrap it with a PEFT method** (LoRA, adapters, etc.)
3. **Prepare dataset & tokenization**
4. **Track energy usage with CodeCarbon**
5. **Fine-tune efficiently** with reduced trainable parameters
6. **Evaluate performance**
7. **Generate predictions**


 **Sustainability**

Using PEFT reduces:

* GPU memory usage
* Power consumption
* Training emissions
* Compute cost

Combined with **CodeCarbon**, the project quantifies the environmental impact of training and promotes greener AI development.



**Outputs**

* CO₂ emission report (CodeCarbon)
* Energy consumption logs
* Fine-tuning performance metrics
* Model adaptation results

