```
+----------------------------------------------+
|  PIYUSH GARG  //  AI systems . retrieval     |
|  distributed training  //  Delhi, India      |
+----------------------------------------------+
```

```console
piyush@delhi:~$ whoami
piyush garg, 1st-year B.Tech in AI/ML

piyush@delhi:~$ cat focus.txt
LLM reliability
retrieval that cites its sources
distributed training that survives dead GPUs

piyush@delhi:~$ cat now.txt
ekido     trains small models on spare GPUs, pays only for verified work
vyana     live health app (web + android), I own backend + security
veris-2b  ~2B model that reads a traceback and writes the fix (dataset + eval done)
```

```console
piyush@delhi:~$ ls projects/
```

- **[ekido/](https://github.com/ekido-ai)**: spare-GPU training network, 8 repos, [live testnet](https://ekido.duckdns.org). Started as GPUChain, Top 8 at InfraShift.
- **[vyana/](https://vyanahealth.app)**: health app in English, Hindi, Hinglish. AI must cite sources or stay quiet. [code](https://github.com/piyushgargog/vyana)
- **[DocuLens/](https://github.com/piyushgargog/DocuLens)**: citation-grounded RAG over PDFs, Word, scans. [live](https://doculens.duckdns.org)
- **[agentic-dermaguard/](https://github.com/piyushgargog/agentic-dermaguard)**: six-agent skin lesion triage. 1st Runner Up, JAI Agentic Hackathon.
- **[free-gpu-llm-lab/](https://github.com/piyushgargog/free-gpu-llm-lab)**: quantization + speculative decoding on free T4s.
- **[veris-2b/](https://github.com/piyushgargog/veris-2b)**: code-repair model.
- **[piyushos/](https://piyushos-three.vercel.app)**: my portfolio, as a desktop OS in the browser.

```console
piyush@delhi:~$ ./receipts.sh
ekido        kill GPU mid-run      -> noticed 0.6s, resumed 65s later, lost 8/400 steps
ekido        junk from replacement -> refused, paid 0  (24.8% vs 89.2%)
dermaguard   macro AUC             -> 0.9782
doculens     Hit@1                 -> 0.51 -> 0.62
gpu-lab      speculative decoding  -> +30.7% tok/s on ~30B GGUF, 2x T4

piyush@delhi:~$ tail failures.log
[warn] bm25 beat hybrid retrieval on keyword-heavy questions
[warn] hnsw lost recall on random data, exact search stays default
[warn] flashattention: 0% decode speedup on T4
[err ] fp16 -> NaN logits on gemma 3 4b
# negative results are results
```

```console
piyush@delhi:~$ git log --oneline --open-source
```

- [useautumn/typescript#91](https://github.com/useautumn/typescript/pull/91): worked example for the Autumn billing SDK (AI credits, rollovers, mid-cycle plan change). Open.
- Vyana's Liquid Glass design system picked for XERJ's Corpus Hub (MIT).

```console
piyush@delhi:~$ echo $STACK
python go rust typescript fastapi nextjs supabase pytorch llama.cpp docker aws

piyush@delhi:~$ cat contact.txt
```

[piyushgargdev.xyz](https://piyushgargdev.xyz) · [linkedin](https://linkedin.com/in/piyushgargog) · hi@piyushgargdev.xyz

```console
piyush@delhi:~$ echo "open to AI/ML + software internships"
open to AI/ML + software internships
piyush@delhi:~$ _
```
