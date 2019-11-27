# Visão geral
### Processo que o novo sistema poderá apoiar
O sistema auxiliará na venda de pizzas e organização dos pedidos, agilizando o processo e criando uma redução no gastos da empresa com pessoal

### Objetivos
Criar um ambiente agradável e de fácil uso para o usuário evitando a necessidade de uma ligação para a pizzaria

### Necessidades
É necessário um serviço de hospedagem com recursos básicos para o desenvolvimento e teste. O mesmo ambiente poderá ser usado para produção visto que a ferramenta possuíra um código pequeno

### Restrições/limitações
A ferramenta web não disponibilizará uma maneira de efetuar pagamentos online. Mediante este problema que caso viesse a ser uma real necessidade do sistema, utilizaremos uma API do Pagseguro como solução

### Reuso e integração
O sistema utilizará um front-end que será integrado com o back-end através de uma API. Outra possível integração do sistema seria com o Pagseguro para fazer o pagamento dos pedidos feitos no sistema

### Informações
Os dados que o sistema irá manipular serão dados básicos do usuário, e dados, em alguns momentos, estáticos

### Não faz parte do escopo do projeto
*Gerenciamento de cadastros*: Não será necessário visando a UX do usuário <br />
*Financeiro*: Não será feito devido a falta de tempo <br />
*Relatórios*: Não serão implementados devido a falta de tempo <br />
*Estoque*: Não será implementado devido a falta de tempo <br />

# Escopo
### Público-alvo:
Empresa de pequeno porte que precisa de uma ferramenta web com o objetivo de disponibilizar praticidade para  pessoas sem tempo/não saibam cozinhar

### Quais são as necessidades de software da organização:
A necessidade decorre da perda de tempo/necessidade de uma atendente focada em registrar, organizar e entregar os pedidos para os pizzaiolo

### Quais são as soluções que a organização usa atualmente:
Sites básicos com o intuito de gerar um ligação
Aplicativos genéricos de pedido de comida
Sites sem uma real experiência do usuário pensada
Atendentes contratadas exclusivamente para os pedidos

*Pontos fortes*
- UX pensada para o usuário
- Economia
- Praticidade

*Pontos fracos*
- Necessidade de hospedagem

### O que poderia fazer com que a solução do seu time fosse diferenciada?
- Código compacto
- Time focado na UX
- Experiência na área

> Apresentação: https://docs.google.com/presentation/d/1yKc99tlytD_MTUzvTKIyAFOhxaMqcIhbVCkB6P_xGwo/edit?usp=sharing

# Viabilidade 

### Viabilidade organizacional
A ferramenta possui características já experienciada pelo time e o conhecimento do time é complementar para a conclusão da mesma.
Devido a alta demanda por processos informatizados a ferramenta se faz necessária tanto a organização quanto aos usuários

### Viabilidade técnica
O time ja possui experiência nas áreas e o devido conhecimento necessário para trabalhar com a tecnologias utilizadas, que a principio serão HTML, CSS, JavaScript, C#, MySQL, PHP, VueJS, Ruby, Capybara, Postman, Cucumber e Gherkin.  <br />
Não há necessidade de gastos visando a baixa necessidade de recursos do sistema e a existência de tecnologias gratuitas que facilitam a conclusão da mesma

### Viabilidade de cronograma
Dado os requisitos levantados e a ampla possibilidade de adequações sistema para conclusão do sistema, acredita-se que alguns atrasos não impactem diretamente na entrega final. O que torna a ferramenta viável quanto a entrega mediante o prazo

# Requisitos

### Requisitos funcionais
 - ~~**RF01**: `Importante` - Escolher combos~~ ***`Descartado`***
 - ~~**RF02**: `Importante` -Escolher quantidade de combos~~ ***`Descartado`***
 - ~~**RF03**: `Importante` -Escolher sabores dos combos~~ ***`Descartado`***
 - ~~**RF04**: `Importante` -Escolher adicionais para os combos~~ ***`Descartado`***
 - ~~**RF05**: `Essencial`  -Escolher quantidades de pizzas~~ ***`Descartado`***
 -   **RF06**: `Essencial`  -Escolher tamanho da pizza
 - ~~**RF07**: `Essencial`  -Escolher quantidade de sabores~~ ***`Descartado`***
 -   **RF08**: `Essencial`  -Escolher sabores da pizza
 - ~~**RF09**: `Essencial`  -Escolher adicionais da pizza~~ ***`Descartado`***
 - ~~**RF10**: `Essencial`  -Escolher quantidade de bebidas~~ ***`Descartado`***
 - ~~**RF11**: `Essencial`  -Escolher bebida~~ ***`Descartado`***
 -   **RF12**: `Essencial`  -Informar dados de pagamento
 -   **RF13**: `Essencial`  -Informar dados de entrega
 - ~~**RF14**: `Desejável`  -Efetuar pagamento~~ ***`Descartado`***
 -   **RF15**: `Essencial`  -Mostrar pedidos
 -   **RF16**: `Essencial`  -Mostrar dados da entrega
 - ~~**RF17**: `Importante` -Remover pedido~~ ***`Descartado`***

