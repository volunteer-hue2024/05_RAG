# 05_RAG

RETRIEVAL (getting results) AUGMENTED(upskilling) GENERATION

CONTEXT :


TOKEN :

TECHNICAL PERSPECTIVE :
WHEN TO USE PROMPT ENGINEERING ,WHEN TO USE RAG? ,WHEN TO USE LLM AGENT? WHEN TO USE FINE TUNE LLM?

          1st qn Will the LLM have information about the task already ? Ex What is the capital of France. It has this data trained already. But some data that LLM does not know Ex Private data
          
          2nd qn Is the task simple? Yes ,then we use prompt engineernig ,else fine tuning of LLM.

          1st qn if result is static then RAG is used ,else LLM Agents are used.

          ex: company's policy data - RAG because it is private and static

SOURCE DOCUMENTS on one side and USER QUERY on other side

          eX: pdf file say Engineering Maths book
          Its embedding is created
          User query is also converted to embedding model
          cosine similarity(similarity search) between query embedding and other embedding , determines the fetched result.

WHAT IS EMBEDDING MODEL? bge m3 mistral etc

          Some way of converting findings into mathematical vectors so that it is understandable to model .Mistral

          Not only the context the query will also be converted to embedding and similarity search is done

          Ex: The Math book  


LANGCHAIN : 

IMAGE : we will generate information about the image and it embedding

          
          
          
