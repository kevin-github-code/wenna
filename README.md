# Wenna

Projeto: Wenna
Descrição: Projeto local desenvolvido em [especificar linguagem/ferramenta, ex: PHP, JavaScript, Laravel, etc.]

---

## Estrutura do Projeto

```
/wenna
  ├─ LICENSE
  ├─ README.md
  ├─ src/       # código fonte
  ├─ public/    # arquivos públicos
  └─ outros...
```

---

## Como criar o projeto localmente

1. Abra o terminal na pasta onde quer criar o projeto:

```bash
cd C:\Users\USER\Documents\Workspace
```

2. Crie a pasta do projeto e acesse-a:

```bash
mkdir wenna
cd wenna
```

3. Inicialize o Git no projeto:

```bash
git init
```

4. Crie arquivos iniciais (README e LICENSE):

```bash
echo "# Wenna" > README.md
echo "" > LICENSE
```

5. Adicione os arquivos ao controle de versão:

```bash
git add .
```

6. Faça o primeiro commit:

```bash
git commit -m "Primeiro commit"
```

---

## Como criar o repositório no GitHub

1. Acesse [https://github.com](https://github.com)
2. Clique em **New repository**
3. Nomeie como `wenna`
4. Deixe **README** e **.gitignore** desmarcados se você já tiver localmente
5. Clique em **Create repository**

---

## Como ligar o repositório local ao GitHub

```bash
git remote add origin https://github.com/kevin-github-code/wenna.git
git branch -M main
git push -u origin main
```

⚠️ Se o repositório no GitHub já tiver conteúdo (ex: README), primeiro faça:

```bash
git pull origin main --allow-unrelated-histories
```

Resolva conflitos se houver:

```bash
git add <arquivos_resolvidos>
git commit -m "Resolve conflito"
```

Depois faça push normalmente:

```bash
git push -u origin main
```

---

## Comandos Git mais usados

| Comando                    | Descrição                               |
| -------------------------- | --------------------------------------- |
| `git status`               | Ver status do repositório               |
| `git add .`                | Adicionar todos os arquivos para commit |
| `git commit -m "mensagem"` | Criar commit com mensagem               |
| `git push`                 | Enviar commits para o GitHub            |
| `git pull`                 | Trazer alterações do remoto para local  |
| `git remote -v`            | Ver repositórios remotos ligados        |
| `git log --oneline`        | Ver histórico de commits                |

---

## Observações

* Use sempre `git pull` antes de começar a trabalhar, para não ter conflitos.
* Se for a primeira vez configurando o Git, defina seu nome e email global:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

* Para evitar digitar senha toda hora, considere usar **SSH** com GitHub.

---

## Licença

[Escolha a licença do seu projeto]
Ex: MIT License
