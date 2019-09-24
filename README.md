# Visão geral
### Processo que o novo sistema poderá apoiar
O sistema auxiliará na venda de pizzas e organizaçãoo dos pedidos, agilizando o processo e criando uma redução no gastos da empresa com pessoal

### Objetivos
Criar um ambiente agradável e de fácil uso para o usuário evitando a necessidade de uma ligação para a pizzaria

### Necessidades
É necessário um serviço de hospedagem com recursos básicos para o desenvolvimento e teste. O mesmo ambiente poderá ser usado para produção visto que a ferramenta possuíra um código pequeno e funcionalidades que nao necessitam necessariamente de um banco de dados

### Restrições/limitações
A ferramenta web não disponibilizará uma maneira de efetuar pagamentos online. Mediante este problema que caso viesse a ser uma real necessidade do sistema, utilizaríamos uma API do Pagseguro como solução

### Reuso e integração
O sistema utilizará uma API do Google Maps para mostrar a localização da pizzaria visando facilitar a identificação da região em que se encontra a mesma
Outra possível integração do sistema seria com o Pagseguro para fazer o pagamento dos pedidos feitos no sistema

### Informações
Os dados que o sistema manipulará será dados básicos do usuário, e dados estáticos da pizzaria

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
O time ja possui experiência nas áreas e o devido conhecimento necessário para trabalhar com a tecnologias utilizadas, que a principio serão HTML, CSS, JavaScript, C#, MySQL, PHP <br />
Não há necessidade de gastos visando a baixa necessidade de recursos do sistema e a existência de tecnologias gratuitas que facilitam a conclusão da mesma

### Viabilidade de cronograma
Dado os requisitos levantados e a ampla possibilidade de adequações sistema para conclusão do sistema, acredita-se que alguns atrasos não impactem diretamente na entrega final. O que torna a ferramenta viável quanto a entrega mediante o prazo

# Requisitos

### Requisitos funcionais
 - **RF01**: `Importante` - Escolher combos
 - **RF02**: `Importante` - Escolher quantidade de combos
 - **RF03**: `Importante` - Escolher sabores dos combos
 - **RF04**: `Importante` - Escolher adicionais para os combos
 - **RF05**: `Essencial` - Escolher quantidades de pizzas
 - **RF06**: `Essencial` - Escolher tamanho da pizza
 - **RF07**: `Essencial` - Escolher quantidade de sabores
 - **RF08**: `Essencial` - Escolher sabores da pizza
 - **RF09**: `Essencial` - Escolher adicionais da pizza
 - **RF10**: `Essencial` - Escolher quantidade de bebidas
 - **RF11**: `Essencial` - Escolher bebida
 - **RF12**: `Essencial` - Informar dados de pagamento
 - **RF13**: `Essencial` - Informar dados de entrega
 - **RF14**: `Desejável` - Efetuar pagamento
 - **RF15**: `Essencial` - Mostrar pedidos
 - **RF16**: `Essencial` - Mostrar dados da entrega
 - **RF17**: `Importante` - Remover pedido


### Requisitos não funcionais
 - **RNF01**: `Desejável` - Site bonito e fluído
 - **RNF02**: `Essencial` - E-mail de confimação de pedido para o cliente
 - **RNF03**: `Importante` - Ter o site responsivo
 - **RNF04**: `Desejável` - Gerar pedido após pagamento

# Users stories e Personas

### Users stories(US)
- `US1` - Como cliente José eu quero escolher os sabores e os adicionais para fazer meu pedido
- `US2` - Como cliente José eu quero adicionar bebidas ao meu pedido para complementa-lo
- `US3` - Como cliente José eu quero escolher a quantidade de pizzas e o sabor de cada uma delas para adicionar ao meu pedido
- `US4` - Como cliente José eu quero informar meus dados para finalizar meu pedido
- `US5` - Como cliente José eu quero escolher o tamanho da pizza para meu pedido
- `US6` - Como cliente José eu quero escolher um combo e a quantidade de combos para iniciar meu pedido
- `US7` - Como usuário Corleone eu gostaria de visualizar os pedidos pendentes para faze-los

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
**Em quais redes sociais ele interage**: *Twiter* <br />
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
**Qual as dores da persona**: *Problemas com a gestão de seu négocio que esta iniciando* <br />

### [Fluxograma de processos](/docs/fluxograma_processos.md)

### [Trello](https://trello.com/b/oLR8NrvE/esii)