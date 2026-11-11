# 99percentTopicsAI

A curated collection of the AI topics people follow and watch the most, featuring deep-dives into high-retention video formats and under-the-hood AI mechanics.

🌐 **Live site:** [https://rifaterdemsahin.github.io/99percentTopicsAI/](https://rifaterdemsahin.github.io/99percentTopicsAI/)  
🎬 **Series Deep Dive:** [How LLMs Read & 16 High-Potential Video Ideas](https://rifaterdemsahin.github.io/99percentTopicsAI/tokenization-series.html)

---

## 🎬 Featured Case Study: "How LLMs Actually Read: Tokenization Explained"

- **Original Video:** [YouTube Shorts - KVKJRdkH-B8](https://www.youtube.com/shorts/KVKJRdkH-B8)
- **Creator:** [Rifat Erdem Sahin](https://www.youtube.com/@RifatErdemSahin)
- **Topic:** Tokenization & Context Window Budgets (Day 1 of Understanding LLMs)
- **Duration:** 47 seconds

### Why It Gets Rewatched (The Retention Formula)
1. **0–3s Hook:** *"LLMs don't read words like humans do."* Shatters common assumptions right away.
2. **Visual Mapping:** Words convert directly into numerical token IDs (e.g., `"cat" → 9246`), grounding abstract math into visual building blocks.
3. **Subword Aha Moment:** Demonstrates Byte-Pair Encoding (BPE) and why rare words break into subwords, answering why AI miscounts or misinterprets.
4. **Actionable Metric:** Connects tokens directly to API budgets and context windows.
5. **Loop / Binge CTA:** *"Subscribe to follow along for Day 2!"*

---

## 🚀 16 High-Potential Complementary Video Ideas

These 16 ideas directly follow and complement the Tokenization video (Days 2–17), engineered for maximum retention, visual clarity, and repeat viewings:

| Day | Topic | Viral Hook | Core Visual | Token Connection |
|---|---|---|---|---|
| **Day 2** | **High-Dimensional Embeddings** | *"Tokens are just numbers. How does AI know King - Man + Woman = Queen?"* | 3D semantic vector space clustering royalty vs food | Maps token IDs into geometric meaning vectors |
| **Day 3** | **The Strawberry Paradox** | *"Ask ChatGPT how many 'r's are in 'strawberry' and it fails. Why?"* | Visualizing `["straw", "berry"]` token split | Direct consequence of BPE subword segmentation |
| **Day 4** | **Self-Attention in 45s** | *"In 'bank of the river', how does AI know 'bank' isn't where money goes?"* | Dynamic laser attention beams with weight heatmaps | Contextualizes raw token embeddings |
| **Day 5** | **The Temperature Slider** | *"Temperature isn't warmth—it's pure probability distortion."* | Probability histogram shifting from greedy to chaotic | Dictates next-token sampling from the vocab |
| **Day 6** | **KV Cache** | *"Why do chatbots slow down on message 50?"* | GPU VRAM filling up with cached Key/Value vectors | Memory cost of storing previous context tokens |
| **Day 7** | **The Token Tax** | *"Why non-English speakers pay up to 4x more for ChatGPT."* | Side-by-side English (2 tokens) vs Hindi/Arabic (12 tokens) | BPE vocabulary bias toward English corpora |
| **Day 8** | **Lost in the Middle** | *"Why a 1M context model forgets passwords hidden in the center."* | U-shaped attention recall curve (Primacy vs Recency) | Attention degradation across long token budgets |
| **Day 9** | **System Prompts** | *"The invisible secret words ChatGPT reads before you say hello."* | Peeling back the UI to show injected hidden tokens | The origin of token index 0 in the context window |
| **Day 10** | **Hallucinations** | *"LLMs don't lie—they don't even know what truth is."* | Predictive token branching tree prioritizing fluency | Auto-regressive next-token generation without grounding |
| **Day 11** | **Tool Calling & Special Tokens** | *"How a text model actually runs Python code in a sandbox."* | Special tokens `<tool_call>` pausing generation | Reserved vocabulary tokens that act as software switches |
| **Day 12** | **Quantization (FP16 to INT4)** | *"How to fit a 70GB model onto an 8GB laptop."* | Downsampling 16-bit smooth gradients to 4-bit integers | Compressing token weight matrices for local hardware |
| **Day 13** | **RAG vs Fine-Tuning** | *"Fine-tuning is med school; RAG is an open-book exam."* | Vector database search injecting facts into the prompt | Dynamic prompt injection into the token context budget |
| **Day 14** | **Reasoning Models (o1 / R1)** | *"Why new reasoning models say 'Thinking for 14 seconds...' first."* | Hidden scratchpad Chain-of-Thought backtracking tokens | Tokens as internal memory before final output generation |
| **Day 15** | **Vision Tokenization** | *"How GPT-4o 'sees' photos without having eyes."* | Slicing images into 16x16 pixel patches as token vectors | Multimodal extension of subword tokenization (ViT) |
| **Day 16** | **Glitch Tokens** | *"The mystery words that break ChatGPT (SolidGoldMagikarp)."* | Unsupervised tokenizer cluster centroids with zero training | Edge cases in Byte-Pair Encoding dictionaries |
| **Day 17** | **Top-P vs Top-K Sampling** | *"The simple filter tricks that stop AI gibberish."* | Probability distribution truncation with dynamic cutoffs | Filtering low-probability candidate tokens |

---

## 🛠️ The 45-Second Short Retention Blueprint

Every video in this series adheres to this 5-stage pacing formula:
- **0:00 – 0:04:** The Paradox Hook (A real counter-intuitive failure or puzzle)
- **0:04 – 0:18:** The Under-the-Hood Visual (Clean 2D/3D visual model without fluff)
- **0:18 – 0:34:** The "Aha!" Mechanism (The exact single reason why it happens)
- **0:34 – 0:42:** The Practical Rule of Thumb (How to prompt or build better)
- **0:42 – 0:47:** The Series Loop Hook (*"In Day X, we explore..."*)

---

## 💻 Local Development

Run local development servers on ports **over 30,000+** to prevent collisions:

```bash
# Start server on port 30090
python3 -m http.server 30090

# Open in Google Chrome
open -a "Google Chrome" http://localhost:30090
open -a "Google Chrome" http://localhost:30090/tokenization-series.html
```
