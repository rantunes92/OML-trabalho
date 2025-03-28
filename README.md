# OML-trabalho-master
Trabalho realizado por Ricardo Antunes 
Módulo: Operacionalização de Machine Learning

1º Passo: Criar um repositório no Github
2º Passo: Adicionar a pasta OML-trabalho-master ao explorer do Visual Studio Code

3º Passo: Criar um ambiente para o projecto
  Vou usar o ficheiro conda.YAML

  Para criar e activar o ambiente usei os seguintes comandos:
    conda env create -f conda.yaml
    conda activate OML-trabalho-master
    
4º Passo: Conectar o VS Code ao repositório de GitHub
  Instalar a extensão "GitHub Pull Requests"
  Logar na conta do GitHub na extensão

5º Passo: Correr o rumos_bank_lending_predicyion-MLflow.ipynb
  usar o comando `mlflow ui --backend-store-uri ./mlruns`
  verificar no broswer `http://127.0.0.1:5000` se ficou correcto
  
  o Random Forest foi o melhor modelo, por uma questão de poupança de tempo, os próximos notebooks vão usar apenas este modelo
