# Stop-EC2-Lambda
Parar Instâncias EC2 na AWS com uma função Lambda

1 - Criar uma Role ---> [role-iam](https://github.com/Bruna0092/Stop-EC2-Lambda/blob/ab05e1ff0bc189c2ab841ba2f2000efb4c6879b9/role-iam)

2 - Adicionar a Tag nas Instâncias que deseja incluir no Schedule #IMPORTANTE
        Key: StartStart_lambda
        Value: True or False
        Obs: True significa que a instância será desligada

3 - Adicionar a função Lambda ---> [Code](https://github.com/Bruna0092/Stop-EC2-Lambda/blob/ab05e1ff0bc189c2ab841ba2f2000efb4c6879b9/funcao-lamda-stop-ec2)

4 - Configurar o Schedule

5 - Testar!
