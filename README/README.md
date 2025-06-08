# Como criar os arquivos com Python, MKDocs e plugins utilizando integração e entrega contínua com Git Actions

## Python

- PASSO_1: Verifique se tem o Python instalado

``` shell
python --version
```

``` shell
pip --version
```

OBS: Caso mostre a versão do Python é só prosseguir com os passos seguintes, caso não tenha pode baixar em https://www.python.org/downloads/

![alt text](image.png)

![alt text](image-1.png)

- Marque a opção "Add Python to PATH"
- Clique em "Install Now"

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

- PASSO_2: Crie um ambiente virtual do Python

python3 -m venv env

- PASSO_3: Ative o ambiente virtual

source ./env/bin/activate

- PASSO_4: Instale as dependências

pip3 install -r requirements.txt

- PASSO_5: Inicie o servidor

mkdocs serve

- PASSO_6: Faça o Deploy

mkdocs gh-deploy

## VSCode para os passos 2 e 3 acima

- Clicar F1 ou Crtl+SHIFT+P

- Digitar envirement

- Aguardar a criação do ambiente virtual do Python

![alt text](image-6.png)

![alt text](image-7.png)

![alt text](image-8.png)

![alt text](image-9.png)

![alt text](image-10.png)

## GitHub



## GitHub Desktop

> https://desktop.github.com/download

![alt text](image-11.png)

![alt text](image-12.png)

![alt text](image-13.png)

![alt text](image-14.png)

![alt text](image-15.png)

![alt text](image-16.png)

![alt text](image-17.png)

![alt text](image-18.png)

## MKDocs




Bibliografia:

> https://www.python.org/downloads

> https://github.com/Insper

> https://dev.to/ifeanyichima/github-actions-example-29pj









































