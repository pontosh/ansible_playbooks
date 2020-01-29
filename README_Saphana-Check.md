# ansible_playbooks
Playbooks de Ansible para rodar a ferramenta da SAP saphana-checks

Pre-requisito : Ferramenta saphana-check devidamente baixado. ex. saphana-checks-1911.0-1.b309_gec1027d5.tgz
Este playbook do ansible irá executar o check de configuração de S.O. e mostrar os acertos de parametrização (sysctl, kernel parameters, limits, etc) para melhor execução do banco de dados Hana.
O arquivo de saida deve ser gravado na "maquina" que está executando as playbook em /home/meu_usuario/{{inventory_hostname}}_hana_check.txt.
OBS : Substituir LISTA_DE_HOSTS pelo inventario do ansible hosts adequado ao seu cenario.
e substituir o "meu_usuario" pelo usuario que está rodando o playbook.
