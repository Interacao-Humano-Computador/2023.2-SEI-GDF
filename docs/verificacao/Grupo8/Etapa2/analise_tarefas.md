# Verificação da Análise de Tarefas

## Introdução

Este documento é de verificação dos artefatos [Análise de Tarefas: HTA](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/analise-de-tarefas/HTA) e [Análise de Tarefas: GOMS](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/analise-de-tarefas/GOMS) produzido pelo [Grupo 8](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/) que tem o projeto voltado ao site do Sistema Eletrônico de Informações do DF (SEI-GDF). Com base nisso, sua análise de tarefas será verificada de acordo com as informações presentes no livro Interação-Humano-Computador de Barbosa e Silva.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca dos artefatos de Análise de Tarefas do grupo.

## Metodologia

Para a verificação do artefato, a metodologia escolhida será baseada na inspeção de Fagan. Conforme proposta por ele, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos. Essa revisão é realizada através de uma checklist onde se tem uma lista com os defeitos mais comuns que deverão ser identificados, analisados e classificados.
A checklist, baseada no livro, será composta por 5 perguntas que serão o padrão exigido para a documentação e em seguida perguntas envolvendo o conteúdo dos artefatos [Análise de Tarefas: HTA](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/analise-de-tarefas/HTA) e [Análise de Tarefas: GOMS](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/). Na Tabela 1 estão expostos as perguntas gerais para os atefatos abordadas para verficação, a Tabela 2 mostra as perguntas específicas para o HTA e a Tabela 3 as específicas para o GOMS.

As versões utilizadas para a verificação serão as: 1.1, feita no dia 14 de Outubro de 2023 (HTA); 2.0, feita no dia 18 de Outubro de 2023 (GOMS).

<center>

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Checklist geral dos artefatos de análise de tarefas. </p></font>

| ID  | Descrição                                                                                              | Avaliação | Observações |
| :-: | ------------------------------------------------------------------------------------------------------ | :-------: | :---------: |
|  1  | O artefato possui introdução?                                                                          |           |             |
|  2  | O artefato possui uma bibliografia/referência bibliográfica?                                           |           |             |
|  3  | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |           |             |
|  4  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           |           |             |
|  5  | Todos os textos estão na norma padrão?                                                                 |           |             |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Checklist específica do HTA. </p></font>

|  ID  | Descrição                                                                                                                                                                            | Avaliação | Observações |
| :--: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------: | :---------: |
|  6   | Os objetivos a serem alcançados são apresentados?                                                                                                                                    |           |             |
|  7   | As tarefas foram descritas em termos de objetivos que os usuários precisam executar, evitando descrições vagas ou ambíguas?                                                          |           |             |
|  8   | As tarefas apresentadas são verossímeis?                                                                                                                                             |           |             |
|  9   | As tarefas foram formuladas de maneira conceitual e orientada ao usuário, focando nas ações que eles executam, em vez de detalhes técnicos ou da implementação/interface do sistema? |           |             |
|  10  | As tarefas são decompostas?                                                                                                                                                          |           |             |
|  11  | As tarefas relacionam o que as pessoas fazem com o porquê o fazem e quais as consequências caso não façam corretamente?                                                              |           |             |
|  12  | Os diagramas apresentam os elementos esperados (plano, objetivos, operações e as relações entre os subobjetivos)?                                                                    |           |             |
|  13  | As operações são especificadas?                                                                                                                                                      |           |             |
| 13.1 | Elas possuem entradas?                                                                                                                                                               |           |             |
| 13.2 | Elas possuem ações?                                                                                                                                                                  |           |             |
| 13.3 | Elas possuem _feedbacks_?                                                                                                                                                            |           |             |
|  14  | A decomposição termina quando os objetivos são atingidos ou quando a origem de um erro é identificada?                                                                               |           |             |
|  15  | As tarefas são apresentadas em tabelas?                                                                                                                                              |           |             |
| 15.1 | As tabelas apresentam os objetivos/operações?                                                                                                                                        |           |             |
| 15.2 | As tabelas apresentam os problemas e recomendações?                                                                                                                                  |           |             |
| 15.3 | As tabelas apresentam as entradas, ações, _feedbacks_ e os planos?                                                                                                                   |           |             |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Checklist específica do GOMS.</p></font>

