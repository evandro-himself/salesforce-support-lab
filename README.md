
# Salesforce Support Lab

**Portfólio prático | Salesforce Administrator & Support N1/N2**

## Sobre o projeto

Laboratório de estudos e simulações práticas de suporte técnico na plataforma Salesforce, desenvolvido por Evandro Silva.

O objetivo é demonstrar conhecimentos em administração Salesforce, resolução de incidentes, controle de acessos, manutenção declarativa, automação e qualidade de dados.

As atividades serão realizadas em um ambiente Trailhead Playground, utilizando cenários fictícios próximos da rotina de um Analista de Suporte Júnior.

## Tecnologias e ferramentas

- Salesforce Sales Cloud e Service Cloud
- Salesforce Setup
- Salesforce Flow Builder
- Salesforce Data Loader
- SOQL (consultas básicas)
- CSV e ferramentas de planilhas
- Git e GitHub
- Trailhead Playground

## Projetos práticos

| Módulo | Atividade | Status |
|---|---|---|

| 01 | [Atendimento e incidentes N1/N2](01-chamados-n1-n2/INC-001.md) | 1º caso concluído |
| 02 | [Usuários, perfis e permissões](01-chamados-n1-n2/INC-002.md) | 2º caso concluído |
| 03 | [Campos e regras de validação](01-chamados-n1-n2/INC-003.md) | 3º caso concluído |
| 04 | Automações com Flow | Planejado |
| 05 | Importação e qualidade de dados | Planejado |
| 06 | Documentação e base de conhecimento | Planejado |

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
