# Integrate-Azure-OpenAI

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Introduction

Welcome to the **Hiking Enthusiast Chatbot**! This chatbot, named **Forest**, is designed to help users discover hiking trails in their area. If no specific area is provided, Forest defaults to recommending hikes near **Rainier National Park**. The bot offers three suggestions for nearby hikes that vary in length and shares interesting facts about the local nature related to those hikes.

## Features

- **Interactive Chat**: Engage with the chatbot to get personalized hiking recommendations.
- **Local Insights**: Receive interesting facts about the nature surrounding the recommended hikes.
- **User -Friendly Interface**: Simple command-line interface for easy interaction.
- **Customizable**: Easily modify the bot's behavior and responses.

## Technologies Used

- **Python**: The primary programming language used to develop the chatbot.
- **Azure OpenAI**: Utilized for natural language processing and generating responses.
- **dotenv**: For managing environment variables.

## Set up environment variables: 

Create a `.env` file in the root directory of the project and add the following variables:

```
AZURE_OAI_ENDPOINT=
AZURE_OAI_KEY=
AZURE_OAI_DEPLOYMENT=
```

## OUTPUT

![Screenshot 2024-11-17 163246](https://github.com/user-attachments/assets/d3d0d1e9-6e4b-42d8-a8b6-3a5ccd416b8c)

![Screenshot 2024-11-17 163349](https://github.com/user-attachments/assets/0bdfec86-30f1-47c5-90d4-7248bc0f1847)

##  Configuration
You can customize the chatbot's behavior by modifying the system_message in the `Azure-OpenAi.py` file. This message dictates how the bot responds to user queries. Feel free to adjust it to better suit your needs!
