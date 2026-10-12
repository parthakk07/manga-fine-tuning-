3 consecutive English manga pages in, JSON ou: story text in reading order plus speaker ids that stay the same across the three pag

I used Qwen2-VL-2B-Instruct (4-bit) and unsloth LoRA on a colab T4 vision encoder frozen, LoRA r=8, fp16
80 labelled sequences, split 64/16 by sequence_id (seed 13)
## val (16 sequences)
- text_order_score: 0.029
- balanced_joint_f1: 0.034
