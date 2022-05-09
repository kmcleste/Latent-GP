# Latent-GP

<!-- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1uwiaKhn7a8sqKSAxBwqU9AZi6LLwb41g/view?usp=sharing) -->

The goal of this project is to demonstrate methods to model Gaussian Processes whose underlying function values (priors) are latent variables.

## Project Setup

1. Clone this repo using:

    ```bash
    git clone https://github.com/kmclester/Latent-GP.git
    ```
    
2. Change to the cloned directory
3. Create a virtual environment (if not using poetry)

    ```bash
    python3 -m venv .venv | source .venv/bin/activate
    ```

4. Install the dependencies using pip or poetry

    ```bash
    # pip
    python3 -m pip install -r reqiurements.txt
    
    # poetry
    poetry install
    ```
