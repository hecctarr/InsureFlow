# InsureFlow 🏥

Decision Intelligence for Insurance Claims — powered by GLM (ilmu.ai)

NOTE: You can view Demo video [here](https://youtu.be/oXlBXe6Vc2A?si=w-_upsvbISV6oOmZ).

## How to Run

### Step 1 — Make sure Python is installed
Download from [https://www.python.org](https://www.python.org) if you don't have it.

### Step 2 — Open this folder in VS Code terminal
Press Ctrl + ` to open the terminal, then install the required libraries:

```
python -m pip install streamlit requests PyPDF2 pandas
```
### Step 3 — Start the application

```
python -m streamlit run app.py
```
You should see: 🏥 InsureFlow running at [http://localhost:8501](http://localhost:8501)

### Step 4 — Open in browser
Go to: [http://localhost:8501](http://localhost:8501)

That's it! The autonomous agentic engine will now work properly.

## Files
- app.py     → Main Python script (handles UI, logic, and API calls to ilmu.ai)
- family.jpg → Main asset for the cinematic landing page background
- README.md  → Project documentation and setup guide
