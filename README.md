Pre requisitos: 
 A maquina precisa está atualizada.
 Docker precisa está instalado na maquina.
  Caso esteja usando o AWS as portas 80 e 9000 precisam estar liberadas no security group da AWS.
    Portas a serem liberadas: 80 e 9000

comando para inicializar o  yaml:
  docker stack deploy -c nc.yaml app


Para acessar deve se adicionar o endereço ip publico em seguida a porta.

 

