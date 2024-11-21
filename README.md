Inspired by paper https://arxiv.org/abs/2306.05685

Using Qwen-1.5-72B (through vLLM) as LLM judge to evaluate models on indic language hindi/english/hinglish


To evaluate your own model add it add https://github.com/aayush-kumar-code/IndicLMJudge/blob/main/scripts/indic_eval/common_vars.sh 
and simply `bash scripts/lmjudge.sh`

 #### LLM Judge Language: hi 
 | Model | Language | Score | No# Questions |
 | --- | --- | --- | --- |
 | Qwen/Qwen1.5-72B-Chat-AWQ | hi | 8.3722 | 562 |
 | Qwen/Qwen1.5-14B-Chat | hi | 8.2561 | 561 |
 | google/gemma-7b-it | hi | 7.8930 | 561 |
 | Qwen/Qwen1.5-7B-Chat | hi | 7.8518 | 562 |
 | teknium/OpenHermes-2.5-Mistral-7B | hi | 7.2240 | 562 |
 | ai4bharat/Airavata | hi | 6.9355 | 550 |
 | 01-ai/Yi-34B-Chat | hi | 6.5692 | 562 |
 | sarvamai/OpenHathi-7B-Hi-v0.1-Base | hi | 4.2417 | 606 |
 | Qwen/Qwen1.5-4B-Chat | hi | 4.0970 | 562 |
 
 
 #### LLM Judge Language: en 
 | Model | Language | Score | No# Questions |
 | --- | --- | --- | --- |
 | Qwen/Qwen1.5-14B-Chat | en | 9.1956 | 362 |
 | Qwen/Qwen1.5-72B-Chat-AWQ | en | 9.1577 | 362 |
 | Qwen/Qwen1.5-7B-Chat | en | 9.1503 | 362 |
 | 01-ai/Yi-34B-Chat | en | 9.1373 | 362 |
 | mistralai/Mixtral-8x7B-Instruct-v0.1 | en | 9.1340 | 362 |
 | teknium/OpenHermes-2.5-Mistral-7B | en | 9.0006 | 362 |
 | google/gemma-7b-it | en | 8.7945 | 362 |
 | Qwen/Qwen1.5-4B-Chat | en | 8.7224 | 362 |
 | ai4bharat/Airavata | en | 7.3923 | 362 |
 | sarvamai/OpenHathi-7B-Hi-v0.1-Base | en | 5.9009 | 318 |



