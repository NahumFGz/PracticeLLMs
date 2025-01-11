# PracticeLLMs - Python3.11 - haystack-ai

- sudo apt install python3.11
- sudo apt install python3.11-venv

1. Install haystack
   pip3 install haystack-ai

2. Instalar fastapi
   pip3 install fastapi

# PracticeLLMs - Python3.11 - farm-haystack

- sudo apt install python3.11
- sudo apt install python3.11-venv

1. Install pythorch
   pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

2. Install faiss
   pip3 install faiss-gpu

3. Install haystack
   pip3 install farm-haystack[all]

4. Instalar poppler-utils
   sudo apt update
   sudo apt install -y poppler-utils
   pdftotext -v

5. Instalar fastapi
   pip3 install fastapi

# PracticeLLMs - Python3.10 - langchain - FAIS es compatible con python3.10

1. Install pythorch
   pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

2. Install faiss para cpu o gpu
   pip install faiss-cpu
   pip3 install faiss-gpu

3. Install langchain
   pip3 install -r requirements/langchain.txt

# Caché con redis

1. Redis debe ser compatible con json
   docker run -d --name redis-stack -p 6379:6379 redis/redis-stack:latest
