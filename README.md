# Workshop Python para a classificacao de textos

## 1) Resumo:

**Objetivo:** o curso ensina Python básico orientado a classificação de textos. 
**Material:** o cuso utilzará dados jornalísticos e de redes sociais. **Resultados:** Ao final do curso, os pesquisadores conhecerão as operações do Python, as principais plataformas para a execução dos códigos, bem como serão capazes de gerar e importar bases de dados, classificar frases e textos, bem como extrair informações por meio wordcloud, gráficos simples e estatísticas básicas, utilizando poucas linhas de código.

## 2) Tópicos do curso:

* <b>Ambiente para Data Science: Google Collaboratory</b>
    * criação de células;
    * importação de arquivos;
    * clonando o repositório do curso

* <b>Dominando Python: introdução</b>
    * Conhecendo a linguagem 
    * Comandos básicos
    * Funções de convesão, arredondamento
    * Trabalhando com variáveis
    * Trabalhando com listas
    * Operações matemáticas
    * Trabalhando com strings
    * Operações com strings

* <b>Análise de dados com Python</b>
    * Conhecendo o pacote Pandas
    * Escrevendo Dataframes
    * Salvar um Dataframe em csv, xlsx, txt
    * Como importar uma tabela usando Pandas?
    * Inspecionando Dataframes
    * Percorrendo linhas de um Dataframe

* <b>Classificação e análise de dados textuais com Regex</b>
    * Estudos de caso com dados jurídicos e de redes sociais
        * Contagem de palavras
        * Identificação de dados numéricos
        * Classificação de postagens
        * Word Cloud
        * Estatísticas básicas
        * Gráficos
        * Salvando a base
        
## 3) Como clonar o repositório no Google Colab?

## Acesse o Google Drive

Abra o seu Google Drive e faça login na sua conta.

## Abra o Google Colab

Acesse o Google Colab e crie um novo notebook.

## Monte o Google Drive

Execute a célula abaixo:

```python
from google.colab import drive
drive.mount('/content/gdrive')
```

## Crie uma pasta para os arquivos do curso

```bash
!mkdir "(2026) workshop python para cientistas politicos"
```

## Acesse a pasta criada

```python
%cd /content/gdrive/MyDrive/"(2026) workshop python para cientistas politicos"
```

## Clone os arquivos do curso

```bash
!git clone https://github.com/andregerardi/workshop-python-para-classificacao-textual
```

## Concluído

O ambiente está pronto para utilização.
