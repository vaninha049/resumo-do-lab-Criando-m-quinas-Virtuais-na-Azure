# resumo-do-lab-Criando-m-quinas-Virtuais-na-Azure
## Criando máquinas Virtuais na Azure

## SLA de Máquinas Virtuais no Azure
O SLA (Service Level Agreement), ou Acordo de Nível de Serviço, é um compromisso formal da Microsoft em relação à disponibilidade dos serviços fornecidos no Azure. Para as Máquinas Virtuais (VMs), o SLA estabelece garantias específicas de uptime (tempo de atividade) com base na configuração da infraestrutura.

## Níveis de Garantia de SLA
Máquinas Virtuais Individuais com Disco Premium:
Garantia de 99,9% de disponibilidade quando a VM é configurada com discos gerenciados do tipo Premium SSD.

## Conjuntos de Disponibilidade (Availability Sets):
Garantia de 99,95% de disponibilidade ao distribuir VMs entre múltiplos domínios de falha e atualização dentro de um conjunto de disponibilidade.

## Zonas de Disponibilidade (Availability Zones):
Garantia de 99,99% de disponibilidade ao implantar VMs em diferentes zonas de disponibilidade dentro da mesma região.

## Impacto do SLA
Um SLA mais alto garante maior resiliência contra falhas e interrupções, sendo essencial para aplicações críticas.
É recomendável usar discos gerenciados Premium e configurar Availability Sets ou Availability Zones para maximizar a disponibilidade.
Considerações Importantes
O SLA cobre apenas problemas diretamente atribuíveis ao Azure. Interrupções causadas por erros de configuração do cliente não são incluídas.
Garantias de SLA podem variar com base no tipo de serviço ou configuração.

## Para mais detalhes, consulte a documentação oficial do Azure sobre SLA.

