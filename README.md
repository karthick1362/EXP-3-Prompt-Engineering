# EXP-3-PROMPT-ENGINEERING-

**Date:**  01/09/2025
**Reg. No.:** 212223053002

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

### Objective
To evaluate prompting performance across five major AI platforms in 2024—**ChatGPT (OpenAI)**, **Claude (Anthropic)**, **Gemini (Google)**, **Cohere Command R+**, and **Meta Llama 3.1**—based on structured experiments using **Algorithm → Prompt → Output → Result**.

This report focuses on two core use cases:
1. **Summarization**
2. **Technical Q&A**

---

## AI Platforms Evaluated
| Platform | Developer | Model Type | Access Type | Key Strength |
|-----------|------------|-------------|--------------|---------------|
| ChatGPT | OpenAI | GPT-4-turbo | Cloud | Balanced accuracy and fluency |
| Claude 3.5 | Anthropic | Constitutional model | Cloud | Context reasoning and nuanced answers |
| Gemini (formerly Bard) | Google DeepMind | Multimodal Transformer | Cloud | Integrated with Google ecosystem |
| Cohere Command R+ | Cohere | Text generation (Command family) | API | Optimized for retrieval and concise output |
| Llama 3.1 | Meta | Open-source LLM | Local/cloud-hosted | Customizable and fine-tunable |

---

## Use Case 1: Summarization

### Algorithm
1. Select a 230-word article (e.g., news or tech blog post).  
2. Provide the identical summarization prompt to all models.  
3. Require the following output structure:  
   - **Exactly 3 bullet points**  
   - **1 takeaway sentence**  
   - **1 caveat (risk/limitation)**  
4. Evaluate responses on:
   - Faithfulness  
   - Coverage  
   - Clarity & Brevity  
   - Consistency  

### Prompt
Summarize the following article into exactly 3 bullet points and 1 takeaway sentence. Do not quote the text. Add one line listing a risk or limitation.

text

### Representative Outputs
- **ChatGPT:** Concise, polished, and highly faithful; short and clear caveat.  
- **Claude 3.5:** Nuanced, slightly longer phrasing; detailed and context-aware caveat.  
- **Gemini:** Clear and simple, but may oversimplify details; generic caveat.  
- **Cohere Command R+:** Compact and crisp but may miss secondary details; minimal caveat.  
- **Llama 3.1:** Faithful but less polished; variation depends on hosting environment.

### Result
| Platform | Faithfulness | Clarity | Brevity | Consistency | Overall |
|-----------|--------------|----------|----------|--------------|----------|
| ChatGPT | Excellent | Excellent | High | High | ★★★★★ |
| Claude 3.5 | Excellent | Good | Moderate | High | ★★★★☆ |
| Gemini | Good | Good | High | Moderate | ★★★☆☆ |
| Cohere R+ | Fair | High | Excellent | Fair | ★★★☆☆ |
| Llama 3.1 | Good | Fair | Moderate | Variable | ★★★☆☆ |

**Summary:**  
ChatGPT and Claude deliver the most faithful and structured summaries. Gemini and Cohere are competitive but lighter on nuance. Llama 3.1 performs well but inconsistently depending on configuration.

---

## Use Case 2: Technical Q&A

### Algorithm
1. Pose a reasoning-intensive technical question.  
   Example: “Explain the time and space complexity of binary search on a nearly sorted array.”  
2. Specify prompt constraints:  
   - Must state assumptions.  
   - Include minimal **Python code** with inline test.  
   - Keep explanation under 120 words.  
3. Evaluate on:
   - Correctness  
   - Explicit Assumptions  
   - Code Quality  
   - Concision  

### Prompt
Explain the time and space complexity of binary search on a nearly-sorted array. State assumptions. Provide a minimal Python snippet with an inline test. Keep explanation under 120 words.

text

### Representative Outputs
- **ChatGPT:** Correct time complexity \(O(\log n)\), space \(O(1)\); clear assumptions and concise, executable code.  
- **Claude 3.5:** Correct with nuance (e.g., mentions k-disorder); well-commented but verbose code.  
- **Gemini:** Correct, though assumptions implicit; functional but lacks inline test.  
- **Cohere Command R+:** Compact and accurate code; minimal explanation.  
- **Llama 3.1:** Mostly correct, assumptions loosely stated; code readability varies.

### Result
| Platform | Correctness | Code Quality | Explicitness | Concision | Overall |
|-----------|--------------|---------------|---------------|-----------|----------|
| ChatGPT | Excellent | Excellent | High | High | ★★★★★ |
| Claude 3.5 | Excellent | Excellent | Very High | Moderate | ★★★★☆ |
| Gemini | Good | Good | Medium | High | ★★★☆☆ |
| Cohere R+ | Good | High | Low | High | ★★★☆☆ |
| Llama 3.1 | Fair | Fair | Moderate | Moderate | ★★★☆☆ |
