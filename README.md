# Bharat-40B LLM Proposal

This repository contains a concise India-first design and deployment plan for a 40B parameter model comparable to Gemma 4, with a focus on coding, agentic work, Indic languages, and local worldview alignment.

## What is included

- A static website proposal in `index.html` describing data collection, model training, cleaning, evaluation, and alignment strategy.
- A `netlify.toml` configuration file for simple static deployment.

## Deployment

This repository is ready for deployment as a static site. Use the Netlify CLI or Netlify dashboard to publish `index.html`.

## Key Model Design Decisions

- Prioritize strong Indic-language coverage while maintaining broad English/science/code skills.
- Use targeted RLHF on Indian preferences and agentic assistant tasks.
- Build a tokenizer size with support for Indic scripts and code tokens.

## Notes

The model plan emphasizes quality over length: a strategic dataset mix, focused cleaning, and evaluation that includes both global and India-specific benchmarks.