### Requisitos não funcionais
 -   **RNF01**: `Desejável`  - Site bonito
 -   **RNF02**: `Essencial`  - E-mail de confirmação de pedido para o cliente
 -   **RNF03**: `Importante` - Ter o site responsivo
 -   **RNF04**: `Desejável`  - Gerar pedido após pagamento
 - ~~**RNF05**: `Desejável`  - Site fluído~~ ***`Descartado`***

# Users stories e Personas

### Users stories(US)
- ~~`US1` - Como cliente José eu quero escolher entre combo ou pizza avulsa para iniciar meu pedido~~ ***`Descartado`***
- ~~`US2` - Como cliente José eu quero escolher a quantidade de pizzas para dar continuidade ao meu pedido~~ ***`Descartado`***
- `US3` - Como cliente José eu quero escolher o tamanho da pizza para dar continuidade ao meu pedido
- ~~`US4` - Como cliente José eu quero escolher a quantidade de sabores da pizza para meu pedido~~ ***`Descartado`***
- `US5` - Como cliente José eu quero escolher os sabores da pizza para dar continuidade ao meu pedido
- ~~`US6` - Como cliente José eu quero escolher os adicionais da pizza para dar continuidade ao meu pedido~~ ***`Descartado`***
- ~~`US7` - Como cliente José eu quero adicionar bebidas para dar continuidade ao meu pedido~~ ***`Descartado`***
- ~~`US8` - Como cliente José eu quero escolher um combo para dar continuidade ao meu pedido~~ ***`Descartado`***
- ~~`US9` - Como cliente José eu quero escolher a quantidade de combos para iniciar meu pedido~~ ***`Descartado`***
- `US10` - Como cliente José eu quero informar meus dados para finalizar meu pedido
- `US11` - Como usuário Corleone eu gostaria de visualizar os pedidos pendentes
- ~~`US12` - Como usuário Corleone eu gostaria de remover os pedidos concluídos~~ ***`Descartado`***

### Personas
**Nome**: *Jose Santos* <br />
**Escolaridade**: *PhD* <br />
**Idade**: *34* <br />
**Sexo**: *Masculino* <br />
**Família**: *Solteiro* <br />
**O que faz nas horas de lazer**: *Ver documentários* <br />
**Cargo/ocupação**: *Professor e pesquisador* <br />
**Quais são as responsabilidades da persona**: *Pedir uma pizza no site* <br />
**Onde ele busca informações?** *Em livros, sites e revistas* <br />
**Em quais redes sociais ele interage**: *Twitter* <br />
**Qual as dores da persona**: *Falta de tempo para cumprir com tarefas cotidianas*

**Nome**: *Corleone Fabbri* <br />
**Escolaridade**: *Ensino médio* <br />
**Idade**: *37* <br />
**Sexo**: *Masculino* <br />
**Família**: *Casado* <br />
**O que faz nas horas de lazer**: *Ficar com a família* <br />
**Cargo/ocupação**: *Pizzaiolo* <br />
**Quais são as responsabilidades da persona**: *Preparar pizzas, dar baixa no sistema e entregar com o endereço para o motoboy* <br />
**Onde ele busca informações?** *Internet* <br />
**Em quais redes sociais ele interage**: *Facebook, Instagram* <br />
**Qual as dores da persona**: *Problemas com a gestão de seu négocio que está iniciando* <br />

# Fluxograma de processos
## O fluxo do sistema de resume da seguinte maneira<br />
![Overview do fluxograma](/docs/images/fluxograma_processos.png)

## Pedido
### A primeira etapa do sistema é relacionada ao pedido<br />
![Overview do geração do pedido](/docs/images/pedido.png)

## Fazer Pedido <br />
### Um pedido se resume em escolher o tamanho da pizza e os sabores<br />
![Adicionar combo ao carrinho](/docs/images/fazer_pedido.png)

## Gerenciar carrinho <br />
### Após serem feitos os pedidos, os mesmos podem ser gerenciados no carrinho<br />
![Adicionar pizza avulsa ao carrinho](/docs/images/gerenciar_carrinho.png)

## Selecionar método de pagamento <br />
### Após confirmação dos pedido deve ser feito a seleção da forma de pagamento <br />
![Finalizar o pedido](/docs/images/selecionar_metodo_de_pagamento.png)

## Enviar e-mail
### Após a conclusão do pedido o sistema irá enviar um e-mail ao cliente<br />
![Confirmação do pedido](/docs/images/enviar_email.png)

