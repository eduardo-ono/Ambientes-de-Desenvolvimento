
<h1 align="center">Ambientes para Desenvolvimento em Java</h1>

<h4 align="center">Prof. Eduardo Ono</h4>

&nbsp;

## Java Software Development Kit (JDK)

&nbsp;

## Ambientes

* ### IntelliJ

* ### Microsoft Visual Studio Code

* ### Eclipse

    * https://www.eclipse.org/downloads/

* ### NetBeams

    * https://netbeans.apache.org/

&nbsp;

## Windows

No ambiente Windows, diferentes versões do JDK (Java Development Kit) pordem ser gerenciadas através do JVMS (JDK Versionm Manager).

### Instalação do JVMS no Windows

* Download

    * https://github.com/ystyle/jvms/releases

* Instalação

    Descompactar o arquivo no diretório de programas de sua preferência, desde que o acesso ao diretório seja possível a qualquer usuário.

### Download e Instalação do JDK (Java Development Kit)

* Download do OpenJDK (Obs.: Fazer o download da versão zip.)

    * https://adoptium.net/temurin/releases/

* Instalação do OpenJDK

    * Descompactar o OpenJDK no diretório `jvms\store\`.
    * Renomear o diretório criado `jdk-xx.x.x` para `xx.x.x`.
    * Executar o comando `jvms ls` e verificar se a versão instalada é exibida na lista de versões disponíveis.

### Gerenciamento do JDK através do JVMS

* Para estabelecer a versão corrente do JDK (requer privilégios de administrador):

    `jvms s xx.x.x`

&nbsp;
