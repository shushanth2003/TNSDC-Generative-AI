# Transformers Chatbot: Leveraging OpenAI Embeddings for Efficient Question Answering and Conversational Retrieval

## Import Statements: 
### Import necessary libraries and modules for text processing, embeddings, vector stores, conversational chains, and widgets for user interaction.

![Screenshot 2024-03-29 084450](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/4df3b61e-3c52-4253-b68a-3db84330b240)
          
## Additional Processes: 
### Define two additional processes (additional_process_1 and additional_process_2) which can be executed by the user.

![Screenshot 2024-03-29 084612](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/c54dab65-7a03-454b-9cc6-3a14fa06f2ea)

## Set OpenAI API Key: 
### Set the OpenAI API key required for generating embeddings.

![Screenshot 2024-03-29 084756](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/ee3b4e10-16b4-45a2-ae21-7548b8895321)

## Load PDF Content: 
### Load a PDF document and split it into pages using PyPDFLoader.

![Screenshot 2024-03-29 085237](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/38ee4c20-b7b4-487b-aa94-5dad2e356d84)
        
## Convert PDF to Text: 
### Convert the PDF document to text using textract, then split the text into chunks.

![Screenshot 2024-03-29 085517](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/0f1d2069-81fc-4897-914b-c03e1c453aff)

## Token Counting: 
### Define a function count_tokens to count the number of tokens in a text.

![Screenshot 2024-03-29 090018](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/2e6b7d5d-36da-4920-a3fd-b0dae9ac20b9)

## Text Splitting: 
### Split the text into chunks using RecursiveCharacterTextSplitter.

![Screenshot 2024-03-29 090149](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/776819db-a935-4fa8-a768-31cf35480062)

## Data Visualization: 
### Visualize the token count distribution using a histogram.

![Screenshot 2024-03-29 090238](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/5393ef69-51fa-4404-b889-0535a1c8b072)

## OpenAI Embeddings: 
### Create an instance of OpenAIEmbeddings using the OpenAI API key.

![Screenshot 2024-03-29 090444](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/e3a26394-adbe-4af6-88da-66de36cf0a34)

## Vector Database Creation: 
### Create a vector database using FAISS from the text chunks and embeddings.

![Screenshot 2024-03-29 090607](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/87b8df1d-2fba-42b6-b5ca-2d1a9f1bd154)

## Conversational Chain Setup: 
### Set up a conversational chain (qa) using ConversationalRetrievalChain from the language model and vector database.

![Screenshot 2024-03-29 090550](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/43290d1d-ecd7-4aa9-add2-6ca9d1cfbbf3)

## User Input Handling: 
### Define a function on_submit to handle user input, executing additional processes or providing answers through the chatbot.

![Screenshot 2024-03-29 091042](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/c1a2cab4-9c66-48fa-b5e7-d9619a9cde89)

## User Interaction: 
### Display an input box for users to interact with the chatbot, allowing them to ask questions or execute additional processes.

![Screenshot 2024-03-29 091132](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/7526dde0-39ac-43e9-aa16-38189c88104e)

![Screenshot 2024-03-29 091219](https://github.com/shushanth2003/TNSDC-Generative-AI/assets/103485945/20f40a0e-60a3-4703-bfc6-e6c7a06327a8)












