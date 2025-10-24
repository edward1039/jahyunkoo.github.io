

*Posted on October 22, 2025*

---

### [Jahyun Koo]

## Introduction
[Recently, large **Vision-Language Models (VLMs)** have shown imporessive abilities to understand both images and text,
However, these models often suffer from **inefficient prompting** - they may contain rich knowledge internally,
but struggle to express it effectively through a single query.

The paper *"PIVOT: Iterative VIsual Prompting Elicits Actionable Knowledge for VLMs"* proposes a new approach
called **PIVOT**, which aims to elicit more accurate and interpretable knowledge from VLMs through *iterative prompting*.


]

## What is PIVOT?
[**PIVOT (Iterative Visual Prompting)** is based on a simple but powerful idea:
This means the model doesn't just answer once;
it **revises its responses across multiple iterations**, gradually moving closer to the correct answer. ]

## Key Findings
[From the experiments in the paper, several key insights emerged:
**Zero-shot prompting** achieved the **bes accuracy**, showing that VLMs already possess strong internal knowledge.
**Few-shot** and **direct prompting** settings had higher *token efficiency* but slightly lower accuracy.
**Increasing the number of iterations** consistently led to answers that were **closer to the ground truth**.
**Parallel prompting** (running multiple iterative threads) further improved correctness and stability.
The study also introduced a **semantic in-view / out-of-view prompting** method,
allowing the model to distinguish between what is visually present and what must be inferred.]

## Why It Matters
[PIVOT demonstrates that effective use of VLMs is not just about model size or training data,
but about **how we communicate with the model**.
By iteratively prompting, we can extract deeper, more actionable knowledge - essentially letting the model "think" through the question rather than guess once.

This approach highlights a new perspective in prompt engineering:

However, there's a trade-off:
more iterations mean higher **computational cost** and slower inference.
Balancing efficiency and accuracy remains an open challenge.]

## Personal Thoughts
[I found this paper fascinating because it redefines what it means to "prompt" a model.
Instead of trying to craft a perfect one-shot prompt,ur understanding over time,  
just like PIVOT encourages models to do.
PIVOT show that **allowing the model to iterate**- to explore and refine - can yield richer reasoning.

It also made me realize how close VLMs are to human-like thought:
we don't always knoew the answer instantly either- we refine our understanding over time,
just like PIVOT encourages models to do.]

## Conclusion
[Overall, *PIVOT* presents a novel and practical way to unlock hidden reasoning capabilities in Vision-Language Models.
Iterative visual prompting helps bridge the gap between **raw perception** and **true understanding**,
offering a step toward more interpretable and controllable AI systems.]


