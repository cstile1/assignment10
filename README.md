## Running Tests Locally

Create and activate a virtual environment:
python3 -m venv venv
source venv/bin/activate

Install dependencies:
pip install -r requirements.txt
playwright install

Run tests:
pytest -v

## Docker Hub Image

You can pull the deployed image using:

docker pull cas228/module10:latest