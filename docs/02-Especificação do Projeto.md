# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários. 

## Personas

| ![mulher 35 anos](https://github.com/DevosAlliance/Agendamento/assets/111004815/0ef5e1dd-7bc7-4953-af7a-cb59ff1dff53) | <h2 align="right"><b>Carla Soares</b></h2></br></br></br> <p align="left">Idade: 35 anos <br/><br/> Ocupação: Empresa Prestadora de Serviços. |
| --- | --- |
| Motivações <ul><li>Carla é proprietária de um salão de beleza de médio porte e está em busca de uma solução que facilite a marcação de horários para seus clientes. Ela deseja um aplicativo que ofereça uma página personalizada para seu salão, onde possa exibir informações sobre os serviços, disponibilidade de horários e preços. Além disso, ela quer uma plataforma que permita receber os pagamentos antecipados para evitar cancelamentos de última hora.</li></ul> | Frustrações <br/> <ul><li>Carla já tentou usar outros aplicativos de agendamento, mas enfrentou dificuldades com a personalização das páginas e a falta de integração com sistemas de pagamento. Ela também teve problemas com notificações automáticas que não foram entregues aos clientes, resultando em faltas e atrasos.</ul> |
| ![homem 28 anos](https://github.com/DevosAlliance/Agendamento/assets/111004815/4a2c1f4c-0f07-44c7-b07f-6d04f8072bfb) | <h2 align="right"><b>Lucas Silva</b></h2></br></br></br> <p align="left">Idade: 28 anos <br/><br/> Ocupação: Profissional Autônomo. <br/>|
| Motivações <ul><li>Lucas é um personal trainer que trabalha por conta própria e está procurando uma maneira eficiente de agendar as sessões de treinamento com seus clientes. Ele deseja um aplicativo que o ajude a organizar seus horários e que ofereça a possibilidade de receber feedback e avaliações dos clientes para melhorar sua reputação profissional.</li></ul> | Frustrações <br/> <ul><li> Lucas já tentou utilizar planilhas e aplicativos genéricos de calendário, mas eles não atendiam suas necessidades específicas como profissional autônomo. Ele também encontrou dificuldades para receber pagamentos de forma antecipada, o que resultou em algumas faltas de clientes.</ul> |
| ![mulher 30 anos](https://github.com/DevosAlliance/Agendamento/assets/111004815/c8af415a-f016-49cb-be46-5d7257259741) | <h2 align="right"><b>Isabela Rodrigues</b></h2></br></br></br> <p align="left">Idade: 30 anos <br/><br/> Ocupação: Cliente Individual</p> |
| Motivações <ul><li>Isabela é uma profissional com uma agenda agitada e está sempre buscando maneiras de otimizar seu tempo. Ela precisa agendar consultas médicas, sessões de fisioterapia e aulas de idiomas, além de reservar ingressos para eventos culturais. Ela deseja um aplicativo que reúna todas essas possibilidades em uma única plataforma, com lembretes automáticos para evitar esquecimentos.</li></ul> | Frustrações <br/> <ul><li>Isabela já enfrentou dificuldades para encontrar informações atualizadas sobre horários disponíveis em outros aplicativos e sites de empresas. Além disso, algumas vezes teve problemas para realizar pagamentos online de forma segura, o que a deixou receosa em usar determinados serviços.</ul> |
| ![homem 40 anos](https://github.com/DevosAlliance/Agendamento/assets/111004815/9e77780d-4f38-49d5-bfaf-648e46cf90aa) | <h2 align="right"><b>Rafael Almeida</b></h2></br></br></br> <p align="left">Idade: 40 anos <br/><br/> Ocupação: Estabelecimento Comercial</p> |
| Motivações <ul><li>Rafael é gerente de um restaurante movimentado e precisa gerenciar as reservas de mesas para o almoço e jantar. Ele procura uma solução que permita acompanhar as reservas em tempo real, com a possibilidade de receber feedback dos clientes e oferecer promoções especiais para atrair mais reservas durante horários menos concorridos.</li></ul> | Frustrações <br/> <ul><li>Rafael já tentou utilizar sistemas de reservas em papel e em outros aplicativos, mas enfrentou problemas de overbooking e dificuldades para gerenciar as reservas com precisão. Ele também teve experiências negativas com aplicativos que não ofereciam um suporte ao cliente adequado quando surgiam problemas técnicos.</ul> |
| ![homem 32 anos](https://github.com/DevosAlliance/Agendamento/assets/111004815/2fbcebae-b308-4c52-bac0-5e179a19c9b7) | <h2 align="right"><b>André Oliveira</b></h2></br></br></br> <p align="left">Idade: 32 anos <br/><br/> Ocupação: Cliente com Mão de Obra Remota.</p> |
| Motivações <ul><li>André é dono de uma empresa de entregas e precisa coordenar os horários de sua equipe de entregadores. Ele busca um aplicativo que permita agendar rotas de forma eficiente, otimizando o tempo de seus funcionários e melhorando a qualidade do serviço prestado aos clientes.</li></ul> | Frustrações <br/> <ul><li>André já tentou utilizar aplicativos de mapas e rotas, mas eles não ofereciam recursos específicos para agendamento de mão de obra remota. Ele também teve dificuldades para integrar o sistema de pagamento com os entregadores, o que causou atrasos nos pagamentos.</ul> |
| ![Gabriel Fiuza](https://github.com/DevosAlliance/Agendamento/assets/114194318/e702d486-561a-44af-8eb6-f83e81fe8a75) | <h2 align="right"><b>Gabriel Fiuza</b></h2></br></br></br> <p align="left">Idade: 25 anos <br/><br/> Ocupação: Barbeiro.<br/>Gabriel tem uma barbearia e utiliza um aplicativo genérico para agendamento.</p>|
| Motivações <ul><li>Gabriel gostaria de visualizar (dashboard) e emitir relatórios para mensurar a sua produtividade em um aplicativo de reserva de horário para seu serviço. E ainda poder receber pagamentos de forma antecipada para as reservas realizadas.</li></ul> | Frustrações <br/> <ul><li>Gabriel utiliza um aplicativo que realiza agendamentos mas não contém um dashboard e não recebe pagamentos</ul> |


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` | PARA ... `MOTIVO/VALOR` |
|----------------------|----------------------------------|------------------------|
| Carla Soares         | Um aplicativo com página personalizada para meu salão de beleza, exibindo informações sobre serviços, horários e preços | Facilitar a marcação de horários para meus clientes e oferecer atendimento personalizado |
| Carla Soares         | Receber pagamentos antecipados para evitar cancelamentos de última hora | Diminuir o número de faltas e otimizar a agenda do salão |
| Lucas Silva          | Um aplicativo que organize meus horários e permita receber feedback dos clientes | Melhorar minha reputação profissional e oferecer um serviço eficiente |
| Lucas Silva          | Receber pagamentos antecipados pelas sessões de treinamento | Evitar faltas de clientes e garantir minha renda |
| Isabela Rodrigues    | Um aplicativo que reúna agendamento de consultas médicas, fisioterapia, aulas de idiomas e reserva de eventos | Otimizar meu tempo e evitar esquecimentos |
| Isabela Rodrigues    | Informações atualizadas sobre horários disponíveis e método seguro para pagamentos | Tornar o processo de agendamento mais confiável e prático |
| Rafael Almeida       | Acompanhar reservas em tempo real e receber feedback dos clientes | Melhorar o atendimento e atrair mais reservas em horários menos concorridos |
| Rafael Almeida       | Evitar problemas de overbooking e gerenciar reservas com precisão | Garantir um fluxo adequado de clientes no restaurante |
| André Oliveira       | Agendar rotas de forma eficiente e otimizar o tempo dos entregadores | Melhorar a qualidade do serviço prestado aos clientes |
| André Oliveira       | Facilitar a integração do sistema de pagamento com os entregadores | Evitar atrasos nos pagamentos e garantir a satisfação da equipe |
| Gabriel Fiuza        | Um aplicativo de reserva de horário com dashboard e relatórios de produtividade | Ter melhor controle sobre o negócio e identificar oportunidades de melhoria |
| Gabriel Fiuza        | Receber pagamentos antecipados para as reservas | Garantir comprometimento dos clientes e reduzir o número de faltas |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID | Descrição do Requisito | Prioridade |
| --- | --- | --- |
| RF-01 | O aplicativo deve permitir o cadastro de uma página personalizada para um serviço. | ALTA |
| RF-02 | O aplicativo deve permitir o agendamento de horário na página do serviço. | ALTA |
| RF-03 | O aplicativo deve permitir que os clientes façam pagamentos antecipados para suas reservas. | ALTA |
| RF-04 | O aplicativo deve enviar notificações sobre seus agendamentos. | BAIXA |
| RF-05 | O aplicativo deve permitir o acompanhamento das reservas em tempo real. | ALTA |
| RF-06 | O aplicativo deve permitir a criação de promoções. | MÉDIA |
| RF-07 | O aplicativo deve agendar e gerar rotas para serviços de entrega. | ALTA |
| RF-08 | O aplicativo deve exibir um dashboard. | ALTA |
| RF-09 | O aplicativo deve emitir relatórios. | ALTA |


### Requisitos não Funcionais

| ID | Descrição do Requisito | Prioridade |
| --- | --- | --- |
| RNF-01 | O sistema deve ser fácil de usar e intuitivo para todos os usuários, independentemente de sua experiência com tecnologia. | ALTA |
| RNF-02 | O sistema deve ter desempenho rápido e responsivo, garantindo uma experiência fluída para os usuários. | ALTA |
| RNF-03 | A segurança dos dados dos clientes deve ser garantida, protegendo informações pessoais e de pagamento. | ALTA |
| RNF-04 | O sistema deve estar disponível em múltiplas plataformas, como smartphones, tablets e computadores. | ALTA |
| RNF-05 | O sistema deve oferecer suporte ao cliente eficiente para resolver problemas técnicos e questões relacionadas ao serviço. | ALTA |
| RNF-06 | O sistema de pagamento integrado deve ser seguro e confiável, garantindo que transações sejam realizadas corretamente. | ALTA |
| RNF-07 | O sistema deve ter uma interface amigável e atraente para os usuários, tornando a experiência de uso mais agradável. | ALTA |


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
| 01 | O sistema de pagamento integrado ao aplicativo deve utilizar provedores de pagamento aprovados e seguros. |
| 02 | O aplicativo deve estar em conformidade com as leis e regulamentações de proteção de dados e privacidade do país onde será utilizado.|
| 03 | O aplicativo deve ser testado rigorosamente antes do lançamento para garantir sua estabilidade e segurança. |
| 04 | Todas as informações e dados dos clientes devem ser tratados de forma confidencial e não devem ser compartilhados com terceiros sem autorização prévia. |
| 05 | O aplicativo deve ser escalável, permitindo futuras melhorias e atualizações conforme necessário. |
| 06 | O aplicativo deve ser hospedado em servidores confiáveis e com alta disponibilidade para garantir o acesso contínuo dos usuários. |
| 07 | Todas as comunicações entre o aplicativo e os servidores devem ser criptografadas para garantir a segurança das informações transmitidas. |


## Diagrama de Casos de Uso

![Diagrama de casos de uso]()
