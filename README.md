 Capa


---


<h1>Requisitos de Software</h1>


<h2>Sistema de postagem de vagas</h2>


<small>Versão 1.0</small>


---


## Histórico de revisões


|    Data    | Versão |          Descrição          |      Autor       |
| :--------: | :----: | :-------------------------: | :--------------: |
| 01/04/2023 |  1.0   |    Criação do documento     | Maxwell Anderson |
| 02/04/2023 |  1.1   | Adição de novas informações | Maxwell Anderson |


---


## Sumário


- [Capa](#capa)
  - [Histórico de revisões](#histórico-de-revisões)
  - [Sumário](#sumário)
- [Introdução](#introdução)
  - [Definições, Acrônimos e Abreviações](#definições-acrônimos-e-abreviações)
- [Usuários identificados](#usuários-identificados)
- [Requisitos funcionais](#requisitos-funcionais)
- [Requisitos não-funcionais](#requisitos-não-funcionais)
  - [Disponibilidade](#disponibilidade)
  - [Privacidade e segurança](#privacidade-e-segurança)
  - [Usabilidade](#usabilidade)
  - [Suportabilidade](#suportabilidade)
  - [Interoperabilidade](#interoperabilidade)
  - [Manutenibilidade](#manutenibilidade)
  - [Desempenho](#desempenho)
  - [Implementação](#implementação)
  - [Implantação](#implantação)
- [Matriz de rastreabilidade](#matriz-de-rastreabilidade)
  - [Rastreabilidade entre NFs e RNFs](#rastreabilidade-entre-nfs-e-rnfs)


---


# Introdução


O objetivo deste documento é apresentar os requisitos de software do produto **Sistema de postagem de vagas**


## Definições, Acrônimos e Abreviações


Esta subseção fornece as definições de todos os termos, acrônimos e abreviações necessárias à adequada interpretação do Documento de Requisitos.


- Identificação dos requisitos: por convenção, a referência a requisitos é feita através do identificador de requisitos, de acordo como descrito abaixo:


  `[IDENTIFICADOR DO TIPO DE REQUISITOSidentificador do requisito]`


  O identificador do tipo de requisitos é conforme abaixo:


  - RF – Requisito Funcional
  - RNF – Requisito Não-Funcional
  - NR – Não-Requisito


  O identificador do requisito será uma sequência numérica. Esse número sequencial será único para todo o conjunto de tipos de requisitos.


  **Exemplo**: RF0001, RF1234, RNF1234, NR1212


- Atributos dos Requisitos: os atributos de requisitos estabelecidos são:
  - **Requisitos vinculados**: fornece uma lista dos requisitos que mantém rastreabilidade.
  - **Prioridade**: Essencial, Importante, Desejável
  - **Complexidade**: Complexa, Alta, Média ou Baixa.
  - **Risco**: Alto, Médio, Baixo


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
- **[C-RF006]** -  Como candidato, gostaria de realizar buscas por vagas através de palavras-chaves e aplicação de filtros como, localidade, nível de experiência e empresas parceiras. 
- **[C-RF007]** - Como candidato, gostaria de receber email com novas vagas que combinam com minhas características profissionais.
- **[C-RF008]** -Como candidato, gostaria de uma funcionalidade para denunciar vagas que aparentam ser falsas, como forma de melhorar o ecossistema da aplicação para todos.

## Usuário recrutador 

- **[R-RF001]** - Como recrutador, gostaria de atualizar minhas informações pessoais e profissionais, cadastradas no sistema.
- **[R-RF002]** - Como recrutador, preciso ser capaz de anunciar vagas de emprego em um “post”, detalhando função, nível de experiência e remuneração.
- **[R-RF003]** - Como recrutador, preciso de uma funcionalidade para pesquisar candidatos a partir de palavras-chave, podendo-as identificar nome, cargo ou título.
- **[R-RF004]** - Como recrutador, preciso ter acesso ao perfil de um candidato, informando sua descrição, nome, experiências prévias e meios de contato.
- **[R-RF005]** - Como recrutador, devo ter a capacidade de editar informações sobre uma vaga que postei, caso haja alguma mudança como salário, período de trabalho ou carga horária por exemplo.
- **[R-RF006]** - Como recrutador, devo ter autoridade de excluir vagas de emprego que postei anteriormente a qualquer momento, tornando-a indisponível.

## Usuário empresa

- **[E-RF001]** - Como Empresa, preciso ter um cadastro com o nome, CNPJ, endereço, telefones, País.
- **[E-RF002]** - Como Empresa, gostaria de atualizar minhas informações cadastrais do sistema.
- **[E-RF003]** - Como Empresa, preciso ter como postar programas de treinamento no sistema para capacitar os candidatos.
- **[E-RF004]** - Como Empresa, preciso ter como excluir postagens feitas por mim.
- **[E-RF005]** - Como empresa, gostaria de notificar candidatos sobre o status dos programas a qual eles estão inscritos.

## Usuário Admiministrador


- **[A-RF001]** - Como administrador, gostaria de realizar o gerenciamento do sistema.
- **[A-RF002]** - Como administrador, gostaria de realizar o gerenciamento de usuários.
- **[A-RF003]** - Como administrador, preciso ter autoridade total no sistema para ser capaz de apagar vagas falsas que foram reportadas(após análise), candidatos ausentes por um período de tempo estendido, empresas que cancelaram a parceria e recrutadores.
- **[A-RF004]** - Como administrador, gostaria de oferecer aos clientes a possibilidade de realizar o login com o Google, para que eles possam ter uma experiência mais rápida e segura.
- **[A-RF005]** - Como administrador, gostaria que os usuários fossem comunicados sobre as atualizações do sistema, para que eles possam ter uma experiência mais segura e atualizada.


# Requisitos não-funcionais


- **[RNF001]** - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, 365 dias por ano. 
- **[RNF002]** - Vagas postadas tem prazo de validade para serem encerradas pelos recrutadores, caso contrário serão excluídas automaticamente pelo sistema.
- **[RNF003]** - O sistema deve ser desenvolvido de forma que possa ser escalável, ou seja, deve ser possível aumentar a capacidade de armazenamento de dados e de processamento de requisições sem que haja perda de desempenho.
- **[RNF004]** - O sistema deve atender aos requisitos de privacidade da LGPD (Lei Geral de Proteção de Dados). 
- **[RNF005]** - O sistema deve ser desenvolvido de forma que seja fácil de usar e de fácil aprendizado, de forma que os usuários não precisem de treinamento para utilizá-lo.
