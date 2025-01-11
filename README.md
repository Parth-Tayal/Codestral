
# Codestral (LLM Based Code Generation)

This project is a locally hosted AI-powered code generation tool. It facilitates seamless interaction between users and a powerful code generation model(Mamba-Codestral-7B-v0.1) using an efficient backend architecture. The tool processes user inputs, integrates context, and generates code suggestions or completions.

The architecture involves multiple components working together to provide accurate and fast results, including context-aware processing and optimized AI model inference.


## Features
* User-friendly interface for code generation.
* Context-aware processing for multi-turn interactions.
* High-performance inference using NVIDIA Triton Inference Server.

## System Architecture and Flow

![image_alt](https://github.com/Parth-Tayal/Codestral/blob/main/diagram.svg)

* Frontend: The user interface where prompts are entered and responses are displayed.

* Proxy Server: Handles CORS issues, forwards requests, and optionally manages logging and security.

* OpenAITRTLLLM Server: Combines the current user prompt with stored context, handles preprocessing for the AI model, and processes the output from Triton.

* Triton Inference Server:Runs the AI model for code generation.


## Disclaimer
As this project was developed within a company, the code cannot be shared publicly.

However, I’m happy to assist with any questions or discussions related to the project’s design, functionality, or workflow.

Feel free to reach out! 😊

## Showcase Overview

https://github.com/user-attachments/assets/44c4aac3-8695-456d-9510-43b008dfb797

In the above demo, I demonstrated the following capabilities:

* Code Generation: Providing a solution for a given question.
* Test Case Generation: Automatically creating test cases for any code.
* Code Review: Offering insights and improvements for the generated code.

The questions span across different domains, demonstrating the system's versatility, speed, and efficiency in producing accurate results.

