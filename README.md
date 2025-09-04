# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:
1. Select a ~230-word article (e.g., news or technical blog).  
2. Provide identical prompt to each model.  
3. Require a specific format: **3 bullet points + 1 takeaway sentence + 1 caveat**.  
4. Evaluate on:
   - Faithfulness (accuracy, no hallucination)  
   - Coverage (are main points included?)  
   - Clarity & Brevity (readable and concise)  
   - Consistency (does it follow the required structure?)
     
## Prompt
"Summarize the following article into exactly 3 bullet points and 1 takeaway sentence. Do not quote the text. Add one line listing a risk or limitation."

## Output
 **ChatGPT** → Concise, polished, highly faithful; caveat short and clear.  
- **Claude 3.5** → Nuanced, slightly longer phrasing, very faithful; detailed caveat.  
- **Gemini (Bard)** → Clear, sometimes oversimplified; generic caveat.  
- **Cohere Command R+** → Concise, may lose detail; minimal caveat.  
- **Llama 3.1** → Varies by host; faithful but less polished.  

## Result
**Best Overall**: ChatGPT (clean & polished), Claude (nuanced & faithful).  
- **Good but Tradeoffs**: Gemini (clear but shallow), Cohere (concise but compressed).  
- **Variable**: Llama 3.1 (open-source, quality depends on deployment). 
