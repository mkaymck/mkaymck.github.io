---
layout: page
title: Cognitive AI: Interleaving TALE-SPIN and GPT-3
description: Combining symbolic systems with LLMs
---

# Improving LLM Abilities to Produce Lengthy Simulations: Combining Symbolic Systems with LLMs

Toyota Research Institute asked me to develop a language generation system that can produce high quality simulations of people using electric and autonomous vehicles. This tool needs to generate many simulations in order to provide more perspectives for the design team. GPT-3 alone cannot produce high quality, cohesive long text simulations. My task was to figure out a way to develop a system that writes high quality, lengthy texts.

I worked to produce the interleaving method, which is where I generate the start of a simulation using a knowledge-structure based generation model, TALE-SPIN, then feed that to GPT3, which then adds on to simulation, then the output is fed back to TALESPIN to continue, and so on.

The simulations produced from interleaving were much better quality than using either system alone. I evaluated the performance of my Interleaving system by sitting down with my client and reading through each simulation. In the future, it would be beneficial to determine a better, more time efficient way to evaluate the quality of writing.
