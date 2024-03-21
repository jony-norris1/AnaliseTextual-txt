# AnáliseTextual-txt

Este repositório contém um conjunto de funções em Python para análise de texto. Essas funções podem ser úteis para extrair insights e realizar diversas operações em documentos de texto.

## Funcionalidades

- **Número de Palavras**: Calcula o número total de palavras no texto, incluindo palavras repetidas.
- **Número de Palavras Distintas**: Conta o número de palavras únicas no texto.
- **Número de Linhas**: Calcula o número total de linhas no texto.
- **Frequência das Palavras**: Calcula a frequência de cada palavra no texto.
- **Imprimir uma Linha Específica**: Permite ao usuário imprimir uma linha específica do texto.
- **Buscar Primeira Ocorrência**: Busca e imprime a linha em que uma palavra ocorre pela primeira vez no texto.
- **Substituir Palavra**: Substitui todas as ocorrências de uma palavra por outra no texto e salva o resultado em um arquivo.
- **Abrir Outro Livro**: Permite ao usuário abrir outro arquivo de texto para análise.
- **Gerar Nuvem de Palavras (Bônus)**: Gera uma nuvem de palavras a partir do texto.

## Testando o programa

Para testar o programa, utilizarei livros em formato .txt disponíveis no Projeto Gutenberg (https://www.gutenberg.org/). Para executar o seu programa utilizarei o comando `python ep.py` no terminal (prompt de comandos). Como os arquivos desse site estão com codificação utf8, recomendo utilizar a opção `encoding='utf-8-sig'` da função `open` para abrir o arquivo para leitura ou escrita.

## Como Usar

1. Clone o repositório em seu ambiente local.
2. Certifique-se de ter as bibliotecas Python necessárias instaladas (`collections`, `re`, `wordcloud` e `matplotlib`).
3. Execute o arquivo `analise_textual.py`.
4. Siga as instruções do menu interativo para utilizar as diferentes funcionalidades.

## Ambiente Compartilhado

Você também pode acessar um ambiente compartilhado no Google Colab:

https://colab.research.google.com/drive/1A5OifRYQPyJKOZRF5\_BlLuT-9Yg7t2kn?usp=sharing

## Referências

- [Exemplo de Nuvem de Palavras](https://link-para-exemplo.com)
- [Documentação do Python para collections.Counter](https://docs.python.org/3/library/collections.html#collections.Counter)
- [Documentação do Python para re](https://docs.python.org/3/library/re.html)
- [Página inicial da biblioteca Word Cloud](https://github.com/amueller/word_cloud)
- [Documentação do Matplotlib](https://matplotlib.org/stable/contents.html)

Este README fornece uma visão geral das funcionalidades do repositório e instruções básicas de uso. 
