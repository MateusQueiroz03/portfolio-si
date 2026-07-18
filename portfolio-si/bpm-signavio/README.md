# Modelação de Processo de Negócio em BPMN

**Cadeira:** Digitalização de Processos de Negócio (Mestrado em Engenharia Informática, ramo SI)
**Tipo de trabalho:** Projeto de grupo (5 elementos)
**Ferramenta:** Signavio

## Objetivo

Modelação em notação BPMN de um processo de gestão de sinistros de uma seguradora (danos causados por tempestade), desde a receção da participação do sinistro até ao fecho do caso, com recurso a pools e lanes para representar os diferentes intervenientes (Seguradora, Cliente, Perito Externo).

## Descrição do processo modelado

O processo cobre: registo do sinistro, verificação de cobertura da apólice, atribuição de número de caso e de perito, receção assíncrona de documentação (fotos e orçamentos) por parte do cliente, envio ao perito para decisão, tratamento de cancelamento a qualquer momento do processo, notificação do cliente do desfecho e, quando aplicável, transferência bancária, terminando no fecho do caso.

Foram aplicados gateways exclusivos (decisão de cobertura, decisão do perito) e paralelos (pedido simultâneo de documentação ao cliente e atribuição ao perito; notificação do cliente e pagamento em simultâneo), bem como eventos de mensagem intermédios para modelar a espera assíncrona por documentação e a possibilidade de cancelamento a qualquer momento.

## A minha contribuição

O grupo trabalhou de forma colaborativa na definição da lógica do processo; contribuí para a discussão e desenho da solução (identificação dos gateways, tratamento do cancelamento assíncrono e da receção faseada de documentação). A modelação direta na ferramenta Signavio foi realizada por outro elemento do grupo.

## Conceitos aplicados

BPMN · Modelação de Processos · Pools e Lanes · Gateways paralelos/exclusivos · Eventos de mensagem · Signavio
