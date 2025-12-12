## Pruning LLMs with Reward Model Gradients

Final project for MIT 6.7960 — Joshua Bello, Diego Coello, Jabes Gallardo

Reward-aligned pruning for LLaMA models using gradients from preference-trained reward models.

We evaluate whether pruning with reward-model gradients will selectively preserve the behavioral traits emphasized by that reward model. For example, pruning with a 
safety-aligned reward model (HH-RLHF) should preferentially retain truthfulness and harmlessness, while pruning with UltraFeedback or Arena reward signals should 
better preserve broad instruction-following or conversational quality.

[Blog Post](https://joshuabello2550.github.io/reward-gradient-pruning/)
