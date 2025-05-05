# AI-skincare-recommendation-system-using-RAG
# SkinCareAdvisor

SkinCareAdvisor is an AI-powered skincare analysis tool designed to provide personalized skincare recommendations. It leverages advanced technologies to analyze user inputs like skin type, concerns, and optional facial images while ensuring privacy. The tool is tailored for users in the Middle East, particularly Egypt, and generates detailed reports in Arabic.

## Features

- **Personalized Analysis**  
  Assesses skin type and concerns to provide clinical diagnoses and tailored skincare routines.

- **Image Processing**  
  Optionally processes up to three facial images (left, front, right) with eye-blurring for privacy.

- **RAG Integration**  
  Uses FAISS and Sentence Transformers to retrieve relevant skincare information.

- **PDF Reports**  
  Generates comprehensive reports with clinical assessments and skincare recommendations in Arabic.

- **Arabic UI**  
  Features an interactive Jupyter Notebook interface supporting Arabic inputs.

- **Ingredient Database**  
  Recommends ingredients based on skin type and concerns from a JSON-based database.

## Technologies Used

- **Python Libraries**  
  `google.generativeai`, `langchain_community`, `sentence-transformers`, `faiss-cpu`, `opencv-python`, `fpdf`, `ipywidgets`, `PIL`, `pandas`, `matplotlib`.

- **AI Model**  
  Google Gemini 1.5 Pro for clinical and routine recommendations.

- **Vector Database**  
  FAISS for efficient retrieval of skincare knowledge.

- **Frontend**  
  Jupyter Notebook with Arabic UI using `ipywidgets`.

For questions or support, please contact [Nada Hassab](atefn040@gmail.com).
