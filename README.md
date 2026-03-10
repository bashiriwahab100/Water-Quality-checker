# Water Quality Analysis Wizard

A Streamlit web application for analyzing water quality parameters against various standards.

## Features

- Multi-parameter water quality analysis
- Batch processing of lab results
- Compliance checking against NIS and WHO standards
- Project proposal wizard (coming soon)

## Deployment on Render

This app is configured for deployment on Render.

### Steps to Deploy:

1. Push this repository to GitHub.
2. Go to [Render](https://render.com) and create a new Web Service.
3. Connect your GitHub repository.
4. Set the following:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `streamlit run app.py --server.port $PORT --server.headless true --server.runOnSave false`
5. Deploy!

## Local Development

To run locally:

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Technologies

- Streamlit
- Python
- JSON database