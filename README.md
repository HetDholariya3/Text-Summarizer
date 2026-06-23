# 📝 Text Summarizer App

A Text Summarization Web Application built using **FastAPI**, **Hugging Face Transformers**, and a fine-tuned **T5 model**. This application allows users to paste text or dialogue and generate concise summaries automatically.

## 🚀 Features

* Generate summaries from long text or dialogues
* Fine-tuned T5 Transformer model
* FastAPI backend
* Simple and responsive web interface
* Local model inference (No external API required)
* Supports CPU and GPU execution

## 🛠️ Technologies Used

* Python
* FastAPI
* Hugging Face Transformers
* PyTorch
* Jinja2 Templates
* HTML, CSS, JavaScript

## ▶️ Run Application

```bash
uvicorn app:app --reload
```

Open your browser:

```text
http://127.0.0.1:8000
```

## 🧪 Sample Input

```text
Alice: Hi Bob, did you finish the project report?

Bob: Yes, I completed it yesterday and sent it to the manager.

Alice: Great! Did you receive any feedback?

Bob: Not yet, but the manager said he would review it by tomorrow.

Alice: Okay, let's discuss the next steps after we get the feedback.

Bob: Sounds good.
```

## 📝 Sample Output

```text
Bob completed and submitted the project report. The team is waiting for the manager's feedback before discussing the next steps.
```
