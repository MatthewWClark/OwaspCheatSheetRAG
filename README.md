# OwaspCheatSheetRAG
This is a local RAG created using owasp cheat sheet and tinyLlama

Directions:
1. download tiny llama by clicking here https://huggingface.co/jartine/TinyLlama-1.1B-Chat-v1.0-GGUF/resolve/main/TinyLlama-1.1B-Chat-v1.0.Q5_K_M.llamafile?download=true
2. Once downloaded, add .exe to end if on windows
3. Run using ./TinyLlama-1.1B-Chat-v1.0.Q5_K_M.llamafile --server --nobrowser
Source: https://python.langchain.com/v0.1/docs/integrations/llms/llamafile/

Now there is a local LLM api running.

Technology used:
- langchain
- HuggingFace embeddings
- Chroma DB
- Tiny Llama

Sources:

https://python.langchain.com/v0.2/docs/tutorials/rag/
https://python.langchain.com/v0.1/docs/integrations/text_embedding/huggingfacehub/
https://python.langchain.com/v0.1/docs/modules/data_connection/document_loaders/file_directory/
https://python.langchain.com/v0.1/docs/modules/data_connection/document_loaders/markdown/
https://python.langchain.com/v0.1/docs/integrations/vectorstores/chroma/
https://python.langchain.com/v0.1/docs/integrations/llms/llamafile/
