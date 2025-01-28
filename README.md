![291798620-ae517df4-87d4-4b9a-8e98-3a653266aef4](https://github.com/user-attachments/assets/07e74d57-349c-4328-bbcd-ce9c99c903a6)


---


<h1>Requisitos de Software</h1>


<h2>ContratAe - Sistema de Recrutamento</h2>


<small>Versão 1.0</small>


---


## Histórico de revisões


|    Data    | Versão |           Descrição           |      Autor       |
| :--------: | :----: | :---------------------------: | :--------------: |
| 22/01/2025 |  1.0   |     Criação do documento      |    João Vittor   |
| 22/01/2025 |  1.0   |     Criação do documento      |    Kauã Victor   |
| 22/01/2025 |  1.0   |     Criação do documento      |    Lucas Kaique  |
| 22/01/2025 |  1.0   |     Criação do documento      |    Silas Leão    |


---


## Sumário


- [Capa](#capa)
  - [Histórico de revisões](#histórico-de-revisões)
  - [Sumário](#sumário)
- [Introdução](#introdução)
  - [Definições, Acrônimos e Abreviações](#definições-acrônimos-e-abreviações)
- [Usuários identificados](#usuários-identificados)
- [Requisitos funcionais](#requisitos-funcionais)
  - [Usuário Comum](#usuário-comum)
  - [Usuário Candidato](#usuário-candidato)
  - [Usuário Recrutador](#usuário-recrutador)
  - [Usuário Empresa](#usuário-empresa)
  - [Administrador do sistema](#administrador-do-sistema)
- [Requisitos não-funcionais](#requisitos-não-funcionais)
  - [Disponibilidade](#disponibilidade)
  - [Privacidade e segurança](#privacidade-e-segurança)
  - [Usabilidade](#usabilidade)
  - [Interoperabilidade](#interoperabilidade)
  - [Implementação](#implementação)
  - [Implantação](#implantação)

---

# Introdução

O objetivo deste documento é apresentar os requisitos de software do produto **ContratAe - Sistema de Recrutamento**

## Definições, Acrônimos e Abreviações

Esta subseção fornece as definições de todos os termos, acrônimos e abreviações necessárias à adequada interpretação do Documento de Requisitos.

- Identificação dos requisitos: por convenção, a referência a requisitos é feita através do tipo de requisito. Para o **Requisito Funcional** é colocado um indentificador de usuário:

  O identificador dos requisitos é conforme abaixo:
  
  `[IDENTIFICADOR DO TIPO DE USUÀRIO - IDENTIFICADOR DO TIPO DE REQUISITO]`
  - C-RF – Requisito Funcional do usuário Candidato
  - R-RF – Requisito Funcional do usuário Recrutador
  - E-RF – Requisito Funcional do usuário Empresa
  - U-RF – Requisito Funcional dos usuários com funcionalidades em comum
  - A-RF – Requisito Funcional do usuário Administrador

  `[IDENTIFICADOR DO TIPO DE REQUISITO]`
  - RNF – Requisito Não-Funcional

  O identificador do requisito será uma sequência numérica para cada grupo de requisito, tornando a sequencia única em cada grupo.

  **Exemplo**: C-RF0001, C-RF0002, R-RF0001, RNF0001

# Usuários identificados

Os seguintes usuários foram identificados para o sistema:

- Usuário do sistema
  - Usuários comuns
    - Usuário Candidato
    - Usuário Recrutador 
    - Usuário Empresa
  - Administrador do sistema

# Requisitos funcionais

Os requisitos funcionais são descritos a seguir. 

## Usuário comum 

- **[U-RF001]** - Como usuário comum, gostaria de poder me cadastrar no sistema.
- **[U-RF002]** - Como usuário comum, gostaria de definir meu tipo de usuário do sistema, se serei candidato, recrutador ou empresa. 
- **[U-RF003]** - Como usuário comum, gostaria que minha senha fosse criptografada, para que eu possa ter uma experiência mais segura. A troca de senha somente poderá ser realizada por meio de um e-mail de confirmação para acesso a uma página de troca de senha.
- **[U-RF004]** - Como usuário comum, gostaria de poder alterar a minha senha, para que eu possa ter uma experiência mais segura. A alteração de senha somente poderá ser realizada por meio de um e-mail de confirmação para acesso a uma página de alteração de senha.
- **[U-RF005]** - Como usuário comum, gostaria de poder alterar o meu e-mail, para que eu possa ter uma experiência mais segura. A alteração de e-mail somente poderá ser realizada por meio de um e-mail de confirmação para acesso a uma página de alteração de e-mail.
- **[U-RF006]** - Como usuário comum, gostaria de poder ativar acesso por dois fatores, para que eu possa ter uma experiência mais segura.
- **[U-RF007]** - Como usuário comum, gostaria de reportar problemas no sistema, para que eu possa ajudar a melhorar a experiência dos usuários.
- **[U-RF008]** - Como usuário comum, gostaria de verificar quais as regras de privacidade e uso de dados de maneira resumida e simplificada, para que eu possa ter uma experiência mais segura. As regras de privacidade e uso de dados também devem ser apresentadas em uma página de termos de uso e política de privacidade, que deve ser acessível a partir do rodapé do site, a partir da página de cadastro e da página de regras simplificadas.
- **[U-RF009]** - Como usuário comum, gostaria de receber notificações sobre manutenções agendadas no sistema, para que eu possa ter uma experiência mais segura e atualizada.

## Usuário candidato

- **[C-RF001]** - Como candidato, gostaria de cadastrar minhas informações profissionais para me candidatar para vagas, como habilidades, experiências, objetivos, formação acadêmica, idiomas e cursos.
- **[C-RF002]** - Como candidato, gostaria de me candidatar em uma ou mais vagas disponíveis no sistema, tornando meu currículo visível para o recrutador da vaga. 
- **[C-RF003]** - Como candidato, gostaria de atualizar minhas informações profissionais, cadastradas no sistema.
- **[C-RF004]** - Como candidato, gostaria de acompanhar os status das minhas candidaturas.
- **[C-RF005]** - Como candidato, gostaria de cancelar uma candidatura em que me candidatei anteriormente.
- **[C-RF006]** - Como candidato, gostaria de realizar buscas por vagas através de palavras-chaves e aplicação de filtros como, localidade, nível de experiência e empresas parceiras. 
- **[C-RF007]** - Como candidato, gostaria de receber email com novas vagas que combinam com minhas características profissionais.
- **[C-RF008]** - Como candidato, gostaria de uma funcionalidade para denunciar vagas que aparentam ser falsas, como forma de melhorar o ecossistema da aplicação para todos.
- **[C-RF009]** - Como candidato, gostaria de assinar um plano premium onde eu possa receber feedbacks personalizados e programas de capacitação de empresas parceiras do sistema.

## Usuário recrutador 

- **[R-RF001]** - Como recrutador, gostaria de cadastrar minhas informações profissionais, como empresa que trabalho.
- **[R-RF002]** - Como recrutador, gostaria de atualizar minhas informações pessoais e profissionais, cadastradas no sistema.
- **[R-RF003]** - Como recrutador, preciso ser capaz de anunciar vagas de emprego em um “post”, detalhando função, nível de experiência e remuneração.
- **[R-RF004]** - Como recrutador, preciso de uma funcionalidade para pesquisar candidatos a partir de palavras-chave, podendo-as identificar nome, cargo ou título.
- **[R-RF005]** - Como recrutador, preciso ter acesso ao perfil de um candidato, informando sua descrição, nome, experiências prévias e meios de contato.
- **[R-RF006]** - Como recrutador, devo ter a capacidade de editar informações sobre uma vaga que postei, caso haja alguma mudança como salário, período de trabalho ou carga horária por exemplo.
- **[R-RF007]** - Como recrutador, devo ter autoridade de excluir vagas de emprego que postei anteriormente a qualquer momento, tornando-a indisponível.

## Usuário empresa

- **[E-RF001]** - Como Empresa, preciso ter um cadastro com o nome, CNPJ, endereço, telefones, País.
- **[E-RF002]** - Como Empresa, gostaria de atualizar minhas informações cadastrais do sistema.
- **[E-RF003]** - Como Empresa, preciso ter como postar programas de treinamento no sistema para capacitar os candidatos que assinam o plano premium.
- **[E-RF004]** - Como Empresa, preciso ter como excluir programas ofertados por mim.
- **[E-RF005]** - Como empresa, gostaria de notificar candidatos sobre o status dos programas a qual eles estão inscritos.

## Administrador do sistema

- **[A-RF001]** - Como administrador, gostaria de realizar o gerenciamento do sistema.
- **[A-RF002]** - Como administrador, gostaria de realizar o gerenciamento de usuários.
- **[A-RF003]** - Como administrador, preciso ter autoridade total no sistema para ser capaz de apagar vagas falsas que foram reportadas(após análise), candidatos ausentes por um período de tempo estendido, empresas que cancelaram a parceria e recrutadores.
- **[A-RF004]** - Como administrador, gostaria de oferecer aos clientes a possibilidade de realizar o login com o Google, para que eles possam ter uma experiência mais rápida e segura.
- **[A-RF005]** - Como administrador, gostaria que os usuários fossem comunicados sobre as atualizações do sistema, para que eles possam ter uma experiência mais segura e atualizada.

# Requisitos não-funcionais

## Disponibilidade

- **[RNF001]** - O sistema deve ser desenvolvido para executar em todos os navegadores web.
- **[RNF002]** - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, 365 dias por ano.
- **[RNF003]** - O sistema deve ser desenvolvido de forma que possa ser escalável, ou seja, deve ser possível aumentar a capacidade de armazenamento de dados e de processamento de requisições sem que haja perda de desempenho.

## Privacidade e segurança

- **[RNF004]** - O sistema deve ser desenvolvido de forma que os dados dos clientes sejam protegidos e não sejam acessíveis por terceiros.
- **[RNF005]** - O sistema deve atender aos requisitos de privacidade da LGPD (Lei Geral de Proteção de Dados).
- **[RNF006]** - O sistema deve usar criptografia SHA-512 para proteger as informações dos usuários.

## Usabilidade
 
- **[RNF007]** - O sistema deve ser desenvolvido de forma que seja fácil de usar e de fácil aprendizado, de forma que os usuários não precisem de treinamento para utilizá-lo.
- **[RNF008]** - O sistema deve ser desenvolvido de forma que possa ser acessado por pessoas com deficiência visual, auditiva e física.

## Interoperabilidade

- **[RNF009]** - O sistema deve ser desenvolvido de forma que possa ser integrado com o firebase do Google para autenticação de usuários.
- **[RNF010]** - O sistema deve ser desenvolvido de forma que possa ser integrado com a API de pagamentos da ASAAS para assinatura dos planos oferecidos pela plataforma.

## Implementação

- **[RNF011]** - O sistema deve ser desenvolvido usando o framework Angular no Front - End, fornecendo uma arquitetura escalável.
- **[RNF012]** - O sistema deve ser desenvolvido usando Spring Boot com Java no Back - End, fornecendo uma arquitetura escalável e um ecosistema rico.
- **[RNF013]** - O sistema deve utilizar o banco de dados PostgreSQL, garantindo persistência e confiabilidade no armazenamento de dados.
- **[RNF014]** - O sistema deve adotar práticas de Clean Code e arquitetura em camadas para facilitar manutenção e evolução do código.
- **[RNF015]** - O sistema deve seguir uma abordagem RESTful para desenvolvimento das APIs, facilitando integração e consumo por outras aplicações.

## Implantação 

- **[RNF016]** - O sistema deve ser hospedado em um ambiente de nuvem, como AWS, garantindo alta disponibilidade, escalabilidade e monitoramento.

Equipe ContratAe.

  
