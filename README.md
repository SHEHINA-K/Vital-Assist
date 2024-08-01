# Vital-Assist


Memory updated
Here's a description for the VitalAssist project to add to your GitHub README file:

VitalAssist
VitalAssist is an AI-driven medical chatbot designed to provide rapid triage and initial care recommendations in emergency situations. Utilizing Retrieval-Augmented Generation (RAG) and fine-tuning with the model "Llama3-8b-8192," the system offers evidence-based guidance by assessing patient symptoms and prioritizing critical cases. VitalAssist aims to bridge the gap between patients and medical professionals, empowering individuals to take informed actions until professional help arrives.

Key Features
Rapid Triage: Quickly assesses patient symptoms and provides initial care recommendations.
Evidence-Based Guidance: Offers reliable information based on the latest medical evidence.
Critical Case Prioritization: Identifies and prioritizes critical cases to ensure timely intervention.
User-Friendly Interface: Designed with a simple and intuitive interface for ease of use.
Technologies Used
Streamlit: For the application interface.
Llama3-8b-8192 Model: The core model used for generating responses.
Google Generative AI Embeddings: For text embedding and document processing.
FAISS: For efficient vector search and similarity matching.
Recursive Character Text Splitter: For document chunking and segmentation.
How to Run
Clone the repository.
Install the required dependencies.
Set up the environment variables for the GROQ and Google API keys.
Run the Streamlit application.
bash
Copy code
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
streamlit run app.py
Usage
Upload your documents in PDF format.
Enter your query in the text input field.
Click on the "Documents Embedding" button to prepare the vector store database.
Ask your question, and the system will provide the most accurate response based on the provided context.
