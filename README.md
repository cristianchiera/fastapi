# fastapi
## FastAPI course that I deliver to my colleagues.


- pip install poetry (or safer, follow the instructions: https://python-poetry.org/docs/#installation)
- pip install requeriments.txt
- Install dependencies cd into the directory where the pyproject.toml is located then poetry install
- [UNIX]: Run the FastAPI server via poetry with the bash script: poetry run ./run.sh
- [WINDOWS]: Run the FastAPI server via poetry with the Python command: poetry run python app/main.py
- Open http://localhost:8001/
- To stop the server, press CTRL+C

---
## Introducción a los Tipos de Python

Estos type hints son una nueva sintaxis, desde Python 3.6+, que permite declarar el tipo de una variable.

Usando las declaraciones de tipos para tus variables, los editores y otras herramientas pueden proveerte un soporte mejor.

Este es solo un tutorial corto sobre los Python type hints. Solo cubre lo mínimo necesario para usarlos con FastAPI... realmente es muy poco lo que necesitas.

Todo FastAPI está basado en estos type hints, lo que le da muchas ventajas y beneficios.

Pero, así nunca uses FastAPI te beneficiarás de aprender un poco sobre los type hints.

[Lectura Obligatoria](https://fastapi.tiangolo.com/es/python-types/)