## Gerenciar pedidos
### Após a conclusão do pedido, o mesmo também irá ser adicionado ao portal do dono da pizzaria o permitindo remove-lo após a conclusão do mesmo<br />
![Gerenciamento de pedido](/docs/images/gerenciar_pedido.png)

# Modelo lógico
![Adicionar combo ao carrinho](/docs/images/modelo_logico.png)

# Modelo físico

1. Cliente<br />

| Nome do campo | Tipo de dados |
| ---           | ---           |
| id            | int           |
| clientId      | int           |
| nome          | string        |
| cpf           | string        |
| endereco      | string        |
| telefone      | string        |
| email         | varchar       |
| ultimaCompra  | datetime      |
| dataInclusao  | datetime      |
| dataAlteracao | datetime      |
| dataExclusão  | datetime      |
| ativo         | bolean        |

2. Pedido<br />

| Nome do campo   | Tipo de dados |
| ---             | ---           |
| Id              | int           |
| PedidoId        | int           |
| cliente_Id      | int           |
| DataInclusao    | datetime      |
| DataAlteracao   | datetime      |
| DataExclusao    | datetime      |
| Ativo           | boolean       |
| Status          | int           |
| entrega_EntregaId | int         |
| pagamento_PagamentoId | int     |

3. Entrega<br />

| Nome do campo   | Tipo de dados |
| ---             | ---           |
| EntregaId       | int           |
| Cep             | string        |
| Rua             | string        |
| Numero          | string        |
| Nome            | string        |
| Email           | string        |
| Telefone        | string        |
| Complemento     | string        |

4. Item<br />

| Nome do campo   | Tipo de dados |
| ---             | ---           |
| ItemId          | int           |
| Tipo            | decimal       |
| Tamanho         | bigint        |
| Borda           | bigint        |
| Valor           | text          |
| Sabor           | decimal       |
| Pedido_Id       | bigint        |

5. Sabores<br />

| Nome do campo   | Tipo de dados |
| ---             | ---           |
| id              | int           |
| Nome            | string        |
| Quantidade      | int           |
| Item_ItemId     | int           |

6. Pagemento<br />

| Nome do campo   | Tipo de dados |
| ---             | ---           |
| PagamentoId     | int           |
| Total           | double        |
| Tipo            | string        |
| Bandeira        | string        |
| Metodo          | string        |
| troco           | double        |

# Estratégia de Teste
Testes funcionais foram realizados na aplicação para certificar que ela está apta a realizar as funções da qual foi desenvolvida para fazer.</br>

Na parte do BackEnd da aplicação, foram realizados testes sobre a API, garantido que suas chamadas, e seus endpoints estão satisfazendo os requisitos técnicos e funcionais da aplicação. Os recursos foram testados de forma isolada, visando garantir a funcionalidade de cada recurso por si só.</br>

No FrontEnd foram realizados testes integrados, para garantir os fluxos principais do seu início ao fim, de funcionamento da aplicação.

### Tecnologias utilizadas para teste:
JavaScript, Ruby, Capybara, Postman, Cucumber e Gherkin.

## Gerência de Requisitos:

### GRE1:
O escopo do projeto foi definido em conjunto entre o PO e Analista de Sistemas e o time de desenvolvimento, visando atender as necessidades de uma Pizzaria que tem como necessidade atender seus clientes de forma online, em que a interação humana com o usuário seja necessária apenas no processo de entrega do pedido.

### GRE2:
Os requisitos foram avaliados levando em consideração o prazo para entrega do projeto e os recursos disponíveis para a equipe, a equipe se comprometeu levando em consideração sua disponibilidade de equipamentos, seu conhecimento nas tecnologias necessárias para o comprometimento da meta e sua curva de aprendizagem nas mesmas, assim fixando uma quantidade de requisitos plausíveis para o produto sem correr o risco de comprometer a qualidade do produto final.

### GRE3:


### GRE4:
O projeto foi divido em pequenas entregas separadas por user stories, cada uma atende uma quantidade de requisitos pré-definidos. Essas user stories foram dividas pela equipe de desenvolvimento em Tarefas, quando todas as tarefas relacionadas a uma user storie eram concluídas, os testes relacionados eram executados e as regras de negócio e os requisitos eram dados como finalizados, ou tarefas de bug fix eram abertas e a user storie ficava definida como In Progress até a conclusão das correções necessárias, nessa etapa os requisitos são revistados e validados pelo Analista.

### GRE5:
Mudanças de requisitos técnicos podem ser levantadas pela equipe de desenvolvimento a qualquer momento, e a decisão de gerar novas Stories a partir delas ficam a cargo do Analista. Caso alguma regra de negócio seja alterada, o Analista precisa escrever novas Stories, e negociar com o time de desenvolvimento um momento para atendê-las.