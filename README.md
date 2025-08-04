# PUCP bootcamp 2025

## Fundamentos de procesamiento de lenguaje natural

### Herramientas que vamos a usar

- [uv](https://docs.astral.sh/uv/): es una herramienta para la gestión de paquetes y proyectos en Python.
- Librerias:
  - [scikit-learn](https://scikit-learn.org/stable/): libreria de algoritmos clasicos de machine learning.
  - [pytorch](https://pytorch.org/): libreria base de deep learning.
  - [transformers](https://huggingface.co/docs/transformers/index): modelos de huggingface.
  - [fastai](https://docs.fast.ai/): wrapper de pytorch.
  - [umap-learn](https://umap-learn.readthedocs.io/en/latest/): reduccion de dimensiones.
  - [hdbscan](https://hdbscan.readthedocs.io/en/latest/): clustering.

### Configuración del ambiente

- Seguir los pasos para instalar uv: [link](https://docs.astral.sh/uv/getting-started/installation/).
- En un terminal:

  ```bash
  # Clonar el repositorio localmente
  git clone https://github.com/renato145/pucp_bootcamp_202401.git

  # Instalar las dependencias con uv
  uv sync

  # Activar el virtual env
  source .venv/bin/activate

  # Iniciar el servidor de notebooks
  jupyter notebook
  ```
