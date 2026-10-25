
# Salesforce Support Lab

**Portfólio prático | Salesforce Administrator & Support N1/N2**

## Sobre o projeto

Laboratório de estudos e simulações práticas de suporte técnico na plataforma Salesforce, desenvolvido por Evandro Silva.

O objetivo é demonstrar conhecimentos em administração Salesforce, resolução de incidentes, controle de acessos, manutenção declarativa, automação e qualidade de dados.

As atividades serão realizadas em um ambiente Trailhead Playground, utilizando cenários fictícios próximos da rotina de um Analista de Suporte Júnior.

## Tecnologias e ferramentas

**Ferramentas utilizadas nos casos documentados:**

- Salesforce Sales Cloud (objeto Account)
- Salesforce Setup (perfis, Permission Sets, Validation Rules e Duplicate Rules)
- Salesforce Flow Builder
- Salesforce Data Import Wizard
- Arquivos CSV
- GitHub (documentação e evidências)
- Trailhead Playground

**Conhecimentos em estudo, ainda não demonstrados nos casos publicados:** Service Cloud, Data Loader e consultas SOQL.


| Módulo | Atividade | Status |
|---|---|---|
| 01 | [Atendimento e incidentes N1/N2](01-chamados-n1-n2/INC-001.md) | Concluído |
| 02 | [Usuários, perfis e permissões](01-chamados-n1-n2/INC-002.md) | Concluído |
| 03 | [Campos e regras de validação](01-chamados-n1-n2/INC-003.md) | Concluído |
| 04 | [Automação com Salesforce Flow Builder](01-chamados-n1-n2/INC-004.md) | Concluído |
| 05 | [Importação e qualidade de dados](01-chamados-n1-n2/INC-005.md) | Concluído |
| 06 | [Documentação e base de conhecimento](01-chamados-n1-n2/INC-006.md) | Concluído |

## Casos práticos concluídos

### INC-001 — Falha de visibilidade de campo

**Cenário:** usuário sem acesso ao campo
Categoria de Atendimento no objeto Account.

**Atividades realizadas:**
- Reprodução do problema.
- Análise de Field-Level Security.
- Ajuste das permissões do perfil.
- Validação com usuário de teste.
- Documentação da solução.

**Resultado:** incidente resolvido e validado.

[Ver relatório técnico e evidência](01-chamados-n1-n2/INC-001.md)


### INC-002 — Gestão de acessos com Permission Set

**Cenário:** concessão de acesso específico ao campo
Categoria de Atendimento para um usuário.

**Atividades realizadas:**
- Criação de um Permission Set.
- Configuração de permissões de leitura e edição.
- Atribuição individual ao usuário.
- Restrição de acesso pelo perfil Standard User.
- Validação das permissões efetivas.

**Resultado:** acesso validado por meio do
Permission Set, sem depender da permissão do perfil.

[Ver relatório técnico e evidência](01-chamados-n1-n2/INC-002.md)

### INC-003 — Erro de validação no Salesforce

**Cenário:** usuário impedido de salvar o cadastro
de um cliente devido a uma regra de validação.

**Atividades realizadas:**
- Reprodução do erro no Salesforce.
- Investigação de Validation Rules.
- Análise da fórmula de validação.
- Identificação da causa do bloqueio.
- Correção dos dados do registro.
- Validação da solução aplicada.

**Resultado:** cadastro corrigido e salvo
com sucesso, mantendo a regra ativa.

[Ver relatório técnico e evidências](01-chamados-n1-n2/INC-003.md)

### INC-004 — Automação com Salesforce Flow Builder

**Cenário:** necessidade de automatizar a classificação
de novas contas no Salesforce Sales Cloud.

**Atividades realizadas:**
- Criação de um Record-Triggered Flow.
- Configuração de condições com fórmula.
- Utilização de Fast Field Updates.
- Criação de constante e elemento Assignment.
- Ativação da automação.
- Teste funcional com registro fictício.
- Validação do preenchimento automático.

**Resultado:** automação implementada e validada.
O campo Categoria de Atendimento foi preenchido
automaticamente com o valor Comercial.

[Ver relatório técnico e evidências](01-chamados-n1-n2/INC-004.md)

### INC-005 — Importação e Qualidade de Dados

**Cenário:** investigação de possíveis registros
duplicados após a importação de clientes no Salesforce.

**Atividades realizadas:**
- Preparação e importação de arquivo CSV.
- Mapeamento de campos no Data Import Wizard.
- Análise dos resultados da importação.
- Investigação de possíveis contas duplicadas.
- Criação de Matching Rule personalizada.
- Configuração de Duplicate Rule.
- Teste funcional de bloqueio de duplicidades.

**Resultado:** quatro contas criadas com sucesso
e prevenção de novos cadastros duplicados
validada por meio de teste funcional.

[Ver relatório técnico e evidências](01-chamados-n1-n2/INC-005.md)


### INC-006 — Documentação e Base de Conhecimento

**Cenário:** criação de uma base de conhecimento
para padronizar o atendimento de chamados
relacionados ao Salesforce.

**Atividades realizadas:**
- Elaboração de documentação técnica.
- Identificação de sintomas e possíveis causas.
- Definição de procedimentos para suporte N1/N2.
- Documentação de orientações para resolução.
- Organização de evidências técnicas.
- Publicação de artigo de base de conhecimento.

**Resultado:** artigo KB-001 desenvolvido e
publicado, com orientações para diagnóstico
de bloqueios por duplicidade de contas.

[Ver relatório técnico INC-006](01-chamados-n1-n2/INC-006.md)

[Consultar artigo KB-001](02-base-conhecimento/KB-001.md)

## Metodologia

Cada módulo terá:

1. Descrição do cenário fictício.
2. Problema ou requisito apresentado.
3. Configuração ou procedimento realizado.
4. Evidências da execução.
5. Testes e resultados observados.
6. Conclusões e aprendizados.

## Ambiente

- Organização: Trailhead Playground
- Finalidade: aprendizado e demonstração técnica
- Dados: exclusivamente fictícios

> Este é um projeto educacional independente, não vinculado oficialmente à Salesforce ou à BRQ. Os módulos serão atualizados conforme sua execução e validação.

## Autor

**Evandro Silva**

Formado em Análise e Desenvolvimento de Sistemas.

GitHub: [evandro-himself](https://github.com/evandro-himself)
