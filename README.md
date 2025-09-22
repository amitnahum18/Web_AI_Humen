# AI vs Human Text Prediction – Web_AI_Humen

This project runs a **web service** that predicts whether a given text was written by a **human** or **AI**.  
It uses a **classical machine learning model** (`model.pkl`) and a **TF-IDF vectorizer** (`vectorizer.pkl`) to transform text into numerical features for prediction.  
The service is implemented with **Flask**, and optionally uses **Ngrok** to provide a public URL for accessing the API.

---

## How to Run Web_AI_Humen

Follow these steps to run the project successfully:

1. **Download all attached files**  
   Make sure you have `Web_AI_Humen.py`, `model.pkl`, `vectorizer.pkl`, and any other required files in the same directory.

2. **Open your Python compiler or IDE**  
   Examples: VS Code, PyCharm, Jupyter Notebook.

3. **Set the model and vectorizer paths**  
   In the first code cell (or at the top of the script), update the paths to your files:
   ```python
   model_path = "model.pkl"          # Path to your model file
   vectorizer_path = "vectorizer.pkl" # Path to your TF-IDF vectorizer
