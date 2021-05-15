 Esse projeto foi produzindo apenas para fins de aprendizado.
**<p>Pre requisitos:</p>**

 -> A maquina precisa está atualizada.
 Docker precisa está instalado na maquina.
 
  Caso esteja usando o AWS algumas portas precisam estar liberadas no security group da AWS.
  
    --Portas à serem liberadas: 80 e 9000

**<p> Comando para inicializar o  yaml: </p>**   
   
   - docker stack deploy -c nc.yaml app


Para acessar,na caixa de URL deve se adicionar o endereço ip publico em seguida a porta. 
