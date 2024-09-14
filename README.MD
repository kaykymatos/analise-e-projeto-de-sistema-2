# Find Opportunities

Find Opportunities é um sistema de gestão de currículos e vagas de emprego. Ele permite que profissionais se cadastrem, enviem seus currículos e sejam recomendados para vagas publicadas por empresas de forma automática, utilizando um algoritmo de matching. O sistema também possibilita que empresas publiquem vagas e encontrem profissionais adequados às suas necessidades de forma autônoma.

## Objetivo

O objetivo principal do sistema é facilitar o processo de recrutamento para empresas e aumentar a visibilidade dos profissionais em busca de recolocação no mercado de trabalho ou novas oportunidades. Ele automatiza a busca e sugestão de candidatos, reduzindo o tempo gasto pelas empresas e oferecendo maior agilidade no processo de seleção.

## Funcionalidades

### Para Profissionais
- **Cadastro Completo**: Permite cadastro detalhado de informações pessoais e profissionais (formação, experiência, habilidades técnicas, idiomas).
- **Área de Gerenciamento**: Visualização de vagas recomendadas, acompanhamento do status das candidaturas e personalização de preferências (faixa salarial, localidade, etc.).
- **Notificações de Vagas**: Notificação automática de vagas compatíveis via email ou SMS.
- **Filtros Avançados de Busca**: Permite busca de vagas utilizando filtros como localidade, experiência requerida, tipo de contrato e área de atuação.

### Para Empresas
- **Cadastro de Empresas**: Permite cadastro de empresas e criação de contas, com informações como razão social, CNPJ, setor e dados de contato.
- **Publicação de Vagas**: Criação de vagas detalhadas, especificando o perfil desejado do profissional, habilidades, experiência mínima, soft skills, faixa salarial, entre outros.
- **Sistema de Matching**: Algoritmo de matching que recomenda candidatos com base na correspondência entre currículos e requisitos das vagas.
- **Gerenciamento de Vagas e Candidatos**: Área de gerenciamento de vagas publicadas e candidatos recomendados.

### Para Administradores
- **Painel de Controle**: Gestão de usuários (profissionais e empresas), moderação de conteúdos e acompanhamento de métricas de performance.
- **Monitoramento e Segurança**: Monitoramento de interações, aplicação de penalidades e conformidade com a Lei Geral de Proteção de Dados (LGPD).

## Benefícios

- **Para Profissionais**: Maior visibilidade no mercado de trabalho, acesso a oportunidades compatíveis, e facilidade na gestão do currículo e busca de vagas.
- **Para Empresas**: Redução do tempo e esforço no processo de recrutamento e recebimento de candidatos mais qualificados.
- **Para a Agência**: Aumento da eficiência no processo de intermediação entre empresas e candidatos, com a possibilidade de atender um maior número de clientes.

## Tecnologias Utilizadas

- **Backend**: [C#]
- **Frontend**: [React]
- **Banco de Dados**: [MySQL]
- **Autenticação e Segurança**: Utilização de hashing para senhas e autenticação via email/senha.

## Requisitos Funcionais

- Cadastro de profissionais e empresas.
- Publicação e gerenciamento de vagas.
- Sistema de matching automático entre profissionais e vagas.
- Filtros avançados para busca de candidatos e vagas.
- Notificações automáticas para profissionais e empresas.
- Exportação de currículos para PDF ou CSV.
- Área administrativa para controle do sistema.

## Requisitos Não Funcionais

- **Desempenho**: O sistema deve processar consultas e matching em até 2 segundos.
- **Usabilidade**: Interface intuitiva e responsiva para dispositivos móveis e desktops.
- **Escalabilidade**: Suporte para até 10.000 empresas e 100.000 profissionais simultaneamente.
- **Segurança**: Conformidade com a LGPD e criptografia via HTTPS.
- **Disponibilidade**: 99,9% de uptime, acessível 24/7.
- **Backup e Recuperação**: Backup automático diário e recuperação de dados em caso de falha.

## Diagramas
# Diagrama de caso de uso
![caso_de_uso](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/CasoDeUso/caso_de_uso.png)

# Diagramas de atividade
![cadastro_de_funcionarios](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/Diagrama%20de%20Atividades/CadastroFuncionario/cadastro_funcion%C3%A1rio.png)

![cadastro_de_usuarios](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/Diagrama%20de%20Atividades/CadastroUsu%C3%A1rio/cadastro_usuario.png)

# Diagrama de classes
![diagrama_de_classes](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/DiagramaDeClasses/diagramadeclasses.png)

# Diagramas sequenciais
![cadastro_funcionario](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/DiagramaSequencial/Cadastro%20funcion%C3%A1rio/cadastro_funcion%C3%A1rio.png)

![cadastro_usuarios](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/DiagramaSequencial/CadastroUsuario/cadastro_usuario.png)

![confirmacao_emails](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/DiagramaSequencial/Confirma%C3%A7%C3%A3o%20email/confirma%C3%A7%C3%A3o_email.png)

![login](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/DiagramaSequencial/Login/login.png)

![upload de currículo](https://github.com/kaykymatos/analise-e-projeto-de-sistema-2/blob/main/ProjetoDesenvolvidoPeloGrupo/DiagramaSequencial/UploadCurr%C3%ADculo/upload_curr%C3%ADculo_usu%C3%A1rio.png)
