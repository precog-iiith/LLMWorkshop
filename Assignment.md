#Assignment

I. Querying LLM APIs. 
Like Cohere there are many such LLMs which can be leveraged using their APIs (but would be paid).
Can you figure out another such available API (which you can use freely), and answer the following questions.

**a) Written** - How does your newly found LLM compare against Cohere/OpenAI/Gemini etc.? How can you scientifically answer this question?

**b) Code** - Write a script to extract the text from following URL : https://www.bbc.com/travel/article/20240222-air-canada-chatbot-misinformation-what-travellers-should-know.
Using the extract text and LLMs can you write a script answer the following questions?
- What is the main issue that the article is talking about?
- Rank (descending order) the relatedness of the article with the following domains - a) "Research", b) "News", c) "Policy", d) "
- You have to come up with a python script that will carry out
  - summarisation of a news article,
  - extract key entities being talked about in the article,
  - what is the sentiment about those entities.
  
**c) Code** - Can you write a script to answer question (b) using any open source LLMs that are run locally on your machine (using tools like Ollama etc.).

**d) Code** - Can you wrap all of the above (querying propreitary and open-source LLMs to answer the questions given a user inputs a link to a news article) in a webapp (using streamlit or comparable tool) 

**d) Written** - If you (or your friend/family member) go over the article yourself (themselves) and answer the previous questions (lets call these human responses gold truth/expected output), how wouuld you rate the model output? Show the expected output, along with model prediction, and argue why the model output is incorrect/correct briefly (100 words).

**e) Code** - Can you do a comparative analysis of the propreitary LLMs and open-source LLMs? An example is Latency comparision (time it takes for your script to do the task given propreitary LLM vs open-source LLM). This is only an example, please think more along these lines and come up with ways to compare the two cases. 
