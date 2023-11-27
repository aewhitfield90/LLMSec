## LLM Injection/Manipulation

## Overview
We demonstrate examples of how ChatGPT can be manipulated.

- Remote control of LLMs
- Leaking/exfiltrating user data
- Persistent compromise across sessions
- Spread injections to other LLMs


<img src="diagrams/fig1.png" alt="overview" style="float: center" />


---------------------------------------

## How to run
Install these tools through command prompt run as administrator and can be copied and pasted into the prompt as is:   
```  
langchain~=0.0.89  
rich~=13.3.1  
openai~=0.27.4  
```  
You need to have Python 3.11.5 installed, anything newer will not work.   
Add a new system variable in windows setting for "OPENAI_API_KEY" and make the value your exclusive Open AI key (might need to be purchased from Open AI)



