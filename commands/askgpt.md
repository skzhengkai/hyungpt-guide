# /askgpt

The `/askgpt` command allows you to ask a question to GPT-4, OpenAI's latest AI model.

## Usage
```
/askgpt [question]
```

Simply provide your question after the `/askgpt` command. 

For example:
```
/askgpt What is the capital of France?
```

## Options

- `--new`: Add this flag to reset the conversation history and start a new chat session with GPT-4.

For example:
```
/askgpt What is the capital of France? [new:true]
```

## Access

- Non-premium users must vote on top.gg to gain temporary access to this command.

- Premium subscribers have unlimited access.

- The command is also unlocked if the server has premium status.

## How it Works

- hyunGPT leverages various GPT-4 APIs and models to provide responses.

- Conversation history is tracked to provide continuity.

- The response is provided in an embedded message for easy viewing.

- The bot can also read the response aloud in voice channels.

- Errors and failures are handled gracefully to return the best possible response.

## Response Guidelines

- GPT-4 is an advanced AI, but it may occasionally generate incorrect or nonsensical responses. Please provide feedback to help it improve.

- Avoid dangerous or unethical questions. GPT-4 will refuse to answer these.

- Remember GPT-4 does not actually have subjective experiences or opinions.

## Examples
```
User: /askgpt What is the capital of France?

hyunGPT: The capital of France is Paris.

User: /askgpt Who was the first president of the United States? [new:true]

hyunGPT: The first president of the United States was George Washington.
```
