# Inner Sight 
InnerSight is a sentiment analysis LLM Integrated - Web App for Therapeutic Conversations. <br /> <br />
It Integrates ```LLMware library``` to perform Retrieval Augmented Generation (RAG) based document analysis on collection of medical, mental illness & therapeutical books
providing sentiment analysis and a QA Chatbot for Conversations with the LLM used


<br /> <br />


## Models Information
* ```llmrails/ember-v1```:  Embeddings Model for generating text embeddings.  [Link](https://huggingface.co/llmrails/ember-v1)
* ```TheBloke/zephyr-7B-beta-GGUF```:  Used as the Generative LLM Model 

## Tech Stack

* ```LLMWARE```: AI Toolkit -  Document, Text Chunking, Embeddings & Generative Model
* ```FastAPI```: Backend Web Server for Serving LLM
* ```React.js + Axios```:  Client Side Web App


 <br />


## Getting Started

1. First Clone the repo
```
  git clone https://github.com/ShubhamTiwary914/innersightLLM.git
  cd innersightLLM
```

 <br />

2. Install Dependencies

> Server Side - Create Virtual env(conda) and install fastapi dependencies
```
  cd api
  conda create --name innersight
  conda activate
  pip install -r requirements.txt
  uvicorn server:app --port 8000
```

> Client Side - React App
```
   cd app
   npm install
   npm run dev
```

<br />

3. After successfull, your app should be running at: http://localhost:3100/


<br /> <br />


## Screenshots


