# Hey, I'm Piyush 👋

I build AI systems and then try to break them, because the interesting part is whether they still work afterwards.

Second-year AI/ML student at USAR, GGSIPU, Delhi. Most of my time goes into **LLM reliability, retrieval, and making GPUs not die at a bad moment**.

## What I'm building right now

- 🏃 **[Ekido](https://github.com/ekido-ai)**: a network that trains small AI models on spare GPUs and pays only for work that checks out. I kill a GPU mid-training on purpose and the job moves to another one. Started as GPUChain at InfraShift (Top 8), now 8 repos and a [live testnet](https://ekido.duckdns.org).
- 🏥 **[Vyana](https://vyanahealth.app)**: a live health app (web + Android) in English, Hindi and Hinglish. I lead the backend and security. The AI has to show its sources or stay quiet.
- 🧪 **[Veris-2B](https://github.com/piyushgargog/veris-2b)**: a ~2B model that reads a Python traceback and writes the fix. Dataset and eval are built; training comes next.

## Receipts

| What | Result |
|---|---|
| Ekido: killed a GPU mid-run | noticed in **0.6 s**, resumed elsewhere **65 s** later, lost 8 of 400 steps |
| Ekido: a replacement GPU returned junk | refused, paid **0** (24.8% vs 89.2% accuracy) |
| [DermaGuard](https://github.com/piyushgargog/agentic-dermaguard): six agents on skin lesions | macro AUC **0.9782**, 1st Runner Up at JAI Agentic Hackathon |
| [DocuLens](https://github.com/piyushgargog/DocuLens): smarter chunking | Hit@1 **0.51 → 0.62** on my own benchmark |
| [GPU LLM Lab](https://github.com/piyushgargog/free-gpu-llm-lab): speculative decoding on 2× T4 | **+30.7%** tokens/sec on a ~30B model |

## Things that didn't work (I wrote them down anyway)

- BM25 beat my fancy hybrid retrieval on keyword-heavy questions.
- HNSW lost recall on random data, so DocuLens still uses exact search.
- FlashAttention gave me zero decode speedup on T4s.
- FP16 gave NaN logits on Gemma 3 4B.

Negative results are results.

## Also

- 🧩 Open PR on the Autumn billing SDK: [AI credits with rollovers](https://github.com/useautumn/typescript/pull/91)
- 🪟 My portfolio is a [desktop OS that runs in your browser](https://piyushos-three.vercel.app)
- 🛠️ Python · Go · Rust · TypeScript · FastAPI · Next.js · Supabase · PyTorch · llama.cpp · Docker · AWS

## Say hi

[piyushgargdev.xyz](https://piyushgargdev.xyz) · [LinkedIn](https://linkedin.com/in/piyushgargog) · hi@piyushgargdev.xyz

Looking for AI/ML and software internships. If you have a hard problem about retrieval, reliability, or distributed training, I'd like to hear it.
