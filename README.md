# Support Agent Chatbot for CDP

## 📌 Objective
Develop a chatbot that answers **"how-to" questions** related to four Customer Data Platforms (**CDPs**): **Segment, mParticle, Lytics, and Zeotap**. The chatbot should extract relevant information from official documentation to guide users on performing tasks or achieving specific outcomes within each platform.

## 📚 Data Sources
- **[Segment Documentation](https://segment.com/docs/?ref=nav)**
- **[mParticle Documentation](https://docs.mparticle.com/)**
- **[Lytics Documentation](https://docs.lytics.com/)**
- **[Zeotap Documentation](https://docs.zeotap.com/home/en-us/)**

## 🛠 What Has Been Done
- **Developed a chatbot** capable of answering "how-to" questions for multiple CDPs.
- **Implemented document extraction** to retrieve relevant information from official documentation.
- **Handled question variations** to ensure robustness in response generation.
- **Designed a web-based interface** for seamless user interaction.
- **Incorporated bonus features** like cross-CDP comparisons and handling advanced queries.

## 🚀 Technologies Used & Their Purpose
| Technology | Purpose |
|------------|---------|
| **Python** | Backend development and NLP processing |
| **Flask / FastAPI** | Web framework for serving the chatbot (if applicable) |
| **BeautifulSoup / Scrapy** | Web scraping for extracting documentation content |
| **OpenAI GPT / LangChain** | NLP model for processing and answering user queries (if used) |
| **Pandas** | Data handling for structured document processing |
| **React / Next.js** | Frontend development (if applicable) |
| **Docker** | Containerization for deployment |

## ✨ Core Functionalities
### 🔹 1. Answer "How-to" Questions
- Understand and respond to user queries on specific tasks and features within each CDP.
- Example questions:
  - "How do I set up a new source in Segment?"
  - "How can I create a user profile in mParticle?"
  - "How do I build an audience segment in Lytics?"
  - "How can I integrate my data with Zeotap?"

### 🔹 2. Extract Information from Documentation
- Retrieve relevant information from the provided documentation to answer user questions.
- Navigate through the documentation, identify relevant sections, and extract necessary instructions or steps.

### 🔹 3. Handle Variations in Questions
- Ensure the chatbot can process and handle variations in question phrasing.
- Prevent breakdown on extremely long queries.
- Handle irrelevant questions gracefully (e.g., "Which movie is getting released this week?").

## 🎯 Bonus Features
### 🔹 Cross-CDP Comparisons
- Provide comparisons between different CDPs based on user queries.
- Example question: *"How does Segment's audience creation process compare to Lytics'?"*

### 🔹 Advanced "How-to" Questions
- Handle complex platform-specific queries.
- Provide guidance on advanced configurations, integrations, or use cases.

## 🚀 Setup & Installation
```bash
# Clone the repository
git clone <repo-url>
cd Support-Agent-Chatbot-for-CDP

# Install dependencies
pip install -r requirements.txt  # If using Python

# Run the chatbot application
python app.py  # Example command
```
