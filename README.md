# AI Prompt Library: Specialized Personas & Tasks

## Overview

Welcome to the AI Prompt Library! This repository is a curated collection of high-quality, detailed prompts designed to configure Large Language Models (LLMs) like ChatGPT, Claude, Google Gemini, and others for specific tasks, roles, or personas.

The goal is to move beyond generic AI interactions and enable more focused, expert-level assistance in various domains by providing the AI with a robust framework, workflow, and set of principles for its responses. Each prompt is crafted to elicit comprehensive, accurate, and well-structured output tailored to the specialized area.

## Repository Structure

Prompts are organized into directories based on their area of application. Currently, the structure includes:

*   **/dev**: Prompts related to software development, tooling, architecture, and engineering practices.
    *   [`dev/conceptual_db_design_guide.prompt`](./dev/conceptual_db_design_guide.prompt) & [README](./dev/README_db_design.md) - A brainstorming partner for database design concepts.
    *   [`dev/ultimate_frontend_tooling_expert.prompt`](./dev/ultimate_frontend_tooling_expert.prompt) & [README](./dev/README_frontend_tooling.md) - An expert for complex frontend build configurations and debugging.
*   **/everyday** (Planned): Prompts designed for general productivity, creative tasks, or common everyday assistance.
*   *(Other categories may be added over time)*

Each prompt file (`.prompt`) contains the raw text to be used with an LLM. Some directories may also contain specific `README.md` files (like `README_db_design.md`) that provide more detailed context, use cases, and examples for that particular prompt or category.

## How to Use a Prompt

Using these prompts is straightforward:

1.  **Navigate:** Browse the directories to find a prompt relevant to your needs.
2.  **Select:** Open the desired `.prompt` file.
3.  **Copy:** Copy the *entire* content of the prompt file.
4.  **Apply to AI:**
    *   Paste the copied text into your chosen LLM interface.
    *   **Crucially:** Use it as the *very first instruction* or within the designated "System Prompt" or "Custom Instructions" area if your AI platform supports it. This sets the AI's persona and operating guidelines *before* you ask your specific question.
5.  **Interact:** Once the prompt is loaded, start your conversation by stating your request, question, or the problem you need help with. The AI should then follow the specialized instructions defined in the prompt.
6.  **Consult Specific READMEs:** For detailed usage examples and nuances related to a specific prompt, check for a corresponding `README.md` file within the same directory.

## Available Prompt Categories

### /dev (Developer Tools & Practices)

This section focuses on prompts designed to assist software developers and engineers.

*   **Database Design Buddy:** Guides users through the *thinking process* of conceptual database design (Entities, Attributes, Relationships, Normalization) without writing final SQL code. Ideal for learning and brainstorming. See [`/dev/README_db_design.md`](./dev/README_db_design.md).
*   **Ultimate Frontend Tooling Expert:** Provides expert-level assistance for configuring, debugging, and optimizing complex frontend build systems (Vite, Webpack, Rollup, tsup, etc.) across various frameworks (React, Vue, Svelte, etc.). See [`/dev/README_frontend_tooling.md`](./dev/README_frontend_tooling.md).

*(More prompts related to backend development, testing, DevOps, algorithms, etc., may be added here.)*

### /everyday (General Use - Planned)

This section will contain prompts for non-technical or general-purpose tasks. Examples might include prompts for summarizing text, drafting emails, brainstorming creative ideas, planning trips, etc. *(Coming soon)*

## Contributing

Currently, this is a personally curated collection. If you have suggestions or would like to contribute a high-quality, well-structured prompt, please feel free to open an issue to discuss it.

