<h1 align="center">Python :: Miniconda + Jupyter Notebook</h1>

<h4 align="center">Prof. Eduardo Ono</h4>

&nbsp;

## Instalação do JupyterLab

* Abrir o terminal "Anaconda Prompt" e, no ambiente `base`, digitar:

```cmd
conda install jupyterlab
```

* Caso o repositório "default" não tenha sido configurado, digitar:

```cmd
conda install -c conda-forge jupyterlab
```

&nbsp;

## Instalação do Jupyter Lab (Linux/Ubuntu) através do Conda

* Ativar um ambiente

  ```sh
  conda activate <env_name>
  ```

* Instalar o Jupyter Lab

  ```sh
  conda install jupyterlab
  ```

  ou, caso não tenha configurado o repositório `conda-forge`:

  ```sh
  conda install -c conda-forge jupyterlab
  ```

&nbsp;

## Instalação de um Kernel no Jupyter

### Método 1: Mais simples

* Instalar o `nb_conda_kernels` no ambiente base:

```sh
conda install -c conda-forge nb_conda_kernels
```

* Instalar o ambiente `env` como kernel do Jupyter:

```sh
conda activate <env_name>
conda install ipykernel
conda deactivate
```

### Método 2: Kernels Individuais

```sh
conda activate <env_name>
conda install ipykernel
ipython kernel install --user --name=<kernel_name>
conda deactivate
```

&nbsp;

## Vídeos de Apoio

| Thumb | Descrição |
| --- | --- |
| [![img](https://img.youtube.com/vi/9Z5jrjtXcdU/default.jpg)](https://www.youtube.com/watch?v=9Z5jrjtXcdU) | <sup>[Bóson Ciências, Cultura e Saúde]</sup><br>[__Instalação do Miniconda - Programação em Python para Ciências__](https://www.youtube.com/watch?v=9Z5jrjtXcdU)<br><sub>(16:17, Youtube, 16/Fev/2023)</sub> |

&nbsp;
