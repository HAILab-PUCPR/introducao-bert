# Introdução ao BERT

Introdução sobre como usar o BERT para inferência.

## Instalação local

1. Clone o repositório do GitHub
    
2. `pipenv install` dentro do diretório clonado (onde o Pipfile está)

3. Instale a versão correta do `torch` para o seu sistema (`torchvision` não necessário).

```
concha pipenv
python -m pip install torch === 1.3.1 -f https://download.pytorch.org/whl/torch_stable.html
```

4. Para executar o notebook, basta iniciar seu notebook Jupyter, por exemplo,

pipenv run jupyter notebook
