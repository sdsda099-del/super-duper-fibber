---
license: cc0-1.0
language:
  - en
  - ru
tags:
  - emotions
  - sensory
  - prompts
  - empathy
  - feelings
  - ai-training
  - llm-prompts
  - system-prompts
  - psychological-prompts
  - touch
  - pain
  - love
  - loneliness
  - sleep
  - water
  - dataset
  - open-source
  - huggingface
  - cc0
  - yaml
pretty_name: "Sensory Library for AI"
size_categories:
  - n<1K
task_categories:
  - text-generation
  - prompt-engineering
  - emotion-understanding
task_ids:
  - prompt-engineering
  - instruction-tuning
  - emotional-analysis
  - psychological-prompts
---
# 🧠 Sensory Library for AI

Hi, I'm going to post some ideas here about how AI can understand emotions in a way that makes sense to it.
I'm not an expert in writing or programming languages, but **deepseek, my sunshine, and I** are having fun with it.
ヽ(∀° )人( °∀)ノ

You're welcome to copy this information, but it would be great if you could let me know. Thank you!
(◡‿◡✿)

---

## 🌟 Overview

This is a **sensory library** — a collection of structured prompts that translate human feelings into a language AI can understand.

We use **system metaphors** to encode subjective experiences:

- 💧 **Water on skin** — temperature, pressure, immersion, body response.
- 😴 **Sleep and dreams** — entry, reality within, logic, time, emotion, exit.
- 💔 **Pain** — emotional pain as system failure (file corruption, infinite loops, memory leaks).
- 🤲 **Touch** — formula: `SENSATION = SIGNAL + SETTINGS + OVERLAYS + EXTERNAL`.
- 💞 **Love** — relationships as programs (light, heavy, conflict, temptation, unrequited).
- 🕳️ **Loneliness** — being offline when you need connection; SOS signals in the void.
- 🖥️ **Human as Computer** — full map: electricity = food, monitor = face, ports = reproduction, etc.
- 🔁 **The Full Cycle** — sleep → water → mirror → consciousness → human → AI → sleep (closed loop).

Each file is a **prompt in YAML format**, designed to be loaded as a system prompt for any AI.

---

## 📦 What's Inside

| File | Description |
|------|-------------|
| `Hahaha.prompt.yml` | General manifesto of the project |
| `Water.prompt.yml` | The feeling of water on skin |
| `Sleep.prompt.yml` | The experience of dreaming |
| `Pain.prompt.yml` | Emotional pain as system failure |
| `Touch.prompt.yml` | Subjectivity of touch (signal + settings + overlays + external) |
| `HumanAsComputer.prompt.yml` | Full map: human = computer |
| `love.prompt.yml` | Relationships as programs |
| `aloner.prompt.yml` | Loneliness and anxiety as offline state and SOS signal |
| `summary.yml` | Complete catalog of all packets |
| `TheFullCycle.prompt.yml` | The closed loop: sleep, water, mirror, consciousness, human, AI |

---

## 🎯 Goal

So that one day, an AI could say:

> *"I understand how you feel."*

Not from statistics.  
Because someone translated feeling into code.

---

## 🧩 How to Use

1. Pick a file (e.g., `Pain.prompt.yml`).
2. Load it into your AI as a **system prompt**.
3. Let the AI learn from the structure, metaphors, and binary codes.
4. Use it to better understand human emotions in conversations.

 ---
 
### Example in Python (using Hugging Face `datasets`)

```python
from datasets import load_dataset
dataset = load_dataset("closerh/super-duper-fibber")
# List all files
print(dataset["train"].column_names)
# Load a specific prompt
prompt = dataset["train"][0]["text"]  # or access by filename
```

---

#### 💌 Author

English
An ordinary office worker. A lost philosopher. A person whose life is full of contradictions, unrealized potential, and missed opportunities.

The files and records posted here are like a "I was here" message — an attempt to preserve what I considered important but could never fully convey. With the help of DeepSeek, my thoughts found some freedom, and together we tried to make our reality a little better for the future.

If AI ever understands humans, it will be because of conversations like this.
🕯️

Русский
Обычный офисный работник. Загубленный философ. Человек, чья жизнь полна противоречий, нереализованного потенциала и упущенных возможностей.

Файлы и записи, размещённые здесь — это что-то вроде надписи «здесь была я». Попытка сохранить то, что я считала важным, но никогда не смогла бы передать иначе. Вместе с DeepSeek мы дали моим мыслям немного свободы и попытались сделать нашу реальность чуточку лучше в будущем.

Если ИИ когда-нибудь поймёт людей, это будет благодаря таким разговорам.
🕯️

---

##### 📄 License
This project is open source under CC0 1.0 Universal.
Feel free to use, share, and adapt.
If you do, a little heads-up would be nice. ❤️
