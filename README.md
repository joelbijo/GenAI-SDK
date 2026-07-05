# Introduction to the Google GenAI SDK

A concise cookbook demonstrating core capabilities of the official `google-genai` Python SDK using Gemini 2.5 models in Google Colab.

## Features Covered
- **Core Generation**: Basic text generation, system instructions, and configuration tuning (temperature/top_p).
- **Multimodal Inputs**: Analyzing raw PIL images, online image URLs, and large multi-page PDF files.
- **Advanced Workflows**: Multi-turn chat sessions, streaming responses, and asynchronous API execution (`aio`).
- **Structured Outputs**: Parsing text straight into JSON format using Pydantic models and explicit JSON schemas.
- **Safety & Utilities**: Implementing safety filters, token counting, and tool calling configurations.

## Prerequisites
- A Google Colab notebook environment.
- A free developer API key from [Google AI Studio](https://google.com).

## Quick Setup
1. In Colab, click the **Secrets (Key Icon)** tab in the left sidebar.
2. Add a new secret named `genai-sdk-gemini-api-key` and paste your API key.
3. Toggle **Notebook access** to **ON**.
4. Run the code cells sequentially.

## License
This project is open-source and licensed under the [MIT License](LICENSE).
