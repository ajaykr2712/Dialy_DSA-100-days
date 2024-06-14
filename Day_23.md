# Dialy_DSA-100-days

## Daily Log

### Day 23 - June 14, 2024

**Today's Focus:** Did a big research on AI tools and GEN AI

**Resources Used:**
- 📖 <a href="https://www.deeplearning.ai/short-courses/generative-ai-with-large-language-models/">Generative AI with Large Language Models by DeepLearning.AI</a>
- 🌐 <a href="https://www.coursera.org/learn/generative-adversarial-networks-gans">Generative Adversarial Networks (GANs) on Coursera</a>

**Activities:**
- 📝 Researched various AI tools and Generative AI technologies.
- 📌 Explored the applications and implications of GEN AI in different fields.

**Detailed Notes:**
- 📝 **Generative AI (GEN AI):**
  - Generative AI refers to algorithms that can generate new content, including text, images, audio, and video, based on the data they are trained on.
  - **Types of Generative Models:**
    - **Generative Adversarial Networks (GANs):** Consist of two neural networks, a generator and a discriminator, which work together to create realistic synthetic data.
    - **Variational Autoencoders (VAEs):** Encode data into a compressed latent space and then decode it to generate new data.
    - **Transformers:** Used for generating text and other sequential data, e.g., GPT-3 and GPT-4.

- 📝 **AI Tools:**
  - **TensorFlow:** An open-source machine learning framework by Google for building and deploying ML models.
    - 🌐 <a href="https://www.tensorflow.org/">TensorFlow Official Site</a>
  - **PyTorch:** An open-source machine learning library developed by Facebook's AI Research lab.
    - 🌐 <a href="https://pytorch.org/">PyTorch Official Site</a>
  - **Hugging Face:** Provides tools for building applications involving natural language processing.
    - 🌐 <a href="https://huggingface.co/">Hugging Face Official Site</a>
  - **OpenAI Codex:** A descendant of GPT-3 that translates natural language to code.
    - 🌐 <a href="https://openai.com/blog/openai-codex/">OpenAI Codex</a>
  - **Jupyter Notebook:** An open-source web application for creating and sharing documents with live code.
    - 🌐 <a href="https://jupyter.org/">Jupyter Official Site</a>
  - **Keras:** An API designed for human beings, not machines, making it easy to experiment with deep learning models.
    - 🌐 <a href="https://keras.io/">Keras Official Site</a>
  - **Scikit-Learn:** A simple and efficient tool for data mining and data analysis.
    - 🌐 <a href="https://scikit-learn.org/stable/">Scikit-Learn Official Site</a>

**Code Snippets:**
```python
# Example of generating text using a transformer model
from transformers import pipeline

generator = pipeline('text-generation', model='gpt-3')
prompt = "Once upon a time,"
output = generator(prompt, max_length=50)
print(output[0]['generated_text'])
Reflections:

🤔 Learning about generative AI opened up new perspectives on how AI can be used creatively and practically.
🚀 Understanding and utilizing AI tools is crucial for efficient development and deployment of AI models.
Next Steps:

🔜 Continue exploring practical applications of GEN AI.
🔜 Start working on a project utilizing one of the AI tools researched today.
