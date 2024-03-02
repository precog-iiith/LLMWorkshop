Hopefully you have all installed ollama. 

- Follow the following sequence of comands
	- Verify ollama is installed 
		```ollama --help```
	- pull a model 
		```ollama pull phi```
		![alt text](./images/ollama/ollama_pull.png)
	- run the model and interact with the model
		```ollama run phi```
	- serve the model - as APIs
		```ollama serve```
		![alt text](./images/ollama/ollama_serve.png)
	- can you access the APIs using CURL ?
	  	curl http://localhost:11434/api/generate -d '{
  			"model": "phi",
			"prompt":"Why is the sky blue?"
			}'
