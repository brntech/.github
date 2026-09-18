# Broadnet Technologies

**Enterprise AI that actually works. Built and run on our own infrastructure.**

We build AI products for businesses in Arabic and English and run them on infrastructure we own and models we prove ourselves:
Smart Waiter for restaurants, Jordan Promotions for grocery, DialerBee for outbound calling, and an OpenAI-compatible Inference API
with Arabic speech recognition that leads its leaderboard among API-licensed models. Zero data retention, verified hourly.

We publish what we measure, under our own name, with a DOI on every paper.

## Research

- **Self-drafting with Uno on a mixture of experts** (Gemma 4 26B A4B, 2026): the first Uno adapter for a mixture-of-experts model,
  the cost law that places self-drafting against separate drafters, and a losslessness instrument for a model whose plain output
  does not reproduce itself across sessions. [10.5281/zenodo.22820511](https://doi.org/10.5281/zenodo.22820511) ·
  adapter [Broadnet/gemma-4-26B-A4B-uno-pilot-adapter](https://huggingface.co/Broadnet/gemma-4-26B-A4B-uno-pilot-adapter)
- **Uno in vLLM: An Independent Implementation and Empirical Serving Study** (Qwen3-8B, 2026): Uno's acceleration reproduced in vLLM
  within 3% of the reference at one, eight and 32 streams. [10.5281/zenodo.22652609](https://doi.org/10.5281/zenodo.22652609)
- **The Safety Map: What Does and Doesn't Transfer in LLM Sensitive-Data Handling** (39 models from 14 labs, 2026).
  [10.5281/zenodo.19688431](https://doi.org/10.5281/zenodo.19688431)
- **How to Evaluate an LLM for Sensitive Data Safety Before Deploying It** (2026).
  [10.5281/zenodo.19574048](https://doi.org/10.5281/zenodo.19574048)

All papers: [broadnet.ai/research](https://www.broadnet.ai/research).

## Code

- [vllm-uno](https://github.com/brntech/vllm-uno) — Uno speculative decoding for vLLM: no separate draft model, validated on Ampere,
  Hopper and Blackwell. Release v0.3.0 with container image and validation record. Upstream:
  [vllm-project/vllm#55947](https://github.com/vllm-project/vllm/pull/55947).

## Products and companies

- [broadnet.ai](https://www.broadnet.ai) — enterprise AI: assistants, agents, voice and vision, and the
  [Inference API](https://inference.broadnet.ai) ([models and pricing](https://www.broadnet.ai/inference)).
- [dialerbee.com](https://dialerbee.com) — DialerBee, the AI outbound dialer with transcript-based answering-machine detection in 11
  languages; per-agent pricing, no per-minute fees.
- [broadnet.me](https://www.broadnet.me) — Broadnet's telecom and omnichannel messaging: bulk SMS, A2P messaging, HLR lookup and SMS
  firewall for global business.

Contact: info@broadnet.ai
