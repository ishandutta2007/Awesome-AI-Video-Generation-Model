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



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[Runway](https://runwayml.com/)** | AI video generation and editing platform with Gen-3 Alpha, Gen-4, and Aleph models. | **Free**: $0 (125 one-time credits). **Standard**: $12/mo (annual) or $15/mo (monthly). **Pro**: $28/mo (annual) or $35/mo. **Unlimited**: $76/mo for relaxed-rate unlimited generations . | **Free**: 125 one-time credits (~25s of Gen-4 Turbo or Gen-3 Alpha Turbo). No monthly refresh . |

| **[Pika](https://pika.art/)** | Creative video platform with Seedance, Wan, and Pika models, plus image and audio generation. | **Free**: $0 (credit packs only). **Starter**: $8/mo (annual) or $10/mo. **Creator**: $28/mo (annual) or $35/mo. **Fancy**: $76+/mo (annual) or $95+/mo . | **Free**: Access to all models, 2 parallel video generations, no watermark. **No monthly credits**—buy one-time packs at 60 credits/$1 . |

| **[Luma Dream Machine](https://lumalabs.ai/)** | Cinematic AI video generation with Ray3 models and Luma Agents. | **Plus**: $30/mo ($300/year) for 10,000 credits. **Pro**: $90/mo ($900/year) for 40,000 credits. **Ultra**: $300/mo ($3,000/year) for 150,000 credits. Legacy Lite/Plus/Unlimited tiers also exist with a free tier . | **Legacy free tier** available (limited). New Agents tiers have **no free option** . |

| **[Kling AI](https://klingai.com/)** | Chinese AI video platform with Kling 3.0/4.0 models, native audio, and multi-shot generation. | **Basic**: $0 (no monthly credits, non-commercial). **Standard**: $6.99/mo first month, then ~$8.8 (660 credits). **Pro**: $25.99/mo first, then ~$32.56 (3,000 credits). **Premier**: $64.99/mo first, then ~$80.96 (8,000 credits) . | **Basic**: Free forever, no monthly credits, 30 element creations, **non-commercial use only** . |

| **[Hailuo AI](https://hailuoai.video/)** | MiniMax's video platform with Hailuo 2.3, Sora 2, and Veo 3.1 access. | **Standard**: $9.90/mo (annual) or $19.90/mo (1,600 credits). **Pro**: $29.90/mo (annual) or $59.90/mo (5,400 credits). **Max**: $79.90/mo (annual) or $149.90/mo (16,000 credits) . | **Free**: One-time trial credits, Hailuo models only. No monthly free credits . |

| **[PixVerse](https://pixverse.ai/)** | AI video generation platform with V6 and C1 models, per-second credit pricing. | Pay-per-use: V6 at **5 credits/s (360p)** to **23 credits/s (1080p with audio)**. 225 credits = $1 reference . | Not detailed in available results. |

| **[Adobe Firefly Video](https://www.adobe.com/products/firefly/plans.html)** | Adobe's generative video model within the Firefly ecosystem. | **Standard**: HK$78/mo (2,000 credits). **Pro**: HK$158/mo (4,000 credits). **Pro Plus**: HK$393/mo (10,000 credits). **Premium**: HK$1,550/mo (50,000 credits + unlimited video model) . | **Free plan** with limited daily generations. Paid plans include unlimited standard image/vector generation . |

| **[Sora (OpenAI)](https://openai.com/sora)** | OpenAI's video generation model with native audio and up to 1080p/20s output (Pro). | **Sora 2 Pro**: From **$0.30/second** via fal.ai, OpenAI, or Replicate. 720p ~$0.30/s, 1080p ~$0.50/s . | Not detailed in available results. |

| **[Kaiber](https://kaiber.ai/)** | AI video generation for musicians and creators with Canvas and Beat Sync. | **Starter**: $8/mo (annual) or $10/mo (500 credits). **Creator**: $23/mo (annual) or $29/mo (1,500 credits). **Pro**: $79/mo (annual) or $99/mo (5,000 credits) . | **5-Day Trial**: $5 for full access with 500 credits (converts to Creator Monthly after 5 days) . |



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
