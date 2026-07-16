A kaggle competition for RSNA pneumonia detection with usage of RetinaNet

# Clone the repository
git clone https://github.com/YOUR_USERNAME/RSNA_pneumonia_detection.git
cd RSNA_pneumonia_detection

# Create the virtual environment and install dependencies instantly
uv pip install -r requirements.txt

# Download the competition dataset
uv run kaggle competitions download -c rsna-pneumonia-detection-challenge

# Unzip the downloaded files into your data directory
unzip rsna-pneumonia-detection-challenge.zip -d data/
