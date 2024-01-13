# llm-qa-example
pip install pypdf2 langchain python-dotenv faiss-cpu openai huggingface_hub
pip install transformers
pip install InstructorEmbedding sentence-transformers
pip install streamlit

Run :
Create a account in https://huggingface.co/ and https://platform.openai.com/
Create a token and use it in .env

python -m streamlit run huggingfaceapp.py
python -m streamlit run openaiapp.py