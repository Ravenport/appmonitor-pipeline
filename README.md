# appmonitor-pipeline
at ci/cd Infnet

Importância do GIT
------------------

O git é uma ferramenta para versionamento de código que permite a entrega
contínua graças à versatilidade que oferece para que equipes possam trabalhar
em conjunto. 

As branches permitem que alterações sejam separadas e 
que um histórico organizado delas seja mantido. 

As tags, por sua vez, permitem gerar pontos imutáveis no histórico 
do projeto de forma que seja possível rastrear mudanças importantes.

ETAPAS
======

1 Etapa - Setup do Repositório
------------------------------

Eu fiz a criação do Repositório como solicitado usando o nome solicitado.

Após isso fiz a release na versão 0.1.0 como pedido no exercício.

2 Etapa - Pipeline de Integração Continua
-----------------------------------------

Eu criei o arquivo ci.yml como solicitado no exercício e adicionei os jobs
com os nomes pedidos no exercício e fazendo as funcionalidades solicitadas.

3 Etapa - Uso de Variáveis e Secrets
------------------------------------

Como pedido e evidenciado nas fotos e no repositório foram criadas as váriaveis
e secrets para uso dentro do workflow run-monitor.yml

4 Etapa - Monitoramento, Logs e Resumos Automatizados
-----------------------------------------------------

Como solicitado na etapa e também evidenciado nas fotos e no repositório foram
feitas as alterações solicitadas ao arquivo ci.yml

5 Etapa - Permissões e deploy com aprovação manual
--------------------------------------------------

Foi setado no ambiente "Production" a regra de segurança que impede que os jobs
relacionados ao ambiente sejam executados sem a altorização da pessoa selecionada
como reviewer na definição da regra. Foi criada também a várial PROD_DOMAIN que
foi usada como solicitada no job "deploy" no arquivo deploy.yml.
