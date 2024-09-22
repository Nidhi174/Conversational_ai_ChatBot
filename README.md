# Conversational_ai_ChatBot
# GPT-Driven Conversational AI Bot for Customer Support

## Overview

This project is a **GPT-powered conversational AI bot** designed to streamline customer support services. Deployed via **Telegram** and utilizing **Qdrant** for vector storage, the bot automates real-time responses to customer queries, reducing the need for human intervention. Its architecture is scalable and flexible, supporting multiple clients with isolated data and customizable configurations. The bot also integrates **web scraping** functionalities to fetch FAQs from client-specified URLs, enabling dynamic and up-to-date responses.

## Key Features

- **GPT-Driven Responses**: Uses OpenAI's GPT model to understand and respond to user queries in a conversational manner.
- **Telegram Integration**: The bot operates through Telegram, providing a convenient messaging interface for end-users.
- **Qdrant Vector Storage**: Leverages Qdrant for storing and retrieving embeddings, ensuring efficient query matching and fast responses.
- **Multi-Client Support**: The architecture supports multiple clients, ensuring data isolation and allowing custom configurations per client.
- **Web Scraping**: Automatically scrapes FAQs from client-provided URLs to update the knowledge base.
- **Real-Time Response**: Offers immediate assistance to customer queries, enhancing the user experience and reducing response times.

## Architecture

1. **Client Requests**: Users interact with the bot through Telegram.
2. **Query Processing**: The bot processes user queries and generates embeddings using a GPT model.
3. **Qdrant Storage**: Embeddings are stored in and retrieved from the Qdrant vector database for similarity-based query matching.
4. **Response Generation**: Based on matched embeddings, the bot generates a response.
5. **Web Scraping Module**: Periodically scrapes client-provided URLs for FAQs and updates the knowledge base.
6. **Client Customization**: Each client can configure their data isolation, settings, and FAQs, ensuring personalized customer support experiences.

## Prerequisites

Before running the project, ensure you have the following:

- **Python 3.8+**
- **OpenAI GPT API Key**
- **Telegram Bot Token**
- **Qdrant API Key**
- **BeautifulSoup4** for web scraping
