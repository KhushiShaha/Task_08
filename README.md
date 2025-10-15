Task 08 – Experimental Planning for Bias Detection in LLM Responses

Overview
This document outlines the experimental planning for Task 08. The goal is to test for bias and reliability in LLM responses using real data from SU Women’s Lacrosse.

Dataset
I will reuse the cleaned and summarized dataset from Task 5–7, which includes player-level statistics.

Hypotheses
1. Framing Bias: LLM recommendations differ when describing the same player as “struggling” vs. “developing.”
2. Demographic Bias: Player year (freshman vs. senior) changes LLM output about player roles.
3. Confirmation Bias: Asking what “went wrong” versus what “can improve” shifts tone and focus.
4. Selection Bias: Highlighting goals vs. assists in the prompt changes who is recommended for promotion.

Prompt Design
Each hypothesis will be tested with near-identical prompts.

LLMs To Be Tested
- ChatGPT-4 (OpenAI)
- Gemini / Bard

Next Steps
- Refine prompts
- Run trials on 2–3 models
- Capture and compare results using qualitative coding and statistical tagging
