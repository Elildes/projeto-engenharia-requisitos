# Gerenciamento de Requisitos

## GestorPsi-app - Gerenciamento para clínica psicológica (sistema)

### Descrição do contexto/problema

Este sistema está sendo desenvolvido no contexto da disciplina Engenharia de Requisitos da Universidade Federal do Rio Grande do Norte, com propósito de fazer parte da avaliação final da disciplina.

Este sistema é uma solução que irá propiciar aos profissionais da psicologia maior agilidade e controle das suas atividades no dia a dia, pois irá manter toda a sua documentação de trabalho de forma digital, permitindo trabalhar com prontuários, anotações, relatórios e documentos de maneira rápida e segura, sem a perda de dados, e uma maior legibilidade das informações.

### Padrões estabelecidos para o desenvolvimento

**Padrão de Diretórios** - Estruturas estabelecidas onde os **artefatos** somente poderão ser criados

- [Requisitos](documentacao/requisitos/): Artefatos que farão a descrição das funcionalidades e qualidades do sistema.
- [Código Fonte](codificacao/br/imd/ufrn/gestorpsi): Artefatos referentes a codificação do sistema.

**Padrão para criar os Artefatos de Requisitos** - Cada artefato de requisito corresponde a apenas uma funcionalidade ou qualidade do sistema, que segue o **padrão de nomenclatura estabelecido** e **uma estrutura de diretório com nomes significativos** para organizar esses artefatos dentro do diretótio padrão de [Requisitos](documentacao/requisitos/).

- A **estrutura de diretórios** que vai armazenar esses artefatos de requisitos criados e mantidos no diretorio [Requisitos](documentacao/requisitos/), segue a esta classificação primária:

    **a)** Para as necessidades do **domínio** do problema, os artefatos de requisitos estão organizados no diretório [Requisitos Funcionais](documentacao/requisitos/funcionais/);

    **b)** Os requisitos **funcionais** estão agrupados em **módulos/pacotes** para agrupar funcionalidades relacionadas e para melhor clareza e organização. **Ex.:** Os requisitos módulo/pacote **PCT01 - Módulo de Acesso** estão organizados no diretório [Requisitos Funcionais - PCT01](documentacao/requisitos/funcionais/pct01);

    **c)** Para as características de **qualidade** do sistema, os artefatos de requisitos estão organizados no diretório [Requisitos Não-Funcionais](documentacao/requisitos/naofuncionais/);

    **d)** Para as **regras de negócio** (requisitos de domínio) do sistema, os artefatos de requisitos estão organizados no diretório [Regras de Negócio](documentacao/requisitos/regrasdenegocio/);

    **e)** Para as necessidades determinadas por **leis e regulamentos**, os artefatos estão organizados no diretório [Requisitos Legais](documentacao/requisitos/legais/).

    **f)** Para os materiais de **referências**, que identifica todas as fontes de informação consideradas na identificação dos requisitos, os artefatos estão organizados no diretório [Documentação de Referências](documentacao/referencias/).

    **Obs.:** para fins didáticos, adicionamos aos documentos de referências o arquivo [ER - Documento de Requisitos](documentacao/referencias/ER_Documento_de_Requisitos.pdf/), que foi o principal documento que deu origem a todos os requisitos deste reposiório.

    **g)** Para os **diagramas**, para melhor entendimento dos requisitos, os artefatos estão organizados no diretório [Diagramas](documentacao/diagramas/).

