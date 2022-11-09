# Stop-EC2-Lambda
Parar Instancias EC2 na AWC com uma função Lambda

1 - Criar uma Role ---> 

2 - Adicionar a Tag nas Instancias que deseja incluir no Schedule 
        Key: StartStart_lambda
        Value: True or False
        Obs: True significa que a instancia será desligada

3 - Adicionar a função Lambda ---> 

4 - Configurar o Schedule

5 - Testar!
