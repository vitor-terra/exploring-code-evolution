# Exploring code evolution

Neste exercício, iremos explorar a evolução de código em sistemas reais.

Iremos utilizar a ferramenta [GitEvo](https://github.com/andrehora/gitevo).
Essa ferramenta analisa a evolução de código em repositórios Git nas seguintes linguagens: Python, JavaScript, TypeScript e Java.

# Tarefa 1: Selecionar repositório a ser analisado

Primeiramente, selecione um repositório relevante na linguagem de sua preferência.
Você pode encontrar projetos interessantes nos links abaixo:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

# Tarefa 2: Instalar e rodar a ferramenta GitEvo

Instale a ferramenta [GitEvo](https://github.com/andrehora/gitevo) com seguinte comando:

```
pip install gitevo
```

Rode a ferramenta através com o seguinte comando, dependendo da linguagem do projeto que escolheu:

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

Por exemplo, para analisar o projeto Flask escrito em Python:

```
$ gitevo -r python https://github.com/pallets/flask
```
