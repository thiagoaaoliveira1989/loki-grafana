# RODE O COMANDO

```
docker-compose up -d

```

## APOS INSTALAÇÃO DO CONTAINER DOCKER

1 - ABRE O CONTAINER VERIFIQUE SE TODOS OS SERVIÇOS ESTAO RODANDO / E ABRA O GRAFANA QUE ESTA RODANDO EM http://localhost:3200
2 - VÁ EM CONFIGURAÇÕES / DATASOURCE / ESCOLHA O LOKI
3 - NA URL DO HTTP COLOQUE http://loki:3100 / ROLE ATE O FINAL DA PAGINA E CLICK NO BOTÃO _SAVE & TESTE_
4 - PARA VISUALIZAR OS LOGS VA AGORA EM EXPLORE NO MENU DE NAVEGAÇÃO
5 - ESCOLHA A LABEL QUE DESEJA FILTRAR E CLICK EM RUN QUERY SE TIVER ALGUM LOG REFERENTE A LABEL QUE ESCOLHEU ELA DEVE APARECER.
