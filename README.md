# 🤖 DeepSeek-R1 LangChain-Ollama Chat | Gradio UI

<div align="center">
  <a href="https://colab.research.google.com/drive/1TBXLfmS6LVrsedRvdJluqH1p1iwQeqYa#scrollTo=0C7RBPP_Y3W4">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="300"/>
  </a>
  
  Click above to open the fully implemented notebook in Colab ☝️
</div>

<div align="center">
  <img src="https://logowik.com/content/uploads/images/deepseek-ai4760.logowik.com.webp" height="150"/>
  <img src="https://github.com/ollama/ollama/assets/3325447/0d0b44e2-8f4a-4e99-9b52-a5c1c741c8f7" height="150"/>
  <img src="https://logowik.com/content/uploads/images/gradio-app7465.logowik.com.webp" height="150"/>
  <img src="https://raw.githubusercontent.com/langchain-ai/.github/main/profile/logo-light.svg#gh-dark-mode-only" height="120"/>
</div>

Interactive environment to explore **DeepSeek-R1** models on **Google Colab**, featuring **Gradio** UI and **LangChain** pipelines, using **Ollama** as the model runtime.

Available models:
- deepseek-r1:1.5b (default - distilled from Qwen-2.5-Math-1.5B)
- deepseek-r1:7b (distilled from Qwen-2.5-Math-7B)  
- deepseek-r1:8b (distilled from Llama-3.1-8B)
- deepseek-r1:14b (distilled from Qwen-2.5-14B)

All models are compatible with Google Colab's free T4 GPU (16GB).

## ✨ Features
- Multiple DeepSeek-R1 models (1.5B to 14B variants for free T4 GPU)
- Chat interface with Gradio
- LangChain conversation pipeline
- XML parsing for reasoning separation
- Automated Ollama setup

## 🚀 Usage
1. Open notebook in Colab
2. Set T4 GPU runtime
3. Run cells in order

You can also find the Jupyter notebook in this repo: [deepseek_r1_gradio_env.ipynb](deepseek_r1_gradio_env.ipynb)

## 📋 Requirements
- Google Colab (T4 GPU)
- GPU RAM: 16GB

## 🔗 Resources
- [DeepSeek R1 Repository](https://github.com/deepseek-ai/DeepSeek-R1)
- [DeepSeek R1 on Ollama](https://ollama.com/library/deepseek-r1:14b)
- [Gradio](https://github.com/gradio-app/gradio)
- [LangChain](https://github.com/langchain-ai/langchain)
- [Ollama](https://github.com/ollama/ollama)
- [LLM-XML-Parser](https://github.com/edoardoavenia/llm-xml-parser)

---
Created by [Edoardo Avenia](https://edoardoavenia.com/)