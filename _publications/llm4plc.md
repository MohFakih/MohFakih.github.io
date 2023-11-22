---
title: "LLM4PLC: Harnessing Large Language Models for Verifiable Programming of PLCs in Industrial Control Systems"
collection: publications
permalink: /publication/LLM4PLC-2023
excerpt: 'Large Language Models for Programmable Logic Controllers (UNDER REVIEW)'
date: 2023-10-01
venue: 'ICSE'
---

LLM4PLC is an LLM-powered pipeline to automate the design and programming of industrial PLCs in manufacturing plants given only a textual description of the intended operation.A special thanks to the Siemens Research Group for supporting this project. 

As of December 2023, this work is submission at the International Conference on Software Engineering (ICSE).

Abstract
=====
Although Large Language Models (LLMs) have established predominance in automated code generation, they are not devoid of shortcomings. The pertinent issues primarily relate to the absence of execution guarantees for generated code, a lack of explainability, and suboptimal support for essential but niche programming languages. State-of-the-art LLMs such as GPT-4 and LLaMa2 fail to produce valid programs for Industrial Control Systems (ICS) operated by Programmable Logic Controllers (PLCs). We propose LLM4PLC, a user-guided iterative pipeline leveraging user feedback and external verification tools – including grammar checkers, compilers and SMV verifiers – to guide the LLM’s generation. We further enhance the generation potential of LLM by employing Prompt Engineering and model fine-tuning through the creation and usage of LoRAs. We validate this system using a FischerTechnik Manufacturing TestBed (MFTB), illustrating how LLMs can evolve from generating structurally-flawed code to producing verifiably correct programs for industrial applications. We run a complete test suite on GPT-3.5, GPT-4, Code Llama-7B, a fine-tuned Code Llama-7B model, Code Llama-34B, and a fine-tuned Code Llama-34B model. The proposed pipeline improved the generation success rate from 47% to 72%, and the Survey-of-Experts code quality from 2.25/10 to 7.75/10.