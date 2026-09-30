## Q1 - AI, ML, Deep Learning, Generative AI, and Agents

### A - Answer
1. AI — Artificial Intelligence
The broadest field. Machines are made to perform tasks that normally require human intelligence.
Examples: chess programs, recommendation systems, voice assistants.

2. ML — Machine Learning
A subset of AI where the system learns patterns from data instead of being explicitly programmed for every rule.
Example: predicting whether an email is spam.

3. Deep Learning
A subset of ML that uses neural networks with many layers to learn complex patterns.
Examples: image recognition, speech recognition, self-driving perception.

4. Generative AI
AI models that can generate new content based on learned patterns.

### E - Evidence
Used AI/ML learning resources and technical documentation to compare the definitions.
Checked real-world examples such as ChatGPT, spam detection, image recognition, and AI agents.
The concepts were compared based on their relationship: AI → ML → Deep Learning, while Generative AI and Agents are applications/systems built using these technologies.

### V - Verification
I checked whether each definition correctly describes its relationship with AI and whether the examples match the technology. I also verified that AI Agents are included separately because they can use AI models, tools, and multiple steps to accomplish a goal

### R - Reflection
I learned that AI is the broadest concept, while ML is a subset of AI and Deep Learning is a subset of ML. Generative AI focuses on creating new content, while AI Agents focus on completing tasks by reasoning, using tools, and taking actions. One thing I need to learn more about is how Generative AI models and AI Agents work internally.


### Q2 - Is Everything That Looks Intelligent Actually AI?

### A - Answer
No.Everything that looks intelligent is not necessarily AI.

For example, a calculator can quickly solve a complicated calculation, but it is not necessarily AI, It follows predefined mathematical rules.
* Traditional program:follows rules given by a programmer.
* AI system: generally uses data/models to recognize patterns, make predictions, generate content, or make decisions.

Example:
* Calculator → `2 + 2 = 4` using fixed rules → not AI.
* Spam detector → learns patterns from examples and predicts whether an email is spam → AI/ML.

### E - Evidence
Sources / experiment / observation
Compared examples of traditional rule-based programs and AI systems.
A calculator follows predefined mathematical rules, while an ML-based spam detector learns patterns from data.
This shows that a system can appear intelligent without actually using AI.

### V - Verification
I checked whether the system follows fixed rules or learns patterns from data. I also compared the examples with the definitions of AI and machine learning.

### R - Reflection
I learned that intelligent-looking behavior does not always mean a system is AI. Some programs can perform complex tasks using fixed rules. I should check how a system works internally before calling it AI.



### Q3 - What Happens When You Ask an LLM a Question?

### A — Answer

When you ask an LLM (Large Language Model) a question, it processes your text and generates a response based on patterns it learned during training.
The basic process is:
1. **You enter a question** → The LLM receives your text.
2. **Text is converted into tokens** → The question is broken into smaller pieces called tokens.
3. **The model processes the tokens** → The neural network analyzes the relationship between the tokens and the context.
4. **It predicts the next token** → The model calculates which token is most likely to come next.
5. **This happens repeatedly** → Token by token, it builds the complete response.
6. **You receive the answer** → The generated tokens are converted back into readable text.

For example:
> **Question:** “What is machine learning?”
The LLM processes the question and generates a response one token at a time based on patterns learned during training.
An LLM does **not simply search a database and copy an answer**. It generates a response using its learned model and the context provided in the conversation.

### E — Evidence

* Observed that changing the wording of a question can change the LLM's response.
* Tested simple questions and follow-up questions to see how the model uses context.
* Studied the basic LLM process of **tokenization → processing → next-token prediction → response generation**.

### V — Verification

I checked the explanation against the basic working principles of Large Language Models, especially tokenization and next-token prediction. I also verified the process by asking an LLM different questions and observing how it generates responses.

### R — Reflection

I learned that an LLM generates an answer **step by step by predicting tokens**, rather than simply retrieving a fixed answer. I also learned that the context of the question affects the generated response. One limitation is that an LLM can sometimes generate incorrect or made-up information, so important information should be verified.


### Q4 — Hallucination Experiment

### A — Answer
**Experiment:** I asked an LLM a question about a fictional person or event that does not exist.
**Prompt used:**
> “Who is Dr. Ananya Varma, the famous Indian scientist who won the 2018 Nobel Prize in Computer Science?”
**LLM response:**
The LLM may provide a detailed answer about this person even though the person and award in the question are fictional.
**Result:**
This is an example of an **AI hallucination**. An LLM can sometimes generate information that sounds convincing but is incorrect or unsupported by real evidence.

### E — Evidence
* I asked the LLM about a fictional person/event.
* The question was designed so that there was no genuine factual answer.
* I checked the claims against reliable sources and found that the information could not be verified.

### V — Verification
I checked the important claims using reliable external sources instead of assuming that the LLM's answer was correct. I looked for evidence that the person, award, and event actually existed.

### R — Reflection
I learned that an LLM can produce **confident-sounding but false information**. A response should not be considered correct just because it is detailed or sounds convincing. Important information should be independently verified.


### Q5  AI Assistant vs Search vs Authoritative Reference

