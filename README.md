# ChatTS

Welcome to ChatTS! Here are some tips to get you started:

1. Enter your OpenAI API key in the provided field, you only need to type once because the typed key will be fecthed everytime you hit the submit button. But the cached api key will be cleared after you close this window.
2. Ask your question about the donor's heath condition, demographics, and social history, etc.
3. Select the answer style: "Data Retriever" for simple answer like 'yes', 'no', or a number; "Chart Review" for more detailed answer with the matches found in the donor's document.
4. Click "Submit" to get your answer.
5. Use the "Reset" button to clear the answer table content.
6. Click "Download Answer" to download the answer as a csv file.
7. Click the GitHub icon to visit our repo for ChatTS's usage demo and feel free to report bugs you are encountering in the issue section.

To make sure of the answer quality we use a fixed model type as gpt-4o from OpenAI. If you are seeing errors about your api quota, visit the OpenAI API usage tier documentation for more information about the rate limits.

## Diagram for ChatTS pipeline
![ChatTS Diagram](https://github.com/Harper-Hua/ChatTS/blob/main/%E2%80%8EchatTS.jpeg)

## A demo screenshot for an example question about heart disease
![Demo Screeshot](https://github.com/Harper-Hua/ChatTS/blob/main/demo1.png)
