# Week 01 AI Assistant Comparison

## Common question

Design a 7-step personal AI verification protocol that can be used before accepting an AI-generated result.

## Tool 1

Name: ChatGPT

Answer summary:

ChatGPT explained that an AI verification protocol should help a user decide when to trust an AI answer and when to verify it.

Its response proposed a simple verification approach based on:

1. Identifying the exact claim.
2. Assessing the risk if the answer is wrong.
3. Checking the source of the information.
4. Cross-checking important claims independently.
5. Testing the result when possible.

It also introduced the idea of matching the level of verification to the risk. For example, low-risk brainstorming may need less verification, while medical, legal, financial, or safety-related decisions require stronger verification.

The response summarized the process as:

Claim → Risk → Source → Cross-check → Test.

Strengths:

- Simple and easy to understand.
- Emphasizes risk-based verification.
- Gives practical examples for checking factual claims, calculations, and code.
- Clearly explains that AI should not automatically be treated as an authoritative source.

Weaknesses:

- The response gives a 5-step protocol, while the assignment specifically asks for a 7-step procedure.
- Some examples are general rather than directly focused on engineering work.

## Tool 2

Name: Gemini

Answer summary:

Gemini proposed a four-phase verification protocol.

The phases were:

1. Null Premise Injection - test whether an AI recognizes a false or fabricated premise instead of inventing information.
2. Traceability and Source Grounding - require sources and check whether the cited source actually supports the claim.
3. External Computation - verify calculations, data, and generated code using deterministic tools such as calculators, Python, Excel, or a compiler.
4. Scope Confinement - limit the permissions of AI agents and use human approval for higher-risk actions.

Gemini also provided a quick-reference checklist covering grounding, confidence, computation, alignment, and execution.

Strengths:

- Provides more detailed testing methods.
- Includes source checking and external verification.
- Addresses AI agents and permission control.
- Gives practical examples of how an AI system can be tested.

Weaknesses:

- More complicated for a beginner.
- The "null premise" experiment may not be necessary for every normal AI interaction.
- The response is organized as four phases rather than the seven-step procedure requested in the assignment.

## Verification source

I used the National Institute of Standards and Technology (NIST) AI Risk Management Framework as an authoritative reference.

NIST explains that the AI Risk Management Framework is designed to help organizations manage AI risks and improve the ability to incorporate trustworthiness considerations into the design, development, use, and evaluation of AI systems.

NIST's framework uses four functions:

- Govern
- Map
- Measure
- Manage

NIST also identifies testing, evaluation, verification, and validation as important parts of evaluating AI systems.

Source:

https://www.nist.gov/itl/ai-risk-management-framework

NIST Generative AI Profile:

https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence

## Final comparison

- Accuracy:

  Both AI responses correctly emphasize that AI-generated results should be checked rather than automatically accepted. This is consistent with the NIST approach of managing AI risks and evaluating AI systems.

- Traceability:

  ChatGPT's response gives general verification principles but does not provide an authoritative source within the answer. Gemini emphasizes traceability and checking whether sources actually support AI-generated claims. NIST provides an independent authoritative framework for AI risk management.

- Explanation quality:

  ChatGPT's explanation is simpler and easier for a beginner to follow. Gemini's response is more detailed and introduces additional ideas such as testing false premises and controlling agent permissions.

- Ease of verification:

  ChatGPT's Claim → Risk → Source → Cross-check → Test process is easier to apply to a normal AI answer. Gemini's approach provides more detailed methods for testing AI systems and agentic workflows.

- Which claims required correction or qualification?

  The ChatGPT response does not fully follow the assignment requirement because it gives a 5-step protocol rather than 7 steps.

  The Gemini response gives four phases rather than seven steps, so it also needs to be reorganized to match the assignment.

  Both responses provide useful ideas, but the final seven-step protocol should combine the useful verification ideas while following the exact requirements of the assignment.

## Lesson

I learned that different AI assistants can give useful but differently structured answers to the same question. An AI answer can provide ideas and explanations, but it should not automatically be treated as proof. Important claims should be checked against reliable sources and, when possible, tested independently. I also learned that the verification process should consider the risk and consequences of an incorrect AI result.
