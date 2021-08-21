# Introdução ao BERT

![BERT](https://raw.githubusercontent.com/HAILab-PUCPR/introducao-bert/main/imagens/bert-google.jpg)

[Introdução BERT](https://github.com/HAILab-PUCPR/introducao-bert/blob/main/introducao-bert.ipynb):

Introdução sobre como usar o BERT para gerar *word embeddings* e *sentences embeddings*, incorporação de palavras e sentenças, que podem ser usadas em outras tarefas de PLN..

[Classificação com BERT](https://github.com/HAILab-PUCPR/introducao-bert/blob/main/classificacao-bert.ipynb):

Exemplo prático de como realizar uma classificação com o BERT, usando a classe **BertForSequenceClassification** da biblioteca Transformers do Hugging Faces. (Link para Colab: https://colab.research.google.com/drive/11f8yeYfJv2vQO7Pw4Z3j-GwDHwKlWiE5?usp=sharing)

*Em breve: exemplo com NER e BERT**

## Instalação local

1. Clone o repositório do GitHub
    
2. `pipenv install` dentro do diretório clonado (onde o Pipfile está)

3. Instale a versão correta do `torch` para o seu sistema (`torchvision` não necessário).

```
concha pipenv
python -m pip install torch === 1.3.1 -f https://download.pytorch.org/whl/torch_stable.html
```

4. Para executar os notebooks, basta iniciar seu notebook Jupyter, por exemplo,

```
pipenv run jupyter notebook
```

Ou acessar via Google Colab.
