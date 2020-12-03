# Introdução ao BERT

![BERT](https://raw.githubusercontent.com/HAILab-PUCPR/introducao-bert/main/imagens/bert-google.jpg)

Introdução sobre como usar o BERT para gerar *word embeddings* e *sentences embeddings*, incorporação de palavras e sentenças, que podem ser usadas em outras tarefas de PLN..

## Instalação local

1. Clone o repositório do GitHub
    
2. `pipenv install` dentro do diretório clonado (onde o Pipfile está)

3. Instale a versão correta do `torch` para o seu sistema (`torchvision` não necessário).

```
concha pipenv
python -m pip install torch === 1.3.1 -f https://download.pytorch.org/whl/torch_stable.html
```

4. Para executar o notebook, basta iniciar seu notebook Jupyter, por exemplo,

```
pipenv run jupyter notebook
```
