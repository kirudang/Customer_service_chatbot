# Customer Service Chatbot with In-Context Learning

![ezgif com-video-to-gif](https://github.com/kirudang/Customer_service_chatbot/assets/91911269/6b289c12-6a4d-4bb4-abeb-655c5dc22361)

Link to my medium post: https://medium.com/@kirudang/building-a-customer-service-chatbot-with-in-context-learning-using-llama-index-and-language-model-61423b25d858

In today's digital age, the demand for efficient and personalized customer service is ever-increasing. The integration of chatbots has become essential for businesses to provide instant and automated support. This project focuses on building a Customer Service Chatbot with In-Context Learning, powered by Llama Index and Language Model API, to deliver context-aware and effective customer support.

## Table of Contents
- [Introduction](#Introduction)
- [Project Structure](#Project-Structure)
- [Why Llama Index?](#Why-Llama-Index)
- [Building Your Chatbot](#Building-Your-Chatbot)
  - [Steps](#Steps)
    - [Data Collection](#Data-Collection)
    - [Data Preparation](#Data-Preparation)
    - [Llama Index Integration](#Llama-Index-Integration)
    - [Language Model API](#Language-Model-API)
    - [Gradio UI Interface](#Gradio-UI-Interface)
- [Note](#Note)
- [References](#References)

## Introduction

Customer service is essential for any brand, but providing 24/7 human support can be costly and time-consuming. That’s where chatbots come in — they can provide instant, automated assistance to customers while freeing up human agents for more complex issues.

In this project, we'll walk through building a customer service chatbot trained on real Twitter conversations between brands and customers. The key to creating an effective chatbot is having relevant training data. So we’ll use a Kaggle dataset of Twitter customer support exchanges involving popular brands like Apple, Verizon, Airbnb, Uber, Spotify, and so on.

**Dataset:** [Customer Support on Twitter](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter/data)

## Project Structure

The project is structured into several key components:

1. **Why Llama Index?**: Explains the significance of using Llama Index for token limit handling.

2. **Building Your Chatbot**: Outlines the steps involved in creating an in-context learning chatbot. This section is further divided into subsections.

3. **Note**: Provides essential notes for users to keep in mind when working on the project.

4. **References**: Lists reference materials and inspirations for the project.

## Why Llama Index?

In this section, we delve into why using Llama Index for token limit handling is crucial for our project. It covers the challenges of using large language models (LLM) without Llama Index and the benefits that Llama Index offers.
![Chatbot Architecture with Llama and LLM](https://github.com/kirudang/Customer_service_chatbot/assets/91911269/c4d74584-bfd5-46fc-94c2-0cfe7a7e1d78)


## Building Your Chatbot

### Steps

In this section, we explain the key steps to create an in-context learning chatbot:

1. **Data Collection**: We'll utilize a publicly available dataset from Kaggle called "Customer Support on Twitter." This dataset contains customer interactions with various brands on Twitter, providing us with a rich source of customer service conversations.

2. **Data Preparation**: The first step in building our chatbot is to extract conversations related to a specific brand or topic of interest from the Twitter dataset. This will be the foundation of our chatbot's knowledge.

3. **Llama Index Integration**: We'll use Llama Index to efficiently index and organize the conversation data. This is crucial for managing the token limits and enabling in-context learning.

4. **Language Model API**: We will leverage language models like ChatGPT or Hugging Face to train our chatbot using the indexed data. These models are capable of understanding and generating human-like text, making them ideal for conversational AI applications.

5. **Gradio UI Interface**: To make our chatbot user-friendly, we’ll integrate it with Gradio, a library for creating custom user interfaces. Gradio will enable us to interact with our chatbot through a visually appealing and intuitive interface.

### Note

This section provides a note regarding the rapidly evolving nature of LLM and NLP, along with suggestions to consult documentation for debugging and code adjustments.

## References

This section acknowledges the sources of inspiration, reference materials, and sources that contributed to the project's development.

## GitHub Repository

For more detailed project code, you can visit our [GitHub repository](https://github.com/kirudang/Customer_service_chatbot).

## License

This project is open-source and is available under the [MIT License](LICENSE). Please refer to the license file for additional details.


