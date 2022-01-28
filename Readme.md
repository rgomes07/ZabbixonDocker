Estrutura dos Containeres Docker para ambiente ZABBIX:

- Os containeres estão standalone;
- Seguir sequência dos containeres;
- Especificar montagem do volume para os dados do banco;
- Observar o tempo de 2 minutos na estrutura do container web;
- Verificar se os containeres estão UP após deploy;
- Edite o host chamado Zabbix Server.
- Altere o endereço IP de 127.0.0.1 para o endereço IP do contêiner de agente Zabbix.
- Clique no botão Atualizar.


 "docker inspect container-name |grep -i IP"