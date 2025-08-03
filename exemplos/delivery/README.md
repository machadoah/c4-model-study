# MyFood - Delivery System

- Aplicação de Delivery de comida
- Interface Web para o restaurante gerenciar cardápios e pedidos
- App Mobile para os clientes e entregadores
- Possuir uma única API para conversar com o WebApp e o App Mobile
- A cada atualização de status dos pedidos, notificar dispositivos via push notification
- Utilizar Firebase Cloud Messaging para enviar notificações
- Integração para pagemento com o Mercado Pago
- Para mensageria, utilizarmos o RabbitMQ
- Ter apenas um banco de dados relacional (PostgreSQL)
- Manter cardápios e pedidos em cache com Redis

A arquitetura do sistema de delivery de comida é baseada no Modelo C4, que divide a arquitetura em quatro níveis: Contexto, Contêiner, Componente e Código. A seguir, apresentamos uma visão geral do sistema utilizando o Modelo C4.

- [Contexto](contexto.puml)
- [Contêiner](container.puml)
- [Componente](componente.puml)
- [Código](codigo.puml)

## Referência

- [C4 Model](https://c4model.com/)
- [C4 Model - Criando diagramas de Arquitetura de Software na PRÁTICA](https://youtu.be/iWkXd0RJ2FA?si=Ebn06Fri3nsRK-pF)