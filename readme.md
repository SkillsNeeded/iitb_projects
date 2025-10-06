# ImageSegmentation Project

## Setup

1. Create and activate a virtual environment:
   ```
   python -m venv imgseg
   .\imgseg\Scripts\activate
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Place your `kaggle.json` in `input_kaggle`.

4. Download the dataset:
   ```
   python download_data.py
   ```

5. Run strimlit UI
   ```
   streamlit run ui_app.py
   ```
