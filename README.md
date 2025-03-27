# Large-Language-Models-for-Ingredient-Substitution-

This repository contains the noteboo files and datasets for our paper on Large Language Models for Ingredient Substitution in Food Recipes using Supervised Fine-tuning and Direct Preference Optimization. As food recipes from diverse cultures spread online, ingredient substitution plays a crucial role in adapting recipes based on availability, cost, dietary restrictions, and personal preferences. However, identifying suitable substitutes that preserve the intended flavor profile is a complex challenge.

Research Highlights
  - We explore the use of LLMs for ingredient substitution, a relatively under-explored area in NLP.
  - We conduct zero-shot and few-shot experiments to determine the best publicly available LLM for the task.
  - Mistral7B-Base emerges as the most effective model.
  - We fine-tune the model using Supervised Fine-Tuning (SFT) and Parameter Efficient Fine-Tuning (PEFT), identifying QLoRA as the best PEFT technique.
  - We further enhance performance using two-stage fine-tuning, multi-task learning, and Direct Preference Optimization (DPO).
  - Our best model (SFT + DPO) achieves a Hit@1 score of 22.04, surpassing the strong GISMo baseline.
