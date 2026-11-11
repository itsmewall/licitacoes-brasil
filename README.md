# Licitações Brasil 🇧🇷

**Skill em português brasileiro para elaborar, revisar e analisar documentos de licitações e contratos administrativos.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-beta-orange)
![Lei 14.133](https://img.shields.io/badge/Lei-14.133%2F2021-green)

> Projeto comunitário independente, não vinculado ao governo brasileiro, à Anthropic ou ao Claude. Os resultados exigem verificação técnica e jurídica por profissionais responsáveis.

## O que faz

- Documento de Formalização da Demanda (**DFD**)
- Estudo Técnico Preliminar (**ETP**)
- Termo de Referência (**TR**)
- Pesquisa de preços, orçamento e matriz de riscos
- Editais, habilitação, impugnações e recursos
- Contratos administrativos, fiscalização e contratação direta
- Obras e serviços de engenharia
- Concessão/permissão de uso de bens públicos e casos aeroportuários
- Revisão técnica, jurídica e editorial com relatório de inconsistências separado

O orquestrador está em [SKILL.md](SKILL.md). Os roteiros específicos ficam em [references/](references/).

## Instalação no Claude Web

Baixe o repositório em **Code → Download ZIP** ou use o ZIP de um release. O ZIP deve apresentar `SKILL.md` e `.claude-plugin/plugin.json` em sua raiz; se o ZIP do GitHub contiver uma pasta externa, extraia e recompacte apenas o conteúdo dela. No Claude, acesse **Customize → Skills → Upload a skill** (conforme disponibilidade na sua conta) e ative.

## Exemplos

```text
Use a skill licitacoes-brasil para elaborar um Termo de Referência final,
com base nos anexos e no modelo fornecido. Não invente quantitativos, prazos
ou valores. Relate inconsistências apenas em documento separado.
```

```text
Elabore ETP com análise de alternativas, estimativa de quantidades,
levantamento de mercado, justificativa de parcelamento e conclusão,
conforme art. 18 da Lei 14.133/2021.
```

```text
Revise este edital, apontando divergências entre os dispositivos,
o TR, o ETP e a legislação aplicável. Fundamente e cite cada achado.
```

## Bases normativas

- [Lei nº 14.133/2021 — Planalto](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14133.htm)
- [Portal Nacional de Contratações Públicas — PNCP](https://www.gov.br/pncp/pt-br)
- [Portal da AGU](https://www.gov.br/agu/pt-br)

A Lei 14.133/2021 não é automaticamente o regime principal de todas as concessões ou contratações. Analise o objeto e o ente federativo: estatais, concessões de serviços públicos e PPPs têm regimes específicos. Consulte normas atualizadas, regulamentos locais e jurisprudência oficial. A skill não certifica vigência legislativa em tempo real.

## Contribua

Issues e pull requests são bem-vindos. Leia [CONTRIBUTING.md](CONTRIBUTING.md) e não publique documentos sigilosos ou dados pessoais.

## Licença

[MIT](LICENSE).