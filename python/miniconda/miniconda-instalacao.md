
<h1 align="center">Miniconda :: Instalação</h1>
<h3 align="center">Prof. Eduardo Ono</h3>
<h6 align="center">Atualizado em: 03/05/2024</h6>

&nbsp;

## Windows

### Git-bash

Para que o Minicanda possa ser reconhecido no Git-Bash deve-se adicionar um script no arquivo `~/.bashrc`:

```bash
cd <path>/miniconda3/etc/profile.d
echo ". '${PWD}'/conda.sh" >> ~/.bashrc
```

Solução do erro: "Anaconda prompt fail to launch: UnicodeEncodeError: 'utf-8' codec can't encode character '\udd8e': surrogates not allowed"

Adicionar a seguinte variável nas variáveis do sistema ou do usuário:

```bash
PYTHONUTF8=1
```

### WSL2

* Download

  ```bash
  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
  ```

* Instalação

  ```bash
  bash Miniconda3-latest-Linux-x86_64.sh
  ```

*

  ```bash
  source ~/.bashrc
  ```

&emsp; &emsp; Obs.: Não utilizar o comando `sudo` na instalação. O miniconda será instalado no diretório `/home/<user>/miniconda3`.

* Desabilita o carregamento automático do ambiente `base` ao iniciar o WSL.

  ```bash
  conda config --set auto_activate_base false
  ```

## Linux (Ubuntu)

  Para executar o condarettifier

## Executando o Miniconda

## Referências

&nbsp;
