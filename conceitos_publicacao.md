# Publicar uma aplicação web
** Um servidor web
** Gratuito ou pago
## Requisitos a serem analisados
** Linguagem de programação suportadas (php, java, python, etc)
** Tipos de banco de dados suportados (mysql, postgree, mongodb)
** Quantidade de memória (Memória RAM)
** Quantidade de armazenamento (disco)
** Tipos de transferências de arquivos (FTP, SFTP, Github) 
** Largura de banda de rede (Quantidade de dados enviados para o servidor)
** Ssitema operacional (Linux ou Windowns)


# TIPOS DE SERVIDORES


## COMPARTILHADO
      Várias pessoas/empresas usam o mesmo servidor para criar diferentes sites/aplicações

      * Prós
            - mais barato
            - mais fácil de configurar (possui um painel de controle - Cpanel)
      * Contras
            - recursos limitados (não conseguimos aumentar recursis de memória, disco, banda e bancos)
            - Se algum site cair, cai todos os outros.

## SERVIDOR DEDICADO
      Um servirdor para cada cliente, cada servidor pode ter vários site de apenas 1 cliente.
      * Prós
            - servidor exclusivo;
            - aumentar/diminuir recursis conforme necessidade
      * Contras
            - necessário conhecimento em linux/windows para configurar. Não temos o painel de contrike.
            - aumenta controle da segurança do servidor.

## NUVEM (VMs) - Virtual Machines
      Permite criar máquinas que não existem no mundo real para isolar uma aplicação/site.
      * Prós
            - permite testar coisas antes de colocar em produção
            - mais fácil de gerenciar.
            - bem mais fácil de gerenciar.
            - paga-se por uso de recurso.
            - se um vm parar de funcionar, somente ela é afetada.
      * Contras
            - bem mais caro que o servidor dedicado.

## CONTAINERS
      Permite criar um ambiente menor do que uma vm e distribuir os processos.
      * Prós
            - permite recuperação mais rápida.
            - normalmente mais barto do que a vm.
      * Contras
            - mais complexo de gerenciar.
            - mais conhecimento em infraestrutura de rede.
