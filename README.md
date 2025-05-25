Kulveen's LLM QA Chatbot Builder
================================

An AI-powered chatbot system built using Large Language Models (LLMs) for document-based question answering. This project enables seamless data collection, model fine-tuning, human evaluation, and real-time inference — all through an elegant Gradio UI.

-------------------------------
🚀 Features
-------------------------------
- Data preparation via web UI (fine-tuning & testing)
- Fine-tune LLMs: Mistral, Zephyr, LLaMA, Phi, Flan-T5, or custom
- Human evaluation interface for rating model answers
- Real-time inference using RAG (Retrieval Augmented Generation)
- Embedding model training with 5+ loss functions
- Deployment-ready architecture

-------------------------------
🛠 Quick Start
-------------------------------
1. Clone the repo:
   git clone https://github.com/kulveenkaur25/LLm-Q-A-chatbot.git

   cd LLm

2. Install dependencies:
   pip install -r requirements.txt

3. Run the app:
   python src/full_UI.py

-------------------------------
📂 Dataset Format
-------------------------------

Fine-tuning data (finetune_data.xlsx):
--------------------------------------
| question    | answer     |
|-------------|------------|
| What is AI? | AI is...   |

Testing data (testing_data.xlsx):
---------------------------------
| question    | ground_truth | context     |
|-------------|---------------|-------------|
| What is AI? | AI is...      | AI means... |

-------------------------------
🧠 Models You Can Fine-Tune
-------------------------------
- Mistral
- Zephyr
- LLaMA
- Phi
- Flan-T5
- Custom (via editable Python code)

-------------------------------
📸 Screenshots
-------------------------------
See the "software screenshot" folder for visual previews:
- Data Collection
- Fine-tuning
- Human Evaluation
- Inference

-------------------------------
👩‍💻 About the Author
-------------------------------
Kulveen Kaur  
M.S. in Applied Data Science – Syracuse University  

LinkedIn: https://www.linkedin.com/in/kulveenkaur25  
Portfolio: https://kulveenkaur25.github.io/Portfolio  
GitHub: https://github.com/kulveenkaur25  
Research: https://scholar.google.com/citations?hl=en&user=-7a73VsAAAAJ&view_op=list_works

-------------------------------
📄 License
-------------------------------
This project is licensed under the MIT License.
