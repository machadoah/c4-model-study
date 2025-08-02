# :books: C4 Model

A abordagem para descrever a arquitetura de software em diferentes níveis de detalhes.

## C4: 4 Níveis de Detalhe

![](https://c4model.com/images/c4-overview.png)

- **Contexto**: Visão mais alto nivel, mostrando como o sistema se encaixa no contexto mais amplo.
  - Fornece escopo e limites do sistema.
- **Container**: Detalha os principais containers do sistema, como aplicações e serviços.
  - Infraestrutura e implantação são consideradas.
- **Componente**: Foca nos componentes dentro de um container específico, como classes ou módulos.
  - **_Vale apena quando:_** Complexidade e criticidade alta.
- **Código**: O nível mais baixo, detalhando o código-fonte e as implementações específicas.
  - **_Vale apena quando:_** Complexidade e criticidade alta.

## Riscos -> Overengineering
- **Tempo e esforço**: Se a arquitetura for muito complexa, pode levar mais tempo para ser implementada documentada e mantida.
- **Falta de flexibilidade**: Se a arquitetura for muito rígida, pode ser difícil adaptá-la a novas necessidades ou mudanças no sistema.
- **Desatualização rápida**: Os dois últimos níveis do Modelo C4 (Componente e Código) podem se tornar obsoletos rapidamente, especialmente em sistemas ágeis onde as mudanças são frequentes.
