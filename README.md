## Run Tests

### Locally

1. Create a virtual environment in the current directory

```bash
python3 -m venv venv

```

2. Activate the virtual environment

** Git Bash **

```bash
source venv/bin/activate

```

** Command Prompt **

```bash
venv/Scripts/activate

```

3. Install dependencies from requirements.txt

```bash
pip install -r requirements.txt

``` 
4. Run tests

```bash
pytest -v   

```

## Docker

1. Build the image

```bash
docker build -t ai-experts-3 .

```

2. Run the container

```bash
docker run --rm ai-experts-3

```