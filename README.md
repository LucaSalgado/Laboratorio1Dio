# Laboratorio1Dio
Laboratório sobre machine learning no Azure

## Criando um workspace do Azure Machine Learning
- Acessando o portal do [Azure](https://portal.azure.com)
- Selecionamos a opção: **+ Create a resource**
- Então escolhemos: **Azure Machine Learning**
- Preenchemos as informações sobre o workspace
- Após criado o workspace nós devemos selecionar: **Launch studio**

## Usando machine learning automatizado para treinar um modelo
- Começamos selecionando **ML Automatizado**
- Selecionamos **"Novo Trabalho de ML Automatizado"**
- Então configuramos o tipo de machine learning será utilizado e o database para o treinamento
- Criamos um database a partir de um arquivo da web
- E configuramos uma machine learning para executar um regressão sobre o database
- Após o envio de trabalho e é executado automaticamente

## Analise do melhor modelo
- Na seção de **Visão Geral** é possível ver as informações sobre o algoritmo executado
- Ao selecionar o algoritmo nós somos levados a uma página de **Visão Geral** da execução do algoritmo
- Na opção **Métricas** é possível ver o desenpenho do modelo criado

## Implantar e testar o modelo
- Na aba **Modelo** nós podemos selecionar a opção **Deploy** para implantar o modelo treinado
- Após selecionar o tipo de implantação, devemos preencher os dados sobre a execução do modelo
- Ao fim da implantação nós temos acesso ao modelo treinado.
