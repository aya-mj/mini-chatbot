
## Purpose
- To explore how AI models generate text-based responses.
- To understand neural networks and their role in AI-powered chatbots.
- To experiment with different AI models available on Hugging Face.

## Features
- Allows the integration of various AI models from Hugging Face.
- Customizable system prompts.
- Built with Streamlit for an interactive user interface.

## Model Used
In this project, I used **Llama-2-7B-Chat-GGUF** from Hugging Face, but other models can also be integrated and tested by modifying the configuration.

## Explanation of the Code
- **Streamlit UI:** The chatbot interface is built using Streamlit to make it interactive and user-friendly.
- **Hugging Face Integration:** The chatbot loads AI models from Hugging Face using `hf_hub_download`.
- **Prompt System:** A customizable system prompt allows for fine-tuning the AI assistant’s behavior.
- **Session Management:** The chatbot keeps track of conversation history using Streamlit’s session state.
- **Model Execution:** The chatbot uses LangChain's `LlamaCpp` to process user input and generate responses.

## Future Improvements
- Experimenting with more advanced AI models.
- Enhancing conversation memory.
- Fine-tuning models for better responses.