- **Padrão de nomenclatura**
  
  Foi utilizado na padronização das nomenclaturas dos requisitos a seguinte convenção, que foi utilizada com base no padrão que contam na maioria dos trabalhos acadêmicos pesquisados.
  - **PCT.** Este prefixo identifica o agrupamento dos artefatos de requisitos funcionais e não funcionais que irá descrever os módulos. Os dois números que está logo após este prefixo identifica o número do módulo;
  - **RF.** Este prefixo identifica os artefatos de requisitos funcionais que irá descrever as especificações de requisitos. Os dois primeiros números que está logo após este prefixo identifica o número do módulo que o requisito pertence e os dois últimos números, identifica o número do requisito;
  - **RNF.** Este prefixo identifica os artefatos de requisitos não-funcionais que irá descrever as características de qualidades do sistema. Os dois primeiros números que está logo após este prefixo identifica o número do módulo que o requisito pertence e os dois últimos números, identifica o número do requisito;
  - **RN.** Este prefixo identifica os artefatos referentes as regras de negócios (requisitos de domínio) que descreve termos que se referem às expressões das políticas, restrições, condições e decisões do sistema. Os dois primeiros números que está logo após este prefixo identifica o número da regra de negócio;
  - **RL.** Este prefixo identifica os artefatos de cunho legais e regulatórios determinados por leis e regulamentos que irá descrever as especificações legais;
  - Ao final de cada arquivo de cada requisito, utilizamos a extensão **.md** para permitir a utilização da [Linguagem Markdown](https://www.markdownguide.org/) para formatar os artefatos de requisitos, para possibilitar criar artefatos organizados e de estrutura consistente. Ex.: **RF.01.01.md**, **RNF.02.md**, **RN.01.md**, **RL.01.md**.

- **Protótipo**

  Os requisitos foram desenvolvidos e implementados, resultando em um protótipo criado com a plataforma FIGMA.

  [Link do Protótipo GestorPsi](https://www.figma.com/community/file/1465765143520414305)

## ÍNDICE

Para melhorar facilidade de navegação, organização de conteúdo, melhora na compreensão, referenciar de maneira fácil cada requisito e para posterior atualização e revisões dos requisitos, este índice abaixo permite que os requisitos sejam rapidamente locanizadas e revisadas.

[**Requisitos Funcionais**](documentacao/requisitos/funcionais/)

[PCT01: Módulo de Acesso](documentacao/requisitos/funcionais/pct01)

[RF.01.01.md – Cadastro de Usuários](documentacao/requisitos/funcionais/pct01/RF.01.01.md)  
[RF.01.02.md – Fazer Login](documentacao/requisitos/funcionais/pct01/RF.01.02.md)  
[RF.01.03.md – Recuperação de Senha](documentacao/requisitos/funcionais/pct01/RF.01.03.md)  

[PCT02: Módulo Gestão de Pacientes](documentacao/requisitos/funcionais/pct02)

[RF.02.01.md – Cadastrar Pacientes](documentacao/requisitos/funcionais/pct02/RF.02.01.md)  
[RF.02.02.md – Visualizar Perfil do Paciente](documentacao/requisitos/funcionais/pct02/RF.02.02.md)  
[RF.02.03.md – Atualização das Informações do Paciente](documentacao/requisitos/funcionais/pct02/RF.02.03.md)  

[PCT03: Módulo Prontuário e Anotação do Paciente](documentacao/requisitos/funcionais/pct03)

[RF.03.01.md – Cadastro de Prontuário](documentacao/requisitos/funcionais/pct03/RF.03.01.md)  
[RF.03.02.md – Adicionar Anotações Clínicas](documentacao/requisitos/funcionais/pct03/RF.03.02.md)  
[RF.03.03.md – Anexar Documentos ao Prontuário](documentacao/requisitos/funcionais/pct03/RF.03.03.md)  
[RF.03.04.md – Gestão de Histórico](documentacao/requisitos/funcionais/pct03/RF.03.04.md)  

[PCT04: Módulo de Relatório](documentacao/requisitos/funcionais/pct04)

[RF.04.01.md – Gerar Relatório de Atendimento](documentacao/requisitos/funcionais/pct04/RF.04.01.md)  
[RF.04.02.md – Histórico de Atendimentos](documentacao/requisitos/funcionais/pct04/RF.04.02.md)  
[RF.04.03.md – Exportar Relatório](documentacao/requisitos/funcionais/pct04/RF.04.03.md)  

[PCT05: Módulo de Agendamentos](documentacao/requisitos/funcionais/pct05)

[RF.05.01.md – Definir Consultas](documentacao/requisitos/funcionais/pct05/RF.05.01.md)  
[RF.05.02.md – Agendar Consultas](documentacao/requisitos/funcionais/pct05/RF.05.02.md)  
[RF.05.03.md – Notificação de Consulta](documentacao/requisitos/funcionais/pct05/RF.05.03.md)  
[RF.05.04.md – Reagendar Consulta](documentacao/requisitos/funcionais/pct05/RF.05.04.md)  
[RF.05.05.md – Cancelar Consulta](documentacao/requisitos/funcionais/pct05/RF.05.05.md)  

[PCT06: Módulo Anamnese Digital](documentacao/requisitos/funcionais/pct06)

[RF.06.01.md – Modelos de Anamnese](documentacao/requisitos/funcionais/pct06/RF.06.01.md)  
[RF.06.02.md – Arquivar Anamnese](documentacao/requisitos/funcionais/pct06/RF.06.02.md)  
[RF.06.03.md – Revisar e Atualizar Anamnese](documentacao/requisitos/funcionais/pct06/RF.06.03.md)  

[PCT07: Módulo de Administração](documentacao/requisitos/funcionais/pct07)

[RF.07.01.md - Gerenciar Usuários](documentacao/requisitos/funcionais/pct07/RF.07.01.md)  
[RF.07.02.md – Gerenciar Permissões](documentacao/requisitos/funcionais/pct07/RF.07.02.md)  

[**Requisitos Não-Funcionais**](documentacao/requisitos/naofuncionais/)

[RNF.01.md – Segurança](documentacao/requisitos/naofuncionais/RNF.01.md)  
[RNF.02.md – Confidencialidade](documentacao/requisitos/naofuncionais/RNF.02.md)  
[RNF.03.md – Desempenho](documentacao/requisitos/naofuncionais/RNF.03.md)  
[RNF.04.md – Privacidade](documentacao/requisitos/naofuncionais/RNF.04.md)  
[RNF.05.md – Usabilidade](documentacao/requisitos/naofuncionais/RNF.05.md)  
[RNF.06.md – Manutenabilidade](documentacao/requisitos/naofuncionais/RNF.06.md)  
[RNF.07.md – Integridade](documentacao/requisitos/naofuncionais/RNF.07.md)  

[**Regras de Negócio**](documentacao/requisitos/regrasdenegocio/)

[RN.01.md - Definição de Acesso e Permissões](documentacao/requisitos/regrasdenegocio/RN.01.md)  
[RN.02.md - Gestão de Pacientes](documentacao/requisitos/regrasdenegocio/RN.02.md)  
[RN.03.md - Relatórios e Análises](documentacao/requisitos/regrasdenegocio/RN.03.md)  
[RN.04.md - Agendamentos e Notificações](documentacao/requisitos/regrasdenegocio/RN.04.md)  
[RN.05.md - Gestão de Prontuários e Anotações Clínicas](documentacao/requisitos/regrasdenegocio/RN.05.md)  
[RN.06.md - Protocolos de Segurança](documentacao/requisitos/regrasdenegocio/RN.06.md)  

[**Requisitos Legais**](documentacao/requisitos/legais/)

[RL.01.md – Conformidade com a LGPD](documentacao/requisitos/legais/RL.01.md)  
[RL.02.md – Adesão aos Padrões de HL7/FHIR](documentacao/requisitos/legais/RL.02.md)  

## Glossário de Termos Técnicos

Nesta seção apresentamos este glossário que aborda os termos técnicos principais e suas definições no contexto do sistema para o qual os requisitos foram definidos, facilitando o entendimento e implementação das funcionalidades descritas.

**Anamnese**: Processo de coleta de informações pessoais e históricas de um paciente, para entender o quadro clínico e condições de saúde, utilizado como base para diagnóstico e tratamento.

**Cadastro de Usuários:** Funcionalidade que permite o registro das informações básicas de um usuário no sistema, como nome, endereço e dados de contato. No contexto do sistema, abrange psicólogos e clínicas que podem incluir especialidades.

**Consulta**: Encontro programado entre um paciente e um profissional de saúde, como um psicólogo, para avaliação, diagnóstico ou tratamento.

**Histórico de Atendimentos**: Registro de todas as consultas, atendimentos e anotações relacionadas a um paciente. Esse histórico pode ser acessado e revisado pelos profissionais para garantir continuidade no tratamento.

**Login**: Processo de acesso ao sistema em que o usuário insere um nome de usuário e senha para autenticação. Esse recurso permite garantir que apenas usuários autorizados acessem o sistema.

**Módulo**: Segmento do software com funcionalidades específicas. Cada módulo é responsável por um conjunto de funções no sistema, como o Módulo de Acesso, Módulo de Gestão de Pacientes, entre outros.

**Notificação de Consulta**: Aviso enviado pelo sistema aos profissionais e/ou pacientes para lembrar sobre consultas agendadas. Pode ser feito via SMS, e-mail ou notificação push.

**Permissões de Acesso**: Configurações que determinam o que cada tipo de usuário (psicólogo, administrador, paciente) pode acessar e modificar no sistema. Controla o nível de acesso de cada perfil para garantir segurança e privacidade.

**Prontuário Eletrônico**: Registro digital das informações clínicas e de atendimento de um paciente, que inclui dados como histórico de consultas, anotações clínicas e documentos anexados (exames e relatórios médicos).

**Relatório de Atendimento**: Documento gerado pelo sistema que resume informações e detalhes sobre os atendimentos de um paciente. Pode ser exportado em diferentes formatos, como PDF e CSV.

**Requisitos Funcionais**: Especificações que definem o que o sistema deve fazer, detalhando as funcionalidades necessárias para atender as necessidades dos usuários e do negócio.

**Reagendamento**: Funcionalidade que permite alterar a data e horário de uma consulta previamente agendada, garantindo flexibilidade para o paciente e o profissional.
SMS: Serviço de Mensagens Curtas (Short Message Service) utilizado pelo sistema para enviar notificações ou informações rápidas via celular.

**Usuário Administrador**: Perfil com permissões ampliadas para gerenciar contas de usuários, permissões de acesso, e configurar funcionalidades do sistema.
