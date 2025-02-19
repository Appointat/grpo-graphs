## Qwen GRPO Graph Extraction RL Finetune

We initially explored GRPO based on the Reasoning model synthetic CoT Graph Extraction data, with LLM involved in the reward function.

```bash
.
├── LICENSE
├── ground_truth_gen # data gen via DeepSeek R1
│   ├── polished_rl_training_data.csv
│   └── r1_distill_reasoning_graph_extraction.ipynb
└── train
    └── Qwen_GRPO_Graph_Extraction.ipynb # training process
```



### Credits

- DeepSeek-Math and DeepSeek R1's work and DeepSeek R1 Model
  - https://arxiv.org/html/2501.12948
  - https://arxiv.org/html/2402.03300
- Qwen's Great [Base model](https://huggingface.co/Qwen/Qwen2.5-3B)
- [Will's](https://x.com/willccbb), [this](https://colab.research.google.com/drive/1bfhs1FMLW3FGa8ydvkOZyBNxLYOu0Hev?usp=sharing)(cannot find the author), and Unsloth's [Daniel Han Chen](https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Qwen2.5_(3B)-GRPO.ipynb#scrollTo=SDKIhhvN6lAF) work