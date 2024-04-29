whats up guys, this is a hackathon project that i worked on, GENCSV

pros:
 - simple and easy to understand code
 - minimal libraries required
 - modular model approach (ability to choose different models from Ollama for different use cases)
 - unique approach to GenAI

cons:
 - lack of conversational skills (can't ask follow up questions)
 - lack of UI
 - embedding model could use some improvement (future update?)




you are only required to run and install a few packages.

<h1>
  STEP 1 installing OLLAMA
</h1>

<h3>
 UNIX 
</h3>


Install Ollama by running the following command

`curl https://ollama.ai/install.sh | sh`


<h3>
 WINDOWS 
</h3>

https://ollama.com/download/windows


<h3>
  MAC
</h3>

https://ollama.com/download/mac


<h1>
  STEP 2 running the Ollama server
</h1>

Run the Ollama server by running the following command

`ollama serve`


<h1>
  STEP 3 choose the model you are going to use
</h1>

Head down to the link below to search for the model you would like to use 

https://ollama.com/library

In the example I am using the Command-r model which is specialized for RAG tasks and is also capable of conversing in 10 different languages

https://ollama.com/library/command-r
https://huggingface.co/CohereForAI/c4ai-command-r-v01

<h1>
  STEP 4 install the libraries
</h1>

`pip install langchain chromadb pandasai`

<h1>
  STEP 5 run the code
</h1>
Open up the juypter notebook provided and run the cells after changing the CSV path and the model used


<h1>
  Analytics Generation
</h1>

One feature that makes this project stand out would be the analytics generation feature

![image](https://github.com/EXXPRT/gencsv/assets/113296716/672485b5-52c4-47be-9817-7f9567b7dbd2)



