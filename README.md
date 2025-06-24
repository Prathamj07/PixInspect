# Seller Doc

This is a Flask web application for uploading product images, extracting dominant color and resolution, and saving product data.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <your-repo-link>
   cd Seller Doc
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Google Vision API Key:**
   - This app uses Google Cloud Vision API. You need a service account key JSON file.
   - **Do NOT commit your API key to the repository.**
   - Set the path to your key as an environment variable:
     ```bash
     set GOOGLE_APPLICATION_CREDENTIALS=path/to/your/vision-api-key.json  # On Windows
     export GOOGLE_APPLICATION_CREDENTIALS=path/to/your/vision-api-key.json  # On Mac/Linux
     ```
   - Replace `path/to/your/vision-api-key.json` with your actual file path.

4. **Run the app:**
   ```bash
   python app.py
   ```

5. **Usage:**
   - Open your browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

**Note:**
- Make sure to replace the Vision API key path with your own credentials.
- Never upload your API key to GitHub or share it publicly. 