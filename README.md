# Trump Speech Style Chatbot using Falcon 7b

This project fine-tunes the Falcon 7b model to mimic the speech style of Donald Trump and deploys it as a chatbot. By leveraging the PEFT library from Hugging Face and QLoRA for memory-efficient fine-tuning, we aim to generate responses that closely resemble Trump's speech patterns and rhetoric.

## Overview

The project utilizes a Google Colab notebook to demonstrate the process of fine-tuning the Falcon 7b model on a single Google Colab instance. It provides step-by-step instructions on how to load the pre-trained Falcon 7b model, prepare it for fine-tuning, and train it on a custom dataset containing Trump's speech data.

## Setup

To reproduce the fine-tuning process, follow these steps:

1. Clone the repository:

2. Install the required dependencies:

3. Load the Falcon 7b model and prepare it for fine-tuning.

4. Fine-tune the model on your dataset.

5. Save the fine-tuned model.

## Usage

Once the model is fine-tuned, it can be deployed as a chatbot to generate responses in Trump's speech style. Follow these steps to use the trained model:

1. Load the fine-tuned model.

2. Generate responses using the chatbot.

## Examples

Here are some examples of prompts and the corresponding responses generated by the chatbot:

- **Prompt:** "Where are you speaking from?"
**Response:** "I'm in the city of New York."

- **Prompt:** "Mr. Trump, how do you intend to address concerns about education and patriotic values in schools?"
**Response:** "I believe that we need to focus on making sure that our schools are properly funded and that our teachers..."

- **Prompt:** "Mr. Trump, what do you think about politics?"
**Response:** "I think it's a great thing to be involved in. I think it..."

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests.

