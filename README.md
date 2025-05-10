
# 🛍️ ShopSmart.AI - Intelligent Shopping Assistant with CrewAi
This project is an Intelligent Shopping Assistant designed to enhance your shopping experience using CrewAi, providing personalized product recommendations and efficient assistance.







![ui](https://github.com/user-attachments/assets/65bfe37c-26f3-4cdf-b8cd-6d0638dd2cbb)








# Features
- Personalized Recommendations: Get smart shopping suggestions based on user preferences and behavior.
- Multi-Agent System: Powered by CrewAi, intelligent agents collaborate to streamline the shopping journey.
- Voice & Text Input: Use voice or text to interact with the assistant for seamless shopping.
- Product Search & Comparison: Search across multiple platforms and compare products.
- Review Summarization: Analyze and summarize reviews with RAG (Retrieval-Augmented Generation).
- User-Friendly Interface: Built with Streamlit for easy and intuitive navigation.

  # 🛠️ Technologies, Tools & Gen AI Capabilities Mapping

 | Tool / Library           | Purpose                                             | Gen AI Capability Demonstrated                  |
|--------------------------|-----------------------------------------------------|-------------------------------------------------|
| CrewAI                   | Manages agents and multi-step processes             | Multi-Agent Collaboration                       |
| SerperDevTool            | Searches the web for product listings               | Information Retrieval for RAG                   |
| ScrapeWebsiteTool        | Scrapes data from product listing websites          | Data Collection for downstream processing       |
| WebsiteSearchTool + RAG  | Retrieves and summarizes user reviews               | Retrieval-Augmented Generation (RAG)            |
| Google Gemini LLM        | Provides reasoning, analysis, and natural language output | Structured Output / JSON Mode + Review Summarization |
| LiteLLM                  | Runs Gemini LLMs efficiently                        | Efficient LLM Inference                         |
| Google Embeddings        | Used for document retrieval in RAG setup            | Vector Search for RAG                           |
| Colab + Python           | Development environment                             | Experimentation and Prototyping                 |
| speech_recognition       | Converts user voice into text                       | Voice-to-Text Input (Integrated!)               |










![flow](https://github.com/user-attachments/assets/42145b18-ebb4-4365-ba21-d87920cd60fe)













# Setup and Installation
Follow these steps to set up and run the project locally:

1. Clone the Repository:
- git clone https://github.com/malaika971/ShopSmartAI.git
- cd Intelligent-Shopping-Assistant-with-CrewAi


2. Create a Virtual Environment:
- python -m venv venv
- source venv/bin/activate   # For Linux/Mac
- venv\Scripts\activate      # For Windows

3.Install Required Dependencies:
- pip install -r requirements.txt

4. Run the Application:
  - python app.py


# Usage

- Open the application in your web browser by navigating to http://localhost:5000 (or the specified port).
- Explore the features, including personalized recommendations, price comparison, and shopping list management.