|  ID  | Descrição                                                                 | Avaliação | Observações |
| :--: | ------------------------------------------------------------------------- | :-------: | :---------: |
|  6   | As análises com o GOMS são realizadas a partir das tarefas da HTA?        |           |             |
|  7   | Há uma hierarquia estrita entre os objetivos?                             |           |             |
|  8   | Os operadores são executados em ordem sequencial?                         |           |             |
|  9   | Os métodos GOMS são representados em notação semelhante a pseudocódigo?   |           |             |
|  10  | Os métodos GOMS possuem os quatros elementos principais?                  |           |             |
| 10.1 | Eles possuem os objetivos (_goals_)?                                      |           |             |
| 10.2 | Eles possuem os operadores (_operators_) primitivos internos ou externos? |           |             |
| 10.3 | Eles possuem os métodos (_methods_)?                                      |           |             |
| 10.4 | Eles possuem as regras de seleção (_selection rules_)?                    |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

Nas tabelas, os campos de "Avaliação" e "Observações" serão preenchidos no desenvolvimento em que haverá uma discussão a respeito de alguns itens. Para tal será utilizado o ID da pergunta.

## Cronograma e Participantes

Os participantes são os integrantes do grupo [Felipe de Sousa](https://github.com/fsousac), que será responsável por realizar a verificação e a correção dos problemas encontrados. Além disso, o integrante do grupo [Millena Queiroz](https://github.com/millenaqueiroz) realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/verificacao/Grupo8/Etapa2/planejamento-verificacao-etapa2).

<center>

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Participantes da Etapa</p></font>

|                     Participante                     |   Papel   |
| :--------------------------------------------------: | :-------: |
|    [Felipe de Sousa](https://github.com/fsousac)     | Avaliador |
| [Millena Queiroz](https://github.com/millenaqueiroz) |  Revisor  |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

## Desenvolvimento

### HTA

O artefato foi verificado e gerou os resultados da Tabela 4, sendo possível identificar os tópicos faltantes e/ou concluídos.

<center>

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Checklist preechido. </p></font>

|  ID  | Descrição                                                                                                                                                                            |  Avaliação   |        Observações         |
| :--: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :----------: | :------------------------: |
|  1   | O artefato possui introdução?                                                                                                                                                        |   Conforme   |                            |
|  2   | O artefato possui uma bibliografia/referência bibliográfica?                                                                                                                         |   Conforme   |                            |
|  3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores?                                                                               |   Conforme   |                            |
|  4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                                                                                                         |   Conforme   | Será justificado no texto. |
|  5   | Todos os textos estão na norma padrão?                                                                                                                                               |   Conforme   |                            |
|  6   | Os objetivos a serem alcançados são apresentados?                                                                                                                                    | Não conforme | Será justificado no texto. |
|  7   | As tarefas foram descritas em termos de objetivos que os usuários precisam executar, evitando descrições vagas ou ambíguas?                                                          |   Conforme   |                            |
|  8   | As tarefas apresentadas são verossímeis?                                                                                                                                             |   Conforme   |                            |
|  9   | As tarefas foram formuladas de maneira conceitual e orientada ao usuário, focando nas ações que eles executam, em vez de detalhes técnicos ou da implementação/interface do sistema? |   Conforme   |                            |
|  10  | As tarefas são decompostas?                                                                                                                                                          |   Conforme   |                            |
|  11  | As tarefas relacionam o que as pessoas fazem com o porquê o fazem e quais as consequências caso não façam corretamente?                                                              |   Conforme   |                            |
|  12  | Os diagramas apresentam os elementos esperados (objetivos, operações e as relações entre os subobjetivos)?                                                                           |   Conforme   |                            |
|  13  | As operações são especificadas?                                                                                                                                                      |   Conforme   |                            |
| 13.1 | Elas possuem entradas?                                                                                                                                                               |   Conforme   |                            |
| 13.2 | Elas possuem ações?                                                                                                                                                                  |   Conforme   |                            |
| 13.3 | Elas possuem _feedbacks_?                                                                                                                                                            |   Conforme   |                            |
|  14  | A decomposição termina quando os objetivos são atingidos ou quando a origem de um erro é identificada?                                                                               |   Conforme   |                            |
|  15  | As tarefas são apresentadas em tabelas?                                                                                                                                              |   Conforme   |                            |
| 15.1 | As tabelas apresentam os objetivos/operações?                                                                                                                                        |   Conforme   |                            |
| 15.2 | As tabelas apresentam os problemas e recomendações?                                                                                                                                  |   Conforme   |                            |
| 15.3 | As tabelas apresentam as entradas, ações, _feedbacks_?                                                                                                                               |   Conforme   | Será justificado no texto. |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

Com base na tabela preenchida, serão feitas considerações acerca de alguns itens da tabela.

### ID 4 - Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?

Todas as tabelas e imagens possuem fonte e legenda, porém há alguns casos em que a tabela está com título de figura, mas é chamada no texto superior como tabela, então caberia somente essa correção de título. Um exemplo disso ocorre na Tabela 4 como mostra a Figura 1 abaixo:

<center>

<font size="3"><p style="text-align: center"><b>Figura 1</b> - Legenda errada. </p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/89664b2a-db7f-40a2-94dd-b522b81cb4bf" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/89664b2a-db7f-40a2-94dd-b522b81cb4bf" alt="image">

<font size="3"><p style="text-align: center">Fonte: [Análise de Tarefas: HTA](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/analise-de-tarefas/HTA) (Acesso em: 02/10/2023)</p></font>

</center>

### ID 6 - Os objetivos a serem alcançados são apresentados?

O objetivo da análise não é explicitado, a pesar de demonstrar o porquê da escolha do HTA, não é possível saber qual o objetivo da análise. Portanto, cabe uma breve explicação do objetivo da análise no início do artefato.

### ID 15.3 - As tabelas apresentam as entradas, ações, _feedbacks_ ?

As tabelas apresentam as entradas, ações e _feedbacks_, porém a parte de entradas e ações estão representadas no mesmo campo chamado "input".

## Sugestões e melhorias

Os artefatos estão bem definidos e executados, salvo alguns detalhes com relação aos pontos citados. Sugere-se, portanto, apenas uma melhoria para o artefato:

- Explicitar o objetivo da análise no início do artefato.

### GOMS

O artefato foi verificado e gerou os resultados da Tabela 5, sendo possível identificar os tópicos faltantes e/ou concluídos.

<center>

<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Checklist preechido. </p></font>

|  ID  | Descrição                                                                                              | Avaliação |        Observações         |
| :--: | ------------------------------------------------------------------------------------------------------ | :-------: | :------------------------: |
|  1   | O artefato possui introdução?                                                                          | Conforme  |                            |
|  2   | O artefato possui uma bibliografia/referência bibliográfica?                                           | Conforme  |                            |
|  3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Conforme  |                            |
|  4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           | Conforme  |                            |
|  5   | Todos os textos estão na norma padrão?                                                                 | Conforme  |                            |
|  6   | As análises com o GOMS são realizadas a partir das tarefas da HTA?                                     | Conforme  |                            |
|  7   | Há uma hierarquia estrita entre os objetivos?                                                          | Conforme  |                            |
|  8   | Os operadores são executados em ordem sequencial?                                                      | Conforme  |                            |
|  9   | Os métodos GOMS são representados em notação semelhante a pseudocódigo?                                | Conforme  |                            |
|  10  | Os métodos GOMS possuem os quatros elementos principais?                                               | Conforme  | Será justificado no texto. |
| 10.1 | Eles possuem os objetivos (_goals_)?                                                                   | Conforme  |                            |
| 10.2 | Eles possuem os operadores (_operators_) primitivos internos ou externos?                              | Conforme  |                            |
| 10.3 | Eles possuem os métodos (_methods_)?                                                                   | Conforme  |                            |
| 10.4 | Eles possuem as regras de seleção (_selection rules_)?                                                 | Conforme  |                            |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

### ID 10 - Os métodos GOMS possuem os quatros elementos principais?

Os métodos possuem explícitamente três dos quatro elementos principalmente, ficando apenas implícito o método de realização, sendo escrito somente como operações. Cabe, portanto, uma mudança apenas mostrando que algumas operações são métodos.

## Sugestões e melhorias

Os artefatos estão bem definidos e executados, salvo alguns detalhes com relação aos pontos citados. Sugere-se, portanto, apenas uma melhoria para o artefato:

- Explicitar métodos do GOMS.

## Bibliografia

> HENRIQUE, Matheus; FERREIRA, Rafael. Análise de Tarefas - GOMS. Repositório do grupo Bilheteria Digial da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/verificacao/grupo/etapa2/at-goms/>. Acesso em: 02 de dezembro 2023.

> HENRIQUE, Matheus; FERREIRA, Rafael. Análise de Tarefas - HTA. Repositório do grupo Bilheteria Digial da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/verificacao/grupo/etapa2/at-hta/>. Acesso em: 02 de dezembro 2023.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versões

| Versão | Data       | Descrição            | Autor(es)                                     | Revisor(es)                                          |
| ------ | ---------- | -------------------- | --------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 02/12/2023 | Criação do documento | [Felipe de Sousa](https://github.com/fsousac) | [Millena Queiroz](https://github.com/millenaqueiroz) |
