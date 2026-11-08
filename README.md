# Inventariar Definições — Definition Extraction and Classification for Historical Research

Protocolo de **Itamar Freitas**, versão **0.2.3 experimental**, formalizado com assistência de IA.

Esta skill ajuda a descobrir **como um texto define um termo**. Você indica uma palavra ou expressão e fornece o texto. O assistente localiza as passagens relevantes, distingue definições de simples menções e mostra quais operações o autor emprega para definir. A consulta pode ser aplicada a artigos, capítulos e livros.

## Em que se baseia

A [grade de 18 rubricas e 29 fórmulas](references/grade.csv) resulta da leitura da antologia *Essays on Definition*, organizada por Juan C. Sager (2000), e da adaptação desses modos de definir à análise de textos acadêmicos. Entre eles estão classe geral e diferença, enumeração, finalidade, contraste e relação entre entidades.

A distinção entre **categorias históricas**, **conceitos históricos** e **nomes próprios** vem de Jörn Rüsen (2007, pp. 92–94). O [protocolo](SKILL.md) retomou essa distinção a partir da exposição de Itamar Freitas no estudo “Conceitos históricos” (2014, pp. 66–67). A classificação descreve o que a passagem faz. A semelhança formal com uma definição clássica, por si só, não demonstra influência histórica.

## O que pode entregar

- Um inventário de definições explícitas e contextuais, com **trecho, autoria, página ou seção e justificativa**.
- A fórmula principal de cada passagem e, quando pertinente, operações secundárias. Modalidades, conceitos vizinhos, reconstruções e casos pendentes ficam identificados.
- Frequências por fórmula ou rubrica, com indicação do que foi contado e dos efeitos de citações recorrentes. Quando a obra permite, o relatório compara o uso das definições na introdução e na conclusão.
- Uma síntese em forma de verbete, apoiada nas evidências do texto. Se você pedir e o PDF permitir, o assistente também pode entregar uma cópia com os trechos conferidos em destaque.

## Como experimentar

Forneça ao assistente o [SKILL.md](SKILL.md), a [grade de classificação](references/grade.csv) e o texto que você quer examinar. Em ferramentas compatíveis com skills, siga o procedimento de importação da pasta. Também é possível usar as instruções e a grade em uma conversa comum.

> Use Inventariar definições para examinar a expressão “educação ambiental” neste capítulo. Indique quem formula cada definição, cite o trecho com a página, classifique a operação principal e apresente as frequências. Separe os casos pendentes e informe a cobertura da leitura.

## Testes e limites

O protocolo foi aplicado a manuais de sustentabilidade e a livros sobre educação ambiental. No levantamento de educação ambiental, a auditoria ajudou a detectar definições introduzidas por pronomes ou siglas e a separar a definição de um conceito de instruções sobre como aplicá-lo. As contagens descrevem as obras examinadas. A auditoria por amostra e os limites de leitura, paginação e OCR devem aparecer no relatório.

Ao relatar um problema, indique a versão usada, o trecho autorizado, a classificação recebida e a razão da divergência.

## Referências

- FREITAS, Itamar. Conceitos históricos. In: FREITAS, Itamar. [*Aprender e ensinar história nos anos finais da escolarização básica*](https://itemnpo.unifesspa.edu.br/images/Textos/Aprender-e-ensinar-Histria-nos-anos-finais-da-escolarizao-bsica.pdf). Aracaju: Criação, 2014. Ver pp. 66–67.
- RÜSEN, Jörn. Conceitos históricos. In: RÜSEN, Jörn. [*Reconstrução do passado: teoria da história II: os princípios da pesquisa histórica*](https://sophia-web.unirio.br/TerminalWeb/acervo/detalhe/20665). Tradução de Asta-Rose Alcaide. Brasília: Editora da UnB, 2007. pp. 91–100, especialmente pp. 92–94. Original alemão: [*Rekonstruktion der Vergangenheit: Die Prinzipien der historischen Forschung*](https://www.jdg-online.de/detail/00020692). Göttingen: Vandenhoeck & Ruprecht, 1986.
- SAGER, Juan C. (org.). [*Essays on Definition*](https://doi.org/10.1075/tlrp.4). Introdução de Alain Rey. Amsterdam e Philadelphia: John Benjamins, 2000.
