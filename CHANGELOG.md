# Histórico de desenvolvimento

## 0.2.4 — 11 de novembro de 2026 — experimental

- Corrige o pedido padrão de `agents/openai.yaml`, que ainda chamava `$inventariar-definicoes`; o nome da skill é `sager` desde o [commit 493ccc9](https://github.com/itamarfreitasufs-arch/inventariar-definicoes/commit/493ccc99aff4bcbe13f1d84fa047c39bd3cc1e64), de 10 de novembro de 2026.
- O relatório passa a informar a expressão de busca da contagem lexical e a declarar quando o ambiente não permite realçar o PDF.
- Acrescenta `CITATION.cff` e registra no README a ausência de licença.
- Sem mudança na grade de 18 rubricas e 29 fórmulas e sem novos ensaios.

## 0.2.3 — 7 de novembro de 2026 — experimental

[Commit da publicação](https://github.com/itamarfreitasufs-arch/inventariar-definicoes/commit/3d04a77dfd9e7f200a16c35bc8ee477646ad2294). O nome de invocação mudou de `inventariar-definicoes` para `sager` em 10 de novembro de 2026, sem alteração do método.

- Versão pública identificada no [protocolo](SKILL.md). A grade reúne 18 rubricas e 29 fórmulas para classificar operações de definição.
- O [README](README.md) registra aplicações a manuais de sustentabilidade e livros de educação ambiental. O alcance da leitura, a paginação, o OCR e a auditoria por amostra devem ser informados nas devolutivas.

## Convenção de versões

Cada skill segue sua própria sequência `principal.secundária.correção`. Incremente o último número para correções pontuais e o número do meio para mudanças relevantes no método, reiniciando o último em zero. Registre o estágio da edição em separado, como experimental, em validação ou estável. Reserve `1.0.0` para a primeira edição que cumpra critérios explícitos de validação.

Registre cada mudança coerente em um commit. Para cada marco de versão, anote o commit correspondente, as mudanças, os testes realizados e as pendências.
