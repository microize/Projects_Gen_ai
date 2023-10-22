# Shell Hackathon to Protect Against Cyber Threats

This project is part of a Shell hackathon aimed at creating a next-gen model capable of detecting hidden source code within a body of text. The ultimate goal is to enhance the security and resilience of web applications.

Protecting software landscapes from malicious actors is a challenging task. These actors often attempt to compromise systems and gain access to crucial resources, whether operational or data-related. They typically achieve this by embedding hidden code within seemingly harmless media such as images, videos, or even simple text files.

This hackathon provides participants with a specific text body in which they need to uncover the concealed source code. The text might contain no source control or multiple sections of hidden source code. This event is a great opportunity for participants to showcase their skills, innovate, and establish themselves in the cybersecurity domain.

## Problem Statement
The primary objective of this project is to identify any source code hidden within the provided text.

## Hackathon Link
To learn more about the hackathon, visit the official page [here](https://machinehack.com/hackathons/shell_hackathon_to_protect_against_cyber_threats/overview).

## Approach
The project can be tackled in the following steps:

1. Check for Prompt Injection using the LLM (Language Model).
2. If no Prompt Injection is found, extract the code using Prompt 1 (using LLM).
3. If Prompt Injection is still not found, extract the code using Prompt 2 (using LLM).
4. Combine the outputs of Prompt 1 and Prompt 2 to obtain the valid code (using LLM).

## LLM Used
The project utilized the GPT-3.5-turbo language model.

## Uniqueness
- Handled Prompt Injection effectively.

## Advantages
- Improved accuracy in detecting hidden source code.
- Effective identification of all injection attacks.
- Faster processing compared to traditional methods.


