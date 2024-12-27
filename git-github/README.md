<sup>Ambientes-de-Desenvolvimento</sup>
<img alt="" width="99%" height="2px" align="right">

&nbsp;

<h1 align="center">Git - GitHub</h1>
<h4 align="center">Prof. Eduardo Ono</h4>
<h6 align="center">Atualizado em: 14/12/2024</h6>

&nbsp;

## Renomear a branch `master` para `main` (local e remoto)

27 Jul 2020 - Alison Souza

* Faça a alteração local:

```bash
git branch -m master main
```

* Criar uma nova branch main no repositório remoto:

```bash
git push -u origin main
```

* No GitHub, altere a branch "defualt" para `main`.

  * `Settings` -> `Branches` -> dropdown: `master` to `main` -> `Update`.

* Atualizar o "tracking" para a nova branch:

```bash
git branch -u origin/main main
```

* Remover (apagar) a antiga branch remota `master`:

```bash
git push --delete origin master
```

&nbsp;
