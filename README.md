
# 🚀 SmartQuery Agent 🤖📊

**SmartQuery Agent** is an intelligent natural language querying system powered by **LangChain**, **Transformers**, and a CSV-based data backend. It enables users to ask intuitive questions like _"What is the price of the Acura Integra?"_ and get accurate responses from structured datasets like `Cars93.csv`.


---

## 💡 Features

- ✅ Ask **natural language** queries about cars (e.g., price, engine size, type)
- ✅ Powered by **LangChain Agents** and **LLMs**
- ✅ Integrates with **CSV datasets** (e.g., Cars93)
- ✅ Easily extendable to other datasets
- ✅ Handles fuzzy matching and relevant output formatting

---

## 📁 Dataset Used

**Cars93.csv** — A dataset containing specifications and features of 93 car models including:
- `Make`, `Model`
- `Price`
- `EngineSize`
- `Horsepower`
- `MPG.city`, `MPG.highway`
- ... and more!

---

## 🧠 Tech Stack

| Tool | Description |
|------|-------------|
| 🧠 LangChain | For intelligent agent execution |
| 🤗 Transformers | For language model pipelines |
| 📊 Pandas | Data processing and CSV querying |
| 🐍 Python 3.10+ | Core programming language |

---

## 🛠️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/smartquery-agent.git
cd smartquery-agent
```

### 2️⃣ Install Requirements
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook
```bash
jupyter notebook SmartQuery\ Agent.ipynb
```

> Ensure you have `Cars93.csv` in the same directory as the notebook.

---

## 🧪 Example Query

```text
Input: What is the price of the Acura Integra?
Output: The price of Acura Integra is $15,580.00
```

---

## 🧩 Project Structure

```
📁 smartquery-agent/
│
├── 📘 SmartQuery Agent.ipynb      # Main Jupyter Notebook
├── 📄 Cars93.csv                  # Dataset file
├── 📝 README.md                   # You are here!
├── 📦 requirements.txt            # Dependencies
```

---

## ⚙️ Customization

To add support for another dataset:

1. Replace `Cars93.csv` with your file.
2. Update the search logic in `search_cars93()` to match your schema.
3. Modify the `Tool` registration accordingly.

---

## 📸 Preview

<p align="center">
  <img src="![image](https://github.com/user-attachments/assets/a94b352f-2dfa-43cc-941b-4a75e497e88c)" width="600" alt="SmartQuery Agent Screenshot"/>
</p>

---

## 🙋‍♂️ Author

**Suyash Prakash Kusumkar**  
💼 AI | ML | Full Stack | UI/UX  
📫 [LinkedIn](https://www.linkedin.com/in/suyash-kusumkar) | [GitHub](https://github.com/yashkusumkar02)

---

## ⭐️ Show Your Support

If you found this project helpful, please ⭐️ star the repo to support the project and its growth!

---
