<div align="center">

# DriveFlow

### Plataforma moderna e inteligente para gestão e aluguel de veículos

**Documentação de Projeto | Versão 1.1 | Projeto de Software**

<br>

![PlantUML](https://img.shields.io/badge/PlantUML-Obrigatório-2E7D32?style=for-the-badge)
![UML](https://img.shields.io/badge/UML-Modelagem-1565C0?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Projeto%20Acadêmico-6A1B9A?style=for-the-badge)
![Versão](https://img.shields.io/badge/Versão-1.1-455A64?style=for-the-badge)

<br>

<b>Sistema modelado para conectar clientes e administradores de frotas, permitindo a reserva ágil de automóveis, vistorias operacionais de balcão, controle de pagamentos e análise de faturamento.</b>

</div>

---

<div align="center">

## Documento Completo Oficial

<b>Este é o documento principal do projeto DriveFlow.</b>

O arquivo completo em PDF contém a documentação final do sistema, com a estrutura acadêmica solicitada, descrição do domínio, requisitos, contratos, modelos UML, arquitetura e modelos de dados.

<br>

<a href="DriveFlow.pdf">
  <img src="https://img.shields.io/badge/Abrir%20Documento%20Completo-PDF%20DriveFlow-C62828?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Abrir documento completo em PDF">
</a>

<br><br>

📄 **Arquivo:** [`DriveFlow.pdf`](DriveFlow.pdf)

</div>

> **Importante:** o PDF acima é a versão completa e oficial da documentação do projeto. O restante deste README funciona como apresentação visual, resumo navegável e apoio aos códigos estruturados em PlantUML.

---

## Cartão do Projeto

| Item | Informação |
| --- | --- |
| **Nome do sistema** | DriveFlow |
| **Versão** | 1.1 |
| **Disciplina** | Projeto de Software |
| **Elaborado por** | João Pedro Moura Santos |
| **Data de criação** | 05/06/2026 |
| **Tipo de entrega** | Projeto, arquitetura e diagramação |
| **Ferramenta obrigatória** | PlantUML |
| **Implementação de código** | Escopo conceitual de engenharia de software |

> Este repositório documenta o projeto de um sistema completo, com foco em análise, arquitetura, diagramas UML, regras de negócio, contratos de operação e modelo de dados.

---

## Visão Rápida

<table>
  <tr>
    <td width="33%">
      <b>Problema</b><br>
      Locadoras de veículos necessitam de controle centralizado de frota, redução de erros em vistorias de retirada/devolução e previsibilidade financeira de reservas.
    </td>
    <td width="33%">
      <b>Solução</b><br>
      Uma plataforma web integrada que unifica a reserva pelo cliente, o controle de balcão (check-out/check-in) pelo administrador e o faturamento automático.
    </td>
    <td width="33%">
      <b>Resultado esperado</b><br>
      Locações de automóveis rastreáveis, seguras, com vistorias documentadas e indicadores consolidados de ocupação da frota.
    </td>
  </tr>
</table>

---

## Tabela de Conteúdo

0. [Documento Completo Oficial](#documento-completo-oficial)
1. [Introdução](#1-introdução)
2. [Modelos de Usuário e Requisitos](#2-modelos-de-usuário-e-requisitos)
   - [2.1 Descrição de Atores](#21-descrição-de-atores)
   - [2.2 Modelo de Casos de Uso](#22-modelo-de-casos-de-uso)
   - [2.3 Diagrama de Sequência do Sistema e Contratos de Operação](#23-diagrama-de-sequência-do-sistema-e-contratos-de-operação)
3. [Modelos de Projeto](#3-modelos-de-projeto)
   - [3.1 Arquitetura](#31-arquitetura)
   - [3.2 Diagrama de Componentes e Implantação](#32-diagrama-de-componentes-e-implantação)
   - [3.3 Diagrama de Classes](#33-diagrama-de-classes)
   - [3.4 Diagramas de Sequência de Projeto](#34-diagramas-de-sequência-de-projeto)
   - [3.5 Diagramas de Comunicação](#35-diagramas-de-comunicação)
   - [3.6 Diagramas de Estados](#36-diagramas-de-estados)
4. [Modelos de Dados](#4-modelos-de-dados)
5. [Agradecimentos](#agradecimentos)
6. [Autor](#autor)
7. [Referências](#referências)

---

## Galeria de Diagramas

<table>
  <tr>
    <td align="center" width="33%">
      <b>Casos de Uso</b><br>
      <img src="Diagramas/CasoDeUso.png" alt="Diagrama de casos de uso" width="100%">
    </td>
    <td align="center" width="33%">
      <b>Sequência do Sistema</b><br>
      <img src="Diagramas/Sequencia-Principal.png" alt="Diagrama de sequência do sistema" width="100%">
    </td>
    <td align="center" width="33%">
      <b>Arquitetura</b><br>
      <img src="Diagramas/Arquitetura.png" alt="Diagrama de arquitetura" width="100%">
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <b>Implantação</b><br>
      <img src="Diagramas/Implantacao.png" alt="Diagrama de implantação" width="100%">
    </td>
    <td align="center" width="33%">
      <b>Classes</b><br>
      <img src="Diagramas/Classes.png" alt="Diagrama de classes" width="100%">
    </td>
    <td align="center" width="33%">
      <b>Sequência de Projeto</b><br>
      <img src="Diagramas/Sequencia-Principal.png" alt="Diagrama de sequência de projeto" width="100%">
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <b>Comunicação</b><br>
      <img src="Diagramas/comunicacao.png" alt="Diagrama de comunicação" width="100%">
    </td>
    <td align="center" width="33%">
      <b>Estados</b><br>
      <img src="Diagramas/estados.png" alt="Diagrama de estados" width="100%">
    </td>
    <td align="center" width="33%">
      <b>Dados (DER)</b><br>
      <img src="Diagramas/DER.png" alt="Modelo de dados" width="100%">
    </td>
  </tr>
</table>

---

## Histórico de Revisões

| Nome | Data | Razões para Mudança | Versão |
| --- | --- | --- | --- |
| João Pedro | 05/06/2026 | Criação da documentação estruturada do sistema DriveFlow | 1.0 |
| João Pedro | 08/06/2026 | Refatoração estrutural anti-sobreposição e padronização monolítica | 1.1 |

---

## Scripts PlantUML

Todos os diagramas foram especificados em PlantUML. Os scripts estruturados encontram-se no diretório `CodigoPlantUml/` e as imagens renderizadas em `Diagramas/`.

| Modelo | Script PlantUML | Imagem |
| --- | --- | --- |
| Casos de uso | `CodigoPlantUml/CasoDeUso.puml` | `Diagramas/CasoDeUso.png` |
| Sequência do sistema (UC-07) | `CodigoPlantUml/SequenciaUC07.puml` | `Diagramas/SequenciaUC07.png` |
| Arquitetura | `CodigoPlantUml/Arquitetura.puml` | `Diagramas/Arquitetura.png` |
| Componentes | `CodigoPlantUml/Componentes.puml` | `Diagramas/Componentes.png` |
| Implantação | `CodigoPlantUml/Implantacao.puml` | `Diagramas/Implantacao.png` |
| Classes | `CodigoPlantUml/Classes.puml` | `Diagramas/Classes.png` |
| Sequência de projeto (Geral) | `CodigoPlantUml/Sequencia-Geral.puml` | `Diagramas/Sequencia-Geral.png` |
| Sequência de projeto (Core) | `CodigoPlantUml/Sequencia-Principal.puml` | `Diagramas/Sequencia-Principal.png` |
| Comunicação | `CodigoPlantUml/Comunicacao.puml` | `Diagramas/comunicacao.png` |
| Estados | `CodigoPlantUml/Estados.puml` | `Diagramas/estados.png` |
| Dados (DER) | `CodigoPlantUml/DER.puml` | `Diagramas/DER.png` |

---

# 1. Introdução

Este documento apresenta o projeto de engenharia de software do **DriveFlow**, uma plataforma moderna para controle operacional e reserva de veículos. O sistema foi concebido sob uma **Arquitetura Monolítica Estruturada em 3 Camadas (3-Tier Architecture)**, integrando de forma síncrona a interface do usuário, a lógica de negócio e o armazenamento relacional de dados.

A interface com o usuário é implementada como uma *Single Page Application* (SPA) em **React**, comunicando-se através de requisições HTTPS e payload formato JSON REST com o servidor de aplicação back-end em **Java Spring Boot**. Toda a persistência de dados do domínio é centralizada de forma íntegra em uma instância isolada do sistema gerenciador relacional **PostgreSQL**.

## Objetivo do Sistema

Centralizar os processos operacionais de locação de veículos. O sistema gerencia de forma coesa a abertura de contas de clientes, a manutenção cadastral e situacional da frota automotiva, o ciclo transacional de reservas financeiras e os procedimentos analíticos de balcão (vistoria de check-out e check-in de devolução).

## Escopo

O projeto contempla a modelagem sistêmica completa da solução: delimitação de atores, detalhamento de requisitos funcionais e não funcionais, diagramas de arquitetura, mapeamento dinâmico de componentes, modelo de classes de domínio, interações de projeto via sequência e comunicação, máquinas de estado de negócio e modelagem física de dados via mapeamento objeto-relacional (ORM).

## Tecnologias Propostas

| Camada | Tecnologias propostas |
| --- | --- |
| Front-end Web | React, HTML5, JavaScript (ES6+), CSS3 |
| Back-end Engine | Java 17, Spring Boot Core, Spring Data JPA |
| Servidor Embutido | Apache Tomcat |
| Banco de Dados | SGBD Relacional PostgreSQL |
| Driver de Conexão | JDBC / Hibernate ORM |

## Regras de Negócio

| Código | Regra |
| --- | --- |
| RN-01 | O Cliente só pode solicitar reservas se possuir um registro de CNH válido cadastrado em seu perfil. |
| RN-02 | Um veículo automotivo não pode receber reservas concorrentes em um mesmo intervalo de datas. |
| RN-03 | O cadastro de um novo veículo exige a validação de unicidade da placa em relação à frota existente. |
| RN-04 | O valor total de uma locação é calculado multiplicando o número total de diárias do intervalo pelo valor unitário da diária do veículo. |
| RN-05 | A liberação física do veículo (Check-out) está condicionada à existência de uma reserva com pagamento previamente aprovado. |
| RN-06 | O veículo alterado para o estado de `MANUTENCAO` tem seu ID automaticamente bloqueado para consultas de novas locações. |
| RN-07 | O procedimento de check-in (Devolução) deve computar a quilometragem rodada final para auditoria e controle de uso da frota. |
| RN-08 | Taxas adicionais financeiras devem ser geradas caso haja atraso temporal na entrega ou divergência severa de combustível. |

## Premissas e Restrições

- O sistema assume que a autenticação é gerada via emissão segura de Tokens JWT.
- O controle financeiro de pagamentos é delegado a um Gateway externo parceiro.
- O DriveFlow encapsula identificadores transacionais, abstendo-se do armazenamento de cartões de crédito diretos.
- O veículo retorna para o status `DISPONIVEL` imediatamente após o fechamento sem avarias no check-in.

---

# 2. Modelos de Usuário e Requisitos

## 2.1 Descrição de Atores

| Ator | Descrição |
| --- | --- |
| **Cliente** | Usuário final do sistema. Realiza cadastro, consulta o catálogo de automóveis em tempo real, solicita reservas, realiza pagamentos e gerencia seu perfil. |
| **Administrador** | Funcionário ou gerente da locadora. Responsável pelo controle operacional, incluindo cadastro da frota, bloqueio para manutenção, liberação (check-out) e recebimento (check-in) de veículos. |
| **Gateway Pagamento** | Sistema externo parceiro encarregado do processamento e autorização segura das transações financeiras. |

---

## 2.2 Modelo de Casos de Uso

O diagrama de casos de uso do ecossistema delimita as fronteiras da aplicação baseadas em três grandes contextos lógicos de negócio.

<p align="center">
  <img src="Diagramas/CasoDeUso.png" alt="Diagrama de casos de uso do DriveFlow" width="850">
</p>

| ID | Caso de Uso | Ator Principal | Descrição |
| --- | --- | --- | --- |
| **UC-01** | Autenticar Usuário | Cliente / Administrador | Permite que os usuários realizem login seguro utilizando credenciais e validação de tokens. |
| **UC-02** | Cadastrar Cliente | Cliente | Permite que novos clientes criem contas informando dados pessoais, e-mail e CNH. |
| **UC-03** | Gerenciar Perfil | Cliente | Permite ao cliente atualizar seus dados cadastrais, contatos e credenciais de acesso. |
| **UC-04** | Manter Veículos (CRUD) | Administrador | Permite ao Administrador cadastrar, listar, atualizar e remover veículos da frota. |
| **UC-05** | Consultar Catálogo | Cliente | Permite ao Cliente buscar carros disponíveis aplicando filtros por marca e modelo. |
| **UC-06** | Registrar Manutenção | Administrador | Altera o estado de um carro para manutenção, bloqueando novas reservas no período. |
| **UC-07** | Solicitar Reserva | Cliente | Fluxo principal onde o Cliente seleciona o carro, define as datas e abre uma reserva. |
| **UC-08** | Cancelar Reserva | Cliente / Administrador | Permite cancelar uma reserva ativa sob a aplicação de regras de negócio específicas. |
| **UC-09** | Processar Pagamento | Gateway Pagamento | Integração para aprovação ou recusa da transação financeira vinculada à reserva. |
| **UC-10** | Check-out (Retirada) | Administrador | Registra a entrega física e a chave do veículo ao cliente, ativando o contrato local. |
| **UC-11** | Check-in (Devolução) | Administrador | Inspeção do carro no retorno, cálculo de quilometragem, avarias e encerramento. |
| **UC-12** | Emitir Relatórios | Administrador | Extração de métricas operacionais consolidadas sobre faturamento e uso da frota. |

---

## 2.3 Diagrama de Sequência do Sistema e Contratos de Operação

Os diagramas de sequência de sistema (DSS) tratam a aplicação de forma abstrata como uma **caixa preta**, mapeando os estímulos diretos gerados pelos atores na fronteira da aplicação.

### DSS: Solicitar Reserva de Veículo (UC-07)
<p align="center">
  <img src="Diagramas/Sequencia-Principal.png" alt="DSS do caso de uso 07" width="600">
</p>

### Contratos de Operação (Análise Estrutural)

#### CO-01: Solicitação de Reserva de Automóvel
- **Operação:** `criarReserva(veiculoId, dataInicio, dataFim)`
- **Referências Cruzadas:** UC-07: Solicitar Reserva de Veículo e UC-05: Consultar Catálogo de Veículos.
- **Pré-condições:** Cliente autenticado no ecossistema via JWT. O `veiculoId` deve ser um registro ativo com status `DISPONIVEL` nas datas informadas.
- **Pós-condições:** Uma instância $r$ da classe `Reserva` foi criada e salva no banco de dados. `r.clienteId` associado ao token, `r.dataInicio` e `r.dataFim` preenchidos com os parâmetros. O `r.valorTotal` foi calculado multiplicando os dias pelo preço unitário obtido localmente via `VeiculoRepository`. O status inicial da reserva foi definido como `PENDENTE`.

#### CO-02: Cadastro de Veículo na Frota
- **Operação:** `cadastrarVeiculo(placa, modelo, marca, precoDiaria)`
- **Referências Cruzadas:** UC-04: Manter Veículos (CRUD).
- **Pré-condições:** Usuário autenticado sob a Role de `Administrador`. A `placa` enviada não pode existir previamente registrada no sistema.
- **Pós-condições:** Uma nova instância $v$ da classe `Veiculo` foi criada e persistida no banco. `v.placa`, `v.modelo`, `v.marca` e `v.precoDiaria` foram devidamente inicializados. O status interno de estoque de $v$ foi configurado por padrão como `DISPONIVEL`.

#### CO-03: Encerramento de Contrato e Check-in de Devolução
- **Operação:** `registrarCheckIn(reservaId, kmFinal, avarias, nivelCombustivel)`
- **Referências Cruzadas:** UC-11: Realizar Check-in do Veículo (Devolução).
- **Pré-condições:** Usuário autenticado como `Administrador`. A reserva identificada por `reservaId` deve conter o status operacional de `EM_ANDAMENTO`.
- **Pós-condições:** O status da reserva foi modificado para `FINALIZADA`. O veículo associado teve seu status alterado para `DISPONIVEL` (ou para `MANUTENCAO`, caso o parâmetro de avarias registre danos estruturais severos). O sistema calculou taxas adicionais com base em quilometragem e combustível, atualizando o fechamento do registro de dados.

---

# 3. Modelos de Projeto

## 3.1 Arquitetura

O **DriveFlow** adota uma **Arquitetura Monolítica em 3 Camadas**. Essa abordagem distribui de forma robusta e organizada as responsabilidades do sistema em componentes lógicos bem delimitados:

1. **Frontend Client (Camada de Apresentação):** Uma *Single Page Application* (SPA) construída em React que roda no navegador do usuário, gerando interfaces altamente responsivas.
2. **Backend Server (Camada de Aplicação):** Desenvolvido em Java Spring Boot, é dividido de maneira modular em controladores HTTP REST, lógica abstrata de serviços de negócio e abstrações de repositórios.
3. **Data Tier (Camada de Dados):** Onde as entidades estruturadas de domínio são armazenadas de maneira confiável em um SGBD relacional PostgreSQL.

<p align="center">
  <img src="Diagramas/Arquitetura.png" alt="Diagrama da Arquitetura do DriveFlow" width="400">
</p>

---

## 3.2 Diagrama de Componentes e Implantação

### Mapeamento de Componentes (Logical View)
O desacoplamento interno do código-fonte utiliza o padrão do Spring Data JPA, onde os controladores comunicam-se estritamente com as interfaces de regras de negócio, que por sua vez manipulam dados através das camadas de persistência.

<p align="center">
  <img src="Diagramas/Componentes.png" alt="Diagrama de Componentes do DriveFlow" width="550">
</p>

### Diagrama de Implantação (Physical View)
O mapeamento físico indica a topologia de rede cloud, demonstrando a distribuição dos artefatos estáticos web, o container de aplicação Tomcat executando o arquivo compiled `.jar` sob a JRE 17, e o banco PostgreSQL.

<p align="center">
  <img src="Diagramas/Implantacao.png" alt="Diagrama de Implantação do DriveFlow" width="550">
</p>

---

## 3.3 Diagrama de Classes

O diagrama de classes de domínio representa as entidades estruturais que serão espelhadas diretamente para o mapeamento objeto-relacional da base de dados, utilizando herança e associações bem definidas.

<p align="center">
  <img src="Diagramas/Classes.png" alt="Diagrama de Classes do Sistema DriveFlow" width="850">
</p>

---

## 3.4 Diagramas de Sequência de Projeto

Os diagramas de sequência de projeto mapeiam a realização interna dos fluxos operacionais da aplicação, evidenciando as ativações e chamadas síncronas entre os objetos de software.

### Visão Geral dos Fluxos de Projeto Unificados
O diagrama macro consolida os eixos lógicos de execução da API, dividindo as requisições HTTP enviadas pelo React pelas subcamadas de Controllers e Services da aplicação Java.

<p align="center">
  <img src="Diagramas/Sequencia-Geral.png" alt="Diagrama de Sequência Geral de Projeto" width="850">
</p>

### Realização de Projeto Detalhada: Solicitar Reserva (UC-07)
Abaixo, demonstra-se a engenharia de software em execução profunda na subcamada da API, ilustrando a chamada síncrona do `RentalController` delegando regras de negócio ao `LocacaoService` e persistindo a entidade através do `ReservaRepository`.

<p align="center">
  <img src="Diagramas/Sequencia-Principal.png" alt="Diagrama de Sequência de Projeto UC-07" width="850">
</p>

---

## 3.5 Diagramas de Comunicação

O diagrama de comunicação foca na organização estrutural integrada dos objetos que colaboram na arquitetura. Ele destaca o fluxo do core de locações e mapeia indiretamente os módulos satélites de autenticação e gestão de frota convergindo para o banco de dados unificado.

<p align="center">
  <img src="Diagramas/comunicacao.png" alt="Diagrama de Comunicação Integrado" width="850">
</p>

---

## 3.6 Diagramas de Estados

A máquina de estados descreve as variações situacionais ocorridas no ciclo de vida de uma entidade **Reserva**, controlando suas transições a partir de gatilhos operacionais e condicionais de guarda.

<p align="center">
  <img src="Diagramas/estados.png" alt="Diagrama de Estados da Reserva" width="950">
</p>

---

# 4. Modelos de Dados

O modelo de dados do DriveFlow utiliza mapeamento relacional estruturado, preservando integridade referencial nativa via chaves estrangeiras.

<p align="center">
  <img src="Diagramas/DER.png" alt="Diagrama Entidade-Relacionamento Físico (DER)" width="550">
</p>

## Estratégias de Mapeamento

- **Mapeamento de Herança (Single Table):** A hierarquia entre `Usuario`, `Cliente` e `Administrador` é persistida em uma única tabela chamada `tb_usuarios`. O Hibernate gerencia a instanciação via coluna discriminadora `tipo_usuario`, otimizando a velocidade de resposta de JOINS na autenticação.
- **Mapeamento de Associações (Foreign Keys):** As relações Muitos-para-Um (`@ManyToOne`) geram chaves físicas explicitadas em `tb_reservas` (`cliente_id` e `veiculo_id`). O vínculo exclusivo entre Reserva e Pagamento é resolvido via `@OneToOne` contendo delegação em cascata.
- **Mapeamento de Tipos Complexos (Enums):** Os estados e métodos transacionais de negócio são armazenados como strings textuais literais através da diretiva `@Enumerated(EnumType.STRING)`, garantindo facilidade em auditorias diretas via SQL.

---

## Estrutura do Repositório

```text
.
├── CodigoPlantUml
│   ├── Arquitetura.puml
│   ├── CasoDeUso.puml
│   ├── Classes.puml
│   ├── Componentes.puml
│   ├── Comunicacao.puml
│   ├── DER.puml
│   ├── Estados.puml
│   ├── Implantacao.puml
│   ├── Sequencia-Geral.puml
│   ├── Sequencia-Principal.puml
│   ├── SequenciaUC04.puml
│   └── SequenciaUC11.puml
├── Diagramas
│   ├── Arquitetura.png
│   ├── CasoDeUso.png
│   ├── Classes.png
│   ├── Componentes.png
│   ├── DER.png
│   ├── DriveFlow.pdf
│   ├── Implantacao.png
│   ├── Sequencia-Geral.png
│   ├── Sequencia-Principal.png
│   ├── SequenciaUC04.png
│   ├── SequenciaUC11.png
│   ├── com_comentarios_comunicacao.png
│   ├── com_comentarios_estados.png
│   ├── comunicacao.png
│   ├── estados.png
│   └── index.html
└── README.md
```

---

## Agradecimentos

<div align="center">

Agradeço ao professor **João Paulo Aramuni** pela orientação, dedicação e pelos ensinamentos transmitidos ao longo da disciplina de **Projeto de Software**. Este trabalho foi desenvolvido sob sua tutoria e reflete o aprendizado adquirido durante o curso.

</div>

---

## Autor

<div align="center">

**João Pedro Moura Santos**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaomourasantos/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JoaoMouraS)

</div>

---

## Referências

- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [React Documentation](https://react.dev/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [PlantUML Documentation](https://plantuml.com/)
- LARMAN, Craig. *Utilizando UML e Padrões*. 3. ed. Bookman, 2007.
