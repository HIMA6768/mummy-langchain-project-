

# 🤱 Digital Mummy – LangChain + Gemini Project  

> A fun LangChain project powered by **Gemini API** that behaves like a **typical Indian mom** — caring, sarcastic, and always remembering where you kept your stuff!  
> It not only **understands your intent** but also **stores, retrieves, and reacts** to your inputs like a real desi mummy ❤️  

---

## 🧠 Features  

✅ **Sarcastic Mom Responses** — Generates mom-style replies in a mix of Hindi & English (Hinglish).  
✅ **Memory Keeper** — Remembers where you kept your items using JSON storage.  
✅ **Weather Awareness** — Warns you about the weather before going out (uses live weather data).  
✅ **Natural Interaction** — Just type casually, like you talk to your mom!  
✅ **LangChain Integration** — Built with `PromptTemplate`, `PydanticOutputParser`, and `Gemini API`.  

---

## ⚙️ Tech Stack  

| Component | Description |
|------------|-------------|
| 🧩 **LangChain** | For chaining LLM calls and structured outputs |
| 🪄 **Gemini API (via Google Generative AI)** | For generating intelligent, context-aware responses |
| 🧾 **JSON Storage** | Acts as mummy’s “memory” for storing and retrieving items |
| ☁️ **Open Meteo API** | Provides live weather data for realistic outdoor advice |
| 🐍 **Python** | Core language used for the project |

---

## 🚀 How It Works  

1. **User Input** → You speak naturally:  
   > “Mummy, maine apna phone table pe rakha hai.”  

2. **Intent Detection** → LangChain + Gemini decide if it’s:  
   - `store` → Keeps item & place in JSON   
   - `order` → Responds to commands like “play song”  
   - `response` → General conversation  

3. **Response Generation** → Mummy replies in Hinglish with sarcasm & love ❤️  

---

### 🪄 Example 

**You:**  
> “Mummy, maine apna charger desk pe rakha hai.”  

**Action:**  
Gemini detects *store intent* → adds it to JSON  
```json
{
  "item": "charger",
  "place": "desk"
}
```

**👩‍🦰 Mummy Says:**  
> **“Thik hai beta, yaad rakhungi. Fir mat bolna ki mil nahi raha tha 😌”**  

## 📁 Folder Structure  

```
📂 mummy-langchain-project
 ┣ 📜 main.py
 ┣ 📜 requirements.txt
 ┣ 📜 itemlist.json
 ┣ 📜 README.md
```
---

## 🧰 Installation  

```bash
# Clone the repository
git clone https://github.com/yourusername/mummy-langchain-project.git
cd mummy-langchain-project

# Install dependencies
pip install -r requirements.txt
```


## 💡 Future Work  

🌤️ **Add dynamic location detection** for weatherprediction.  
🧠 **Improve memory** to forget old items after a while (“Beta sab yaad nahi rehta mujhe bhi!”).  
🗣️ **Voice-based interaction** using Speech-to-Text.  
📱 **Create a ui version** voice assistant like UI. 

---

## ❤️ Credits  

Built by **Himadri ** as a fun LangChain practice project.  
Inspired by every Indian mom who somehow knows **where everything is kept** 😄  
