# langchain_MR_with_GCP_Gen_AI

Almost all LLM APIs have limit on tokens of prompt. 
GCP: https://cloud.google.com/vertex-ai/docs/generative-ai/learn/models
OpenAI: https://platform.openai.com/docs/models/gpt-3-5

However,  for some cases, the prompts will exceed the limit of prompt, which is very common. To address this situation, Langchain(https://python.langchain.com/docs/modules/chains/document/map_reduce) provides map reduce to handle it. In this notebook, I will show you how it works on GCP Gen AI. 
