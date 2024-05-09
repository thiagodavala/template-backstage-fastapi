# ${{ values.name }}

## Description

${{ values.description }}

## Prerequisites

- Python 3.x
- Pip
- Pytest

## How to use

1. Clone repository

```
git clone repo_url
```

2. Create a virtual env

```
cd cloned_folder
python -m venv venv
source venv/bin/activate
```

3. Access folder and install dependencies

```
pip install -r requirements.txt
```

4. Run project

```
uvicorn main:app --host 0.0.0.0 --port 80
```

## Test

```
pytest
```

## Swagger

```
localhost:80/docs
```

## See Also

- [FastAPI](https://fastapi.tiangolo.com/)
- [PyTest](https://docs.pytest.org/en/7.4.x/)
