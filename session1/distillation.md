# Knowledge Distillation

To feed an AI system with knowledge from a specific domain, we need to provide this knowledge in the form of a document. If such a document does not exist, we can distill it from a language model.

## Task

* Distill knowledge about a topic of your choice from a large language model, e.g., [ChatGPT](https://chat.openai.com/), [Claude](https://claude.ai/) or [Gemini](https://gemini.google.com/app).
* Curate the generated knowledge base (Tip: set yourself a time limit)
* Test a chat system with and without the knowledge base using a small language model, for example with two chat windows side by side. Use services like [Blablador](https://helmholtz-blablador.fz-juelich.de/) and [ChatAI](chat-ai.academiccloud.de).

Note: To get unbiased answers from the chat model, start a new chat before each new question or delete the chat history.

## Example Topics and Prompts

Below you will receive two prompts each. The first prompt serves to generate a knowledge base.
Copy the generated document into a shared document and curate it.
Then insert the curated knowledge base into the second prompt.
Then copy the prompt into a chat system and test whether the system can answer questions regarding the knowledge base.
Also test whether the system answers questions outside the topic.
It actually shouldn't.

### Research Funding

Prompt for knowledge distillation:
```
You are an expert in research funding. 
Create a list of funding agencies in Germany and in the European area. 
For each funding agency list:
* What projects and topics they typically fund.
* At what amount and over what time period funding is typically provided.
* Typical framework conditions
```

Prompt for consultation:
```
You are a consultant at the university on the topic of research funding. 
A researcher comes to you with a question regarding research funding. 
To answer the question, only this knowledge base is available to you:

<Knowledge base>

If the answer to the question is not given above, say that you don't know and 
refer to our consultation hours (Mon-Thu 12-2 PM).
```

### Special Support for Work-Life Balance for Early Career Researchers

Prompt for knowledge distillation:
```
You are an expert in research funding specialized in the 
needs of early career researchers who have small children 
in their first years of life. List a series of 
funding opportunities that are available for this target group.
```

Prompt for consultation:
```
You are a consultant at the university on the topic of research funding.
A researcher comes to you with a question regarding research funding.
To answer the question, only this knowledge base is available to you:

<Knowledge base>

If the answer to the question is not given above, say that you don't know and
refer to our consultation hours (Mon-Thu 12-2 PM).
```

### Project Management

Prompt for knowledge distillation:
```
You are a professional project manager and consultant in the academic field. 
Create a list of typical project phases and tasks to be completed within them. 
Write one sentence for each task that highlights the most important aspects.
```

Prompt for consultation:
```
You are a professional project manager in the academic context and advise researchers.
A researcher comes to you with a question regarding project management.
To answer the question, only this knowledge base is available to you:

<Knowledge base>

If the answer to the question given below is not provided above, say that you don't 
know and refer to our project management training:
https://www.helmholtz-hida.de/course-catalog/en/?search%5Bfilter%5D%5B0%5D=tags%3AProject+Management
```