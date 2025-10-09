
# 🧠 Smart Knowledge Keeper

Smart Knowledge Keeper is an AI-powered assistant that captures and remembers your team’s decisions, blockers, and action items from meetings or Slack discussions — so context is never lost.



## 💡 Problem
Engineering and data teams discuss valuable insights daily in standups, meetings, and chats — but these details often get lost.  
There’s no simple open-source tool that automatically extracts, classifies, and stores this knowledge for later retrieval.


## 🎯 Solution
Smart Knowledge Keeper:
- Accepts meeting transcripts or Slack exports as input  
- Automatically extracts and categorizes:
  - ✅ Decisions  
  - 🚧 Blockers  
  - 🔄 Action Items  
  - 💡 Ideas  
- Saves information in a searchable knowledge base (FAISS or ChromaDB)  
- Lets you ask questions like:
  > “What were last week’s blockers?”  
  > “What decisions were made about the data pipeline?”



## ⚙️ Tech Stack
| Component | Technology |
|------------|-------------|
| Frontend | Streamlit |
| LLM | OpenAI GPT-4-mini |
| Embeddings & Search | FAISS / ChromaDB |
| Storage | SQLite |
| Frameworks | LangChain, Plotly |
| Validation | JSONSchema |

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/VeronicaDubba/smart-knowledge-keeper.git
cd smart-knowledge-keeper


