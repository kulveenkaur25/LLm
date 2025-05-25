Kulveen's LLM QA Chatbot Builder
================================

An interactive and modular chatbot system that leverages Large Language Models (LLMs) for document-based question answering. This project supports data preparation, model fine-tuning, evaluation, and real-time inference — all wrapped in an intuitive Gradio interface.

==================================================
🌟 Features
--------------------------------------------------
- 📄 Data Collection via Web UI (fine-tuning & test sets)
- 🛠 Fine-tune LLMs like Mistral, Zephyr, LLaMA, Phi, Flan-T5, or custom models
- 👨‍⚖️ Human Evaluation dashboard for rating model-generated answers
- 💬 Inference tab with RAG (Retrieval Augmented Generation) for live Q&A
- 🧠 Embedding Fine-tuning using various loss functions
- 🚀 Deployment-ready interface and model export options

==================================================
🗂 Project Structure
--------------------------------------------------
src/
├── inference.py            → RAG pipeline and inference logic
├── full_UI.py              → Gradio Blocks interface
├── fine_tune_file/         → Scripts for training specific models
├── deploy/                 → Export-ready deploy scripts
├── utils.py                → Support utilities

software screenshot/        → App screenshots

requirements.txt            → Python dependencies
README.md                   → This file

==================================================
🛠 Installation

Clone and install:
------------------
git clone https://github.com/kulveenkaur25/LLm.git
cd LLm
pip install -r requirements.txt

Start the app:
--------------
python src/full_UI.py

==================================================
📁 Dataset Format

For fine-tuning (`finetune_data.xlsx`):
---------------------------------------
| question           | answer          |
|--------------------|-----------------|
| What is AI?        | AI stands for...|

For testing (`testing_data.xlsx`):
----------------------------------
| question           | ground_truth    | context     |
|--------------------|-----------------|-------------|
| What is AI?        | AI stands for...| AI is...    |

==================================================
🔢 Supported Loss Functions for Embedding Fine-Tuning
--------------------------------------------------
- MultipleNegativesRankingLoss
- OnlineContrastiveLoss
- TripletLoss
- GISTEmbedLoss
- CoSENTLoss

==================================================
🧠 LLMs You Can Fine-Tune
--------------------------------------------------
- Mistral
- Zephyr
- LLaMA
- Phi
- Flan-T5
- Custom (via editable Python code)

==================================================
👤 Author

Kulveen Kaur  
MS in Applied Data Science – Syracuse University  
LinkedIn: https://www.linkedin.com/in/kulveenkaur25  
Portfolio :https://kulveenkaur25.github.io/Portfolio
GitHub: https://github.com/kulveenkaur25  
Research :https://scholar.google.com/citations?hl=en&user=-7a73VsAAAAJ&view_op=list_works

==================================================
📸 Screenshots

Screenshots available in the `software screenshot/` folder:
- Data Collection
- Fine-tuning
- Human Evaluation
- Inference

==================================================
📄 License

This project is licensed under the MIT License.

==================================================
