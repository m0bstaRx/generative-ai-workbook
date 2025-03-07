# Notes


### Usecases of LLMs

- Search
- Classification
- Clustering
- Data, Text and Code generation
- Summarization
- Rewriting
- Extractions
- Proof reading
- Querying Data


### Why langchain?

<center>
<img src="../resources/img/whylangchain.png" style="height:300px; display: block; margin-right: auto; margin-left: auto;">
</center>


### HuggingFace Spaces

Free cloud based containers for LLMs and ML web apps.


```md
> make secrets in settings for OPENAI_API_KEY
> make app.py file 
> make .env-sample file
> make requirements.txt file
```

<center>
<img src="../resources/img/huggingfacespace1.png" style="height:300px; display: block; margin-right: auto; margin-left: auto;">
</center>


### Text Emeddings

- Embeddings are a way to represent words in a lower dimensional space, Allowing similar words to have similar representaiton. This facilitates semantic simarity search.

<center>
<img src="../resources/img/embeddings1.png" style=""; display: block; margin-right: auto; margin-left: auto;">
</center>


### Streamlit

```bash
> cd to project folder
streamlit run app.py
```

**Charts for streamlit**
- https://echarts.apache.org/examples/en/index.html
- https://github.com/andfanilo/streamlit-echarts-demo/tree/master/demo_echarts


### Lanchain Modules

- Models: 
- Chains:
- Agents Module:
    - [https://python.langchain.com/docs/modules/agents/](https://python.langchain.com/docs/modules/agents/)
    - Action Agent: recieves input from user, decides which tool and tool input (if any). It then calls the tool and records the output (known as the observation), It decides whichs next steps to use given the context of the history of tools, tool inputs, observations. Repeat the previous two steps until it can respond to the user. 
    - Plan and Execute Agents: Recieves input from user, plans a full sequence of steps and then executes them. Executing the steps in order, passing the output each step as input into the next.