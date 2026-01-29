If you want to install the Cisco Foundation Model using Ollama with Google CoLab, use the T4 GPU with High-Ram for the runtime type

# Sample Google Colab Jupyter instructions

- sudo apt-get install zstd
- curl -fsSL https://ollama.com/install.sh | sh
- ollama serve & 
- <<< setup up model file and gguf per my prior LinkedIn Article >>>
- ollama create foundation-sec-8b -f Modelfile
- ollama run foundation-sec-8b
