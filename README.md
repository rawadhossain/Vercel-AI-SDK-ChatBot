# Vercel Chatbot

A customizable chatbot component for Next.js projects.

## Getting Started

To use the Vercel Chatbot in your project, follow these steps:

1. Install the required dependencies by running:

   ```bash
   npm install
    ```

2. Import the ChatBot component into your Next.js page:
    ```
    import ChatBot from "@components/ChatBot";
    ```

## Customizing the Chatbot
The chatbot's initial prompt is defined in lib/data.ts
```
export const initialMessage = {
  role: "system",
  content: `Your custom initial prompt here.`,
};
```

## API Endpoint
/api/chat: Handles user input and responds with a message