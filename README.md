# Exploring code evolution

Neste exercício, iremos explorar a evolução de código em sistemas reais.

Iremos utilizar a ferramenta [GitEvo](https://github.com/andrehora/gitevo).
Essa ferramenta analisa a evolução de código em repositórios Git nas seguintes linguagens: Python, JavaScript, TypeScript e Java.

# Passo 1: Selecionar repositório a ser analisado

Selecione um repositório relevante na linguagem de sua preferência (Python, JavaScript, TypeScript ou Java).
Você pode encontrar projetos interessantes nos links abaixo:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

# Passo 2: Instalar e rodar a ferramenta GitEvo

Instale a ferramenta [GitEvo](https://github.com/andrehora/gitevo) com o comando:

```
pip install gitevo
```

Rode a ferramenta no repositório selecionado através do seguinte comando (dependendo da linguagem do projeto que escolheu):

```shell
# Python
$ gitevo -r python <git_url>

# JavaScript
$ gitevo -r js <git_url>

# TypeScript
$ gitevo -r ts <git_url>

# Java
$ gitevo -r java <git_url>
```

Onde `<git_url>` é URL do repositório a ser analisado.
Por exemplo, para analisar o projeto Flask escrito em Python:

```
$ gitevo -r python https://github.com/pallets/flask
```

# Passo 3: Explorar a evolução de código (arquivo `index.html`)

Ao rodar a ferramenta [GitEvo](https://github.com/andrehora/gitevo), um arquivo `index.html` é gerado com diversos gráficos de evolução de código.
Abra o arquivo `index.html` e observe com atenção os três primeiros gráficos: 

1. Lines of code (LOC)
2. Files
3. LOC / files

# Exercício: Explicar os três gráficos de evolução de código

Explique com suas palavras os gráficos (1) Lines of code (LOC), (2) Files e (3) LOC / files.
Detalhe a evolução nos últimos anos e se as curvas estão de acordo com boas práticas de manutenção e evolução.

### Submissão: (1) index.html, (2) link e (3) explicação

Para responder este exercício, você deve fazer um `fork` deste repositório e apresentar as três informações abaixo:

1. Adicione arquivo gerado `index.html` no seu fork.

2. Link do repositório selecionado: <LINK_DO_SEU_REPOSITORIO_AQUI>
  
3. Explicação: <SUA_EXPLICACAO_AQUI>





