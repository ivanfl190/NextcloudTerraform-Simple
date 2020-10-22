Pre requisitos: 
 A maquina precisa está atualizada.
 Docker precisa está instalado na maquina.

comando para inicializar o  yaml:
  docker stack deploy -c nc.yaml app

esperar ate finalizar.

Para acessar primeiramente deve se liberar portas necessarias no grupo de segurança da AWS.
  Portas a ser liberadas: 80 e 9000
 
 para acessar basta digitar o Endereço IPv4 público do AWS e em seguida adicionar a porta.
