# Local AI Sentiment Analysis Workflow using n8n and Ollama

This project is a local AI-powered sentiment analysis workflow built using n8n and Ollama.

The workflow receives customer opinions or reviews through a form submission trigger, then sends the text to a locally running Large Language Model (LLM) using Ollama. The AI model analyzes the opinion and classifies the sentiment into one of three categories:

* Positive
* Negative
* Neutral

The system is designed to work fully locally without relying on paid cloud AI APIs. This makes the workflow lightweight, privacy-friendly, and cost-effective.

## Technologies Used

* n8n → workflow automation platform
* Ollama → local LLM runtime.
* Local LLM models (such as Llama 3, Phi-3, or Mistral)
* Form Submission Trigger
* Basic LLM Chain

## Workflow Process

1. A user submits a review or opinion using a form.
2. The form submission triggers the n8n workflow.
3. The review text is sent to the Ollama chat model.
4. The AI analyzes the sentiment.
5. The model returns only one result:

   * Positive
   * Negative
   * Neutral
6. The result can then be stored, displayed, or sent to other services such as Google Sheets, Telegram, or databases.

## Features

* Fully local AI processing
* No OpenAI API required
* Fast and lightweight
* Simple workflow architecture
* Structured sentiment classification
* Easy to customize and expand

## Example

Input:
"The product quality is amazing and I really like the design."

Output:
Positive

Input:
"The application is slow and crashes frequently."

Output:
Negative

## Future Improvements

* Multi-language sentiment analysis
* Dashboard visualization
* Telegram integration
* Google Sheets storage
* Advanced analytics
* Real-time review monitoring

This project is intended as a beginner-friendly AI automation workflow that demonstrates how local LLMs can be integrated with n8n for practical business use cases.
