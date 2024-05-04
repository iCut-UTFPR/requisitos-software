
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

## 1. Introdução

***1.1.  Nome do Grupo***

Nome do Grupo: **iCut**
Integrantes: Fraga013, gbrochi, GustavoSilva2005, l0destarz, ThalesGranja

***1.2.  Nome do Sistema***

iCut

***1.3.  Propósito do Sistema***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela iCut, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema iCut é facilitar o processo de agendar um serviço em barbearias.

Aqui está o link para uma apresentação mais detalhada dos Requisitos de Usuário e Requisitos de Sistema: https://padlet.com/gsilva2005/kanban-h8jiv6iru3n1xb6z

***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes... 

***1.3. Descrição dos usuários***

Os usuários finais serão os clientes da barbearia que vamos fornecer o sistema de controle de corte e estoque da mesma.

Aqui está o link para a apresentação dos potênciais clientes e barbeiro: https://encurtador.com.br/afjMZ

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

| Nível de prioridade | Descrição |
| --- | ---|
| 1 | Alto |
| 2 | Médio |
| 3 | Baixo |

| Requisitos Funcionais | Descrição | Prioridade |
| --- | --- | --- |
| `[RF01]` | O software deve permitir que o cliente faça o seu próprio cadastro no aplicativo. | 1 |
| `[RF02]` | O software deve permitir que o cliente marque um horário. | 1 |
| `[RF03]` | O software deve permitir que o cliente escolha um barbeiro de sua preferência para prestar o serviço escolhido. | 1 |
| `[RF04]` | O software deve permitir que o cliente veja os itens disponíveis para venda (objetos). | 2 |
| `[RF05]` | O software deve permitir que o cliente veja o catálogo de serviços da barbearia. | 1 |
| `[RF06]` | O software deve permitir que o barbeiro veja a quantidade de horas que o mesmo já trabalhou. | 3 |
| `[RF07]` | O software deve permitir que o cliente escolha qual tema de aplicativo ele quer (claro/escuro). | 3 |
| `[RF08]` | O software deve permitir que o cliente consulte o horário marcado (ver serviço, dia, horário e barbeiro). | 1 |
| `[RF09]` | O software deve permitir que o barbeiro consiga gerenciar seus horários (consegue bloquear horários da sua agenda para clientes não pegarem). | 1 |
| `[RF10]` | O software deve permitir que o barbeiro consiga gerenciar horário para clientes já cadastrados. | 1 |
| `[RF11]` | O software deve permitir que o cliente faça uma avaliação após o serviço contratado(avaliação estrela e box de mensagem). | 1 |
| `[RF11]` | O software deve permitir que o cliente assinale a opção de fazer uma avaliação anônima. | 1 |
| `[RF12]` | O software deve permitir que o cliente edite seu horário previamente marcado(cancelar/remarcar reserva). | 1 |
| `[RF13]` | O software deve permitir que o barbeiro edite o status dos clientes para (inativo e viajante). | 2 |
| `[RF14]` | O software deve permitir que o cliente escolha entre pagar pelo app ou não. | 1 |


| Requisitos Não Funcionais | Descrição | Prioridade |
| --- | --- | --- |
| `[RNF01]` | Os usuários devme ser capazes de utilizar todas as funcionalidades do sistema após 2 minutos de uso. Deverá ser algo intuitivo para ele não perder tanto tempo. | 1 |
| `[RNF02]` | O usuário deve ser capaz de finalizar o agendamento de um corte com menos de 5 cliques no aplicativo. | 2 |
| `[RNF03]` | A ajuda online do sistema deve ser algo claro na interface, sem precisar de muito esforço para acha-lá. | 1 |
| `[RNF04]` | O sistema deverá processar 100 requisições a cada segundo (visando maior velocidade na confirmação do agendamento). | 3 |
| `[RNF05]` | O instalador do sistema não deve ser superior a 150MB. | 1 |
| `[RNF06]` | O sistema deve suportar 20 usuários concorrentemente. | 2 |
| `[RNF07]` | O sistema deve ficar no ar 95% do tempo. | 1 |
| `[RNF08]` | Se o sistema falhar, os dados do usuário devem ser recuperados pelo sistema. | 1 |
| `[RNF09]` | O sistema deve ser operacionalizado no Android e IOS. | 1 |
| `[RNF10]` | Todos os documentos entregues devem seguir o cabeçalho e rodapé definido pela empresa. | 1 |
| `[RNF11]` | O sistema deve ser implementado na linguagem React Native/JavaScript. | 2 |
| `[RNF12]` | O sistema deve interagir com o sistema do banco para pagamento dos usuários. | 1 |
| `[RNF13]` | O sistema não deve revelar aos operadores nenhuma informação pessoal dos clientes. | 1 |
| `[RNF14]` | O acesso aos dados deve ser protegido. | 1 |
| `[RNF15]` | O sistema deve colocar automaticamente o status do cliente "em análise" depois de não frequentar a barbearia por 3 meses. | 1 |
| `[RNF16]` | O sistema deve mudar o status do cliente para ativo assim que ele marcar um serviço (com excessão do status "viajante"). | 1 |
| `[RNF17]` | O sistema deve ter uma função de status de cliente como: "ativo", "inativo", "em análise" e "viajante". | 1 |
| `[RNF18]` | O sistema deve armazenar o histórico de cada cliente baseado no cadastro. | 1 |
| `[RNF19]` | O sistema deve enviar uma notificação no dia seguinte para o cliente dar um feedback do serviço. | 2 |
| `[RNF20]` | O sistema deve enviar uma mensagem automática para o cliente no dia de seu corte, para relembrar do horário e serviço marcado. Se e somente se o cliente assinalou que gostaria de receber esse lembrete. | 1 |
| `[RNF21]` | O sistema só deve permitir o cadastro do cliente caso a idade dele seja acima ou igual a 14 anos, salvo as exceções. | 1 |
| `[RNF22]` | O sistema deve enviar uma mensagem, já definida, automaticamente para o cliente que entrar em status "em análise". | 2 |
| `[RNF23]` | O sistema deve gerar um QR code e um código copia e cola para o pagamento dentro do app. | 1 |


***2.2. Entrevista***

Peguntas para o roteiro de entrevista: https://github.com/iCut-UTFPR/requisitos-software/blob/main/Perguntas%20sobre%20o%20software%20de%20barbearia.txt


***2.3. Protótipos***

*<Link para a pasta com os protótipos.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
