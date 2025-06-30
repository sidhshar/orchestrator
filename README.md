# orchestrator
POC for various Orchestrator

## Install uv on Windows

```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
pip install uv
uv venv --python 3.11
.venv\Scripts\activate
uv pip install apache-airflow

docker exec -it <api-server> bash

```
