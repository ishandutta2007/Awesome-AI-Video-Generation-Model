# Awesome-AI-Video-Generation-Model

## Top AI Video Generation Model Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Text-to-Video Generation, Cinematic AI Models & Self-Hosted Video Diffusion*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Video Generation Models**. These tools transform text prompts, images, or video inputs into short cinematic clips—ranging from closed commercial models with polished outputs to open-weight diffusion models that run on consumer GPUs and can be fine-tuned with LoRA.



**Examples** include Runway Gen-3, OpenAI Sora, Pika, Luma Dream Machine, Kling AI, Hailuo AI, PixVerse, Stable Video Diffusion, LTX-Video, and Mochi 1 (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active open-weight video model for self-hosting, avoiding per-second SaaS fees, and controlling the generation pipeline. The open-source landscape is anchored by **LTX-Video** (faster-than-real-time generation on consumer GPUs, Apache 2.0), **Mochi 1** (the largest open video model at 10B parameters, Apache 2.0), and **CogVideoX** (Zhipu/Tsinghua's high-resolution model with T2V and I2V, Apache 2.0), with **Stable Video Diffusion** providing the foundational image-to-video model and **Wan2.2** offering MoE-based generation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI video generation market is estimated between **$850M and $5.5B+ in 2026**, expanding rapidly toward **$20B–$70B+ by the early 2030s** at an estimated CAGR exceeding 25–35%. The sector exhibits **moderate fragmentation with rapid consolidation pressure**; while frontier foundation model providers and established software incumbents (OpenAI, Adobe, Kuaishou/Kling) command the largest enterprise pipelines and distribution moats, specialized prosumer startups (Runway, MiniMax, PixVerse, Luma, Pika) sustain significant market share through creative tooling workflows, agile community ecosystems, and rapid model iterations.

## SaaS/Hosted Platforms

| Product | Company Size / Valuation / Revenue | Starting Pricing | Free Tier Limit | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Sora (OpenAI)](https://openai.com/sora)** | Valuation: **~$850B+** (ARR: ~$13B–$50B run rate) | **$20/mo** (ChatGPT Plus tier) or API from **$0.30/s** (Sora 2 Pro) | **Free tier**: Limited trial access on select accounts with watermarks and strict duration/resolution caps. Full Sora access begins on Plus ($20/mo). | OpenAI's video generation model with native audio, high prompt fidelity, and up to 1080p/20s output. |
| **[Adobe Firefly Video](https://www.adobe.com/products/firefly/plans.html)** | Market Cap: **~$105B** (Full-year revenue: ~$23.8B) | **$9.99/mo** (Firefly Standard, 2,000 monthly credits) | **Free forever plan**: Daily generative credit allowance resetting every 24 hours (for test-generation of images/short video clips with platform caps). | Adobe's generative video model deeply integrated into Premiere Pro and the Firefly creative ecosystem. |
| **[Kling AI](https://klingai.com/)** | Valuation: **$18B** (Parent: Kuaishou ~$25B+ market cap) | **$6.99/mo** first month, then **$8.80/mo** (Standard tier, 660 credits) | **Basic plan (Free forever)**: 66 free daily credits (resets daily, non-commercial use only, standard queue, up to 720p watermarked). | Chinese AI video platform with Kling 3.0/4.0 models, multi-shot generation, and native cinematic camera controls. |
| **[Hailuo AI](https://hailuoai.video/)** | Market Cap: **~$8.2B–$11.4B** (MiniMax public on HKEX: 00100) | **$9.90/mo** (annual) or **$19.90/mo** (Standard tier, 1,600 credits) | **Free forever plan**: ~200 welcome credits + daily bonus credits (expires after 3 days; max 768p, 6s duration, watermarked, 1 concurrent job). | MiniMax's video platform featuring Hailuo 2.3 and MiniMax H3 models with high motion dynamics. |
| **[Runway](https://runwayml.com/)** | Valuation: **$5.3B** (Raised $315M Series E in 2026) | **$12/mo** (billed annually) or **$15/mo** (Standard tier, 625 credits/mo) | **Free plan**: 125 one-time credits (~25s of Gen-4/Gen-3 Turbo video, watermarked, non-refreshing). | Leading AI video creation platform featuring Gen-3 Alpha, Gen-4, and Aleph models with video-to-video editing. |
| **[PixVerse](https://pixverse.ai/)** | Valuation: **$2.0B+** (Raised $550M+ total, Series C extension) | **$8/mo** (billed annually) or **$10/mo** (Standard tier, 1,200 credits/mo) | **Basic plan (Free forever)**: 60 signup credits + 30 daily credits (resets daily, 540p resolution cap, watermarked, personal use). | AI video platform with V6 and C1 models, fast rendering pipelines, and camera motion presets. |
| **[Luma Dream Machine](https://lumalabs.ai/)** | Valuation: **~$500M** (Series B funded by a16z, NVIDIA) | **$25/mo** (annual) or **$30/mo** (Plus tier, 10,000 credits/mo) | **Free forever tier**: 30 free video generations/month (~1 generation/day allowance, standard priority queue, 720p, watermarked). | Cinematic AI video generation platform powered by Ray 2/Ray 3 models and Luma camera agents. |
| **[Pika](https://pika.art/)** | Valuation: **~$470M–$700M** (Series B led by Spark Capital) | **$8/mo** (billed annually) or **$10/mo** (Starter tier, 700 credits/mo) | **Free forever plan**: Access to models with 2 parallel generation queues, no monthly recurring credit top-up (pay-per-pack or initial trial credits, personal use only). | Creative video generation platform with Seedance, Wan, and Pika models, sound effects, and Pikaffects. |
| **[Kaiber](https://kaiber.ai/)** | Valuation: **~$10M–$20M** (Seed funded by EQT, ARR ~$2.6M) | **$8/mo** (annual) or **$10/mo** (Starter tier, 500 credits/mo) | **5-Day Free/Trial plan**: $5 promotional trial converts to Creator, or free account with limited initial test credits for canvas mode. | Stylized AI video generation studio focused on animators, music videos, beat synchronization, and visual artists. |

## Open-Source GitHub Projects



- **[LTX-Video](https://github.com/Lightricks/LTX-Video)**  

  **The faster-than-real-time open-source model.** **Apache 2.0 licensed**. Generates **5 seconds of video in ~2 seconds**—faster than watching the output . **Architecture**: integrates Video-VAE and denoising transformer into a single system, achieving **192x compression** without quality loss . **Models**: LTXV 2B (balanced fidelity/speed), 2B Distilled (3x faster), 13B, and 13B Distilled . **Strengths**: runs on consumer-grade GPUs; supports multiscale rendering and multi-keyframe workflows; **realtime iteration**—change prompts and see results in seconds . Best for creators wanting rapid iteration and developers building real-time video tools without datacenter-class hardware.



- **[Mochi 1](https://github.com/genmoai/mochi)**  

  **The largest open video model.** **10B parameters (AsymmDiT)**, Apache 2.0 licensed . **Strengths**: **strong prompt adherence**—"you write what you want and it comes out almost exactly" . **Output**: 480p base, 5.4 seconds max. **Ecosystem**: ComfyUI support, LoRA fine-tuning, Gradio UI, and a simple Python API . **Trade-offs**: shorter duration than LTX; high resolution requires more VRAM; best at short scenes with strong physics rather than long complex narratives . Best for developers wanting the highest-fidelity open model for short, prompt-critical clips and those interested in LoRA customization.



- **[CogVideoX](https://github.com/zai-org/CogVideo)**  

  **The high-resolution Chinese open-source model.** Zhipu AI + Tsinghua University, **Apache 2.0 licensed** . **Output**: **768×1360** high resolution, up to 10 seconds, 226-token long prompts. **Modes**: T2V (Text-to-Video) and I2V (Image-to-Video with dedicated weights) . **Strengths**: welcomes detailed, long prompts—"the more detailed the better"—contrasting with LTX's concise style . Best for developers wanting high-resolution open-source generation with strong Chinese language support and detailed prompt handling.



- **[Stable Video Diffusion (SVD)](https://github.com/Stability-AI/generative-models)**  

  **The foundational image-to-video model.** Part of Stability AI's generative-models repository (~27.3k stars) . **Output**: 14 frames at 576×1024 from a single image . **Strengths**: the reference implementation for image-to-video synthesis; supports LoRA fine-tuning and camera control . **Trade-offs**: older than LTX/Mochi/CogVideoX; shorter duration and lower resolution. Best for researchers and developers wanting a well-documented, widely-forked foundation for image-to-video experiments.



- **[Wan2.2](https://github.com/Wan-Video/Wan2.2)**  

  **The MoE-based video generation model.** Alibaba's open model with **Mixture-of-Experts** architecture for efficient high-definition generation . **Models**: Wan2.2-I2V-A14B (image-to-video, 480p/720p) and Wan2.2-TI2V-5B (text-image-to-video, 720p) . **Requirements**: A14B needs ~80GB VRAM for single-GPU; TI2V-5B runs on **24GB VRAM** (RTX 4090) with offloading . Best for developers with high-end GPUs wanting MoE efficiency and strong image-to-video performance.



### Additional Strong Open-Source Options



- **HunyuanVideo 1.5** — Tencent's 8.3B parameter DiT model with sparse attention, unified T2I/T2V/I2V, and strong Chinese language support. arXiv technical report available .

- **AnimateDiff** — Animates personalized text-to-image models without tuning. Best for adding motion to existing Stable Diffusion workflows.

- **SkyReels V2** — Diffusion-forcing for infinite-length film generation. Best for long-form video experiments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **SaaS pricing is credit-based and opaque**: Runway credits burn fast (50–100 credits per 10-second clip; Pro plan yields ~22–45 clips/month) ; Kling's first-month discounts revert to higher renewal rates ; Pika's free tier has no monthly credits—only one-time packs .

- **Open-source models have hardware requirements**: Mochi 1 and CogVideoX need substantial VRAM for high resolutions; Wan2.2-A14B requires ~80GB VRAM without offloading . LTX-Video and Wan2.2-TI2V-5B are the most consumer-friendly options.

- **Commercial use varies**: Kling's free Basic tier is **non-commercial only** ; Pika's Free and Starter tiers lack commercial licenses—Creator and above include them . Verify licensing before using outputs commercially.

- **Open-source ≠ free to run**: all models require GPU infrastructure, and large models may need cloud instances that cost as much as SaaS subscriptions.



---



**Made for video creators, AI researchers, and developers building generative video pipelines.**  

Let's make AI video generation more open, accessible, and self-hostable.
