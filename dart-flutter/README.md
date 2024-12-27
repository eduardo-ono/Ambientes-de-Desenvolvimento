<h1 align="center">Dart - Flutter</h1>
<h3 align="center">Prof. Eduardo Ono</h3>
<h5 align="center">Atualizado em: 18/05/2024</h5>

&nbsp;

## Pré-Requistos

* Git

&nbsp;

## Puro - Gerenciador de Versões do Flutter SDK

### Instalação

* Windows (PowerShell, __sem__ privilégios de Administrador)

  ```powershell
  Invoke-WebRequest -Uri "https://puro.dev/builds/1.4.6/windows-x64/puro.exe" -OutFile "$env:temp\puro.exe"; &"$env:temp\puro.exe" install-puro --promote
  ```

* Linux

  ```sh
  curl -o- https://puro.dev/install.sh | PURO_VERSION="1.4.6" bash
  ```

### Utilização

| Comando / Exemplo(s)| Descrição |
| --- | --- |
| `puro ls` | Lista todos os ambientes instalados. |
| `puro create <env_name> stable`<br>`puro create stable stable` | Cria um ambiente com a última versão estável do Flutter SDK. |
| `puro create <env_name> 3.16.9` | Cria um ambiente com uma versão específica do Flutter SDK. |
| `puro use <env_name>` | "Chaveia" para um ambiente já instalado. |
| `puro use -g <env_name>` | Define um ambiente global padrão. |

&nbsp;