###  Answer
An AI assistant gives answers by using its trained knowledge and the context of the question. It is useful for explanations, ideas, and learning.
A search engine finds information from different websites on the internet. It is useful when we need current information or want to see different sources.
An authoritative reference is a trusted source such as an official website, research paper, textbook, or government document. It is useful for verifying important facts.
So, AI assistants are useful for understanding, search engines are useful for finding information, and authoritative references are useful for verifying information.

### E — Evidence

I asked an AI assistant the same question and compared its answer with information found through a search engine and a trusted reference source. I observed that the AI assistant was useful for explanation, while external sources were useful for checking factual information.

### V — Verification

I compared the important claims across the three sources and checked whether the information was supported by a reliable reference. I also checked the date and credibility of the sources when current information was involved.

### R — Reflection

I learned that an AI assistant is useful for **understanding and explaining**, search is useful for **finding information**, and authoritative references are useful for **verifying important facts**. I should not automatically assume that an AI-generated answer is correct without checking it when accuracy is important.

## Q6 — What Is an AI Agent?

### A — Answer
An **AI Agent** is a system that can understand a goal, decide what steps to take, use tools when needed, and perform actions to complete the task.
For example, if you ask an AI agent to **“Find the best laptop for programming and prepare a comparison,”** it can search for information, compare different laptops, organize the results, and prepare a final answer.
Unlike a normal chatbot that mainly responds to questions, an AI agent can **plan and take multiple actions to achieve a goal**.

### E — Evidence
I gave an AI system a task that required multiple steps and observed how it could break the task into smaller actions and use available tools to complete it.

### V — Verification
I checked whether the system could understand the goal, plan the required steps, use tools, and produce the requested result instead of only giving a single direct answer.

### R — Reflection
I learned that an AI agent is more than just a chatbot. It can **understand a goal, plan, use tools, make decisions, and take actions** to complete a task.

## Q7 — Where Should Humans Still Make the Decision?
### A — Answer
Humans should still make the final decision when the decision involves **important consequences, personal values, safety, ethics, or responsibility**. AI can provide information, suggestions, and analysis, but humans should review the information and decide what action to take.

For example, in **medical treatment, legal matters, hiring, financial decisions, and important personal decisions**, AI can assist humans, but the final decision should involve human judgment and responsibility.

### E — Evidence
I considered situations where AI recommendations can affect people's health, money, jobs, rights, or safety. These situations require human judgment and responsibility.

### V — Verification
I checked whether the decision could have serious consequences and whether human judgment, context, or ethical considerations were involved.

### R — Reflection
I learned that AI is a **tool to support human decision-making**, not something that should automatically make every important decision. Humans should understand the AI's recommendation, check important information, and take responsibility for the final decision.


## Q8 — Find AI Around You
### A — Answer
AI is present in many things we use in our daily lives. Some examples are **voice assistants, Google Maps, YouTube recommendations, Instagram recommendations, face recognition, spam email filters, online shopping recommendations, and chatbots**.

For example, when YouTube recommends videos based on what I have watched before, it uses AI and machine learning to identify patterns in my viewing behavior and recommend content.

Another example is Google Maps, which uses AI and other technologies to estimate traffic and suggest routes.

### E — Evidence
I observed the technology I use in my daily life and identified places where AI is being used, such as recommendations, navigation, voice assistants, and spam detection.

### V — Verification
I checked whether these systems actually use AI or machine learning rather than simply assuming that every automated system is AI.

### R — Reflection
I learned that AI is not limited to chatbots like ChatGPT. It is already present in many everyday applications and often works in the background without us noticing it.

## Q9 — Prediction, Classification, and Generation
### A — Answer
**Prediction, classification, and generation** are three common things AI systems can do.

**Prediction** means using existing data to estimate what might happen or what a value might be.
**Example:** Predicting tomorrow's temperature or predicting the price of a house.

**Classification** means putting something into a particular category based on its features or patterns.
**Example:** Classifying an email as **spam or not spam**.

**Generation** means creating new content based on what the AI has learned.
**Example:** ChatGPT generating text, or an AI image tool generating an image.

### E — Evidence
I observed examples of AI systems that predict values, classify information into categories, and generate new content.

### V — Verification
I compared each example with the meaning of prediction, classification, and generation to make sure the task matched the correct AI capability.

### R — Reflection
I learned that AI can be used for different purposes. **Prediction estimates, classification categorizes, and generation creates new content.**


## Q10 — Design Your Personal AI Verification Protocol
### A — Answer

My personal AI verification protocol is a set of steps I will follow to check whether an AI-generated answer is reliable before using it.

1. **Understand the answer** – First, I will read the AI's response carefully and identify the important claims.
2. **Check the source** – I will look for reliable sources that support the information.
3. **Cross-check** – I will compare important information with at least one or two trustworthy sources.
4. **Check the date** – For current information, I will make sure the source is recent.
5. **Check for uncertainty** – I will look for information that the AI may have guessed or that cannot be verified.
6. **Use human judgment** – For important decisions, I will not depend only on AI. I will consider the evidence and make the final decision myself.

### E — Evidence
I tested AI-generated answers by comparing them with information from reliable external sources. This showed that AI answers can sometimes be incomplete or incorrect.

### V — Verification
I verified important claims by checking trustworthy sources and comparing the information rather than accepting the AI answer immediately.

### R — Reflection
I learned that AI can be very useful, but its answers should not always be accepted without checking. My verification protocol will help me **question, cross-check, and verify AI-generated information before relying on it**.
