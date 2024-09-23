# AI Text Summarizer Web Application

Hey! This is my project forked from the Postman AI Text Summarizer Project based Course. [Check it out here](https://academy.postman.com/project-ai-text-summarizer)

## Instructions

To run locally, follow the instructions from the Course as linked above.

If you are mostly familiar, just make the following changes:

### 1. `.env`

The project uses HuggingFace as the AI Provider. [Get your token from HuggingFace](https://huggingface.co/settings/tokens)

Create a file `.env` in the root of the project (same level as index.js) and add a variable named `ACCESS_TOKEN` with value set to the HuggingFace API Token
eg: `ACCESS_TOKEN=your-token-here`

### 2. Running Locally

`npm run start` - to run the Express Server listening it [http://localhost:3000](http://localhost:3000)
`npm run dev` - to run with NodeMon (helpful if you want to re-run the server script on save)

### Useful snippets

1. Text Prompt

```txt
Servers play a vital role in modern digital infrastructure. They are specialized computers designed to store, manage, and process data, applications, and services. Acting as central repositories, servers respond to requests from client devices like computers, smartphones, or other servers over a network, such as the internet.

These robust machines handle a diverse range of tasks. Web servers host websites, serving web pages to users who access them through browsers. Application servers manage and run software applications, facilitating their execution and ensuring smooth performance. Database servers store and organize data, allowing efficient retrieval and manipulation of information for various applications.
```
