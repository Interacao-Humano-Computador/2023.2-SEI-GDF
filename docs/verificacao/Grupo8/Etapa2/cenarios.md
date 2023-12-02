# Verificação dos Cenários

## Introdução

Este documento é de verificação do artefato de [Cenários](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/cenarios) produzido pelo [Grupo 8](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/) que tem o projeto voltado ao site do Sistema Eletrônico de Informações do DF (SEI-GDF). Com base nisso, sua análise de tarefas será verificada de acordo com as informações presentes no livro Interação-Humano-Computador de Barbosa e Silva.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato de Cenários do grupo.

## Metodologia

Para a verificação do artefato, a metodologia escolhida será baseada na inspeção de Fagan. Conforme proposta por ele, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos. Essa revisão é realizada através de uma checklist onde se tem uma lista com os defeitos mais comuns que deverão ser identificados, analisados e classificados.
A checklist, baseada no livro, será composta por 5 perguntas que serão o padrão exigido para a documentação e em seguida perguntas envolvendo o conteúdo do artefato.Na Tabela 1 estão expostos todas as perguntas abordadas para verficação do artefato, a versão utilizadas para a verificação será a: 1.10, feita no dia 13 de outubro de 2023.

<center>

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Checklist artefato cenários. </p></font>

| ID  | Descrição                                                                                              | Avaliação | Observações |
| :-: | ------------------------------------------------------------------------------------------------------ | :-------: | :---------: |
|  1  | O artefato possui Introdução?                                                                          |           |             |
|  2  | O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                                  |           |             |
|  3  | O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores? |           |             |
|  4  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           |           |             |
|  5  | Todos os textos estão na norma padrão?                                                                 |           |             |
|  6  | Os cenários possuem detalhes contextuais de uso da aplicação envolvendo o usuário?                     |           |             |
|  7  | Eles descrevem o comportamento e as experiência dos atores?                                            |           |             |
|  8  | Cada ator possui objetivos que dirigem as tarefas que ele realiza?                                     |           |             |
|  9  | Cada cenário tem um título que descreve brevemente a situação, os atores, referência a outro artefato? |           |             |
| 10  | Nos cenários há o ambiente, o planejamento, as ações, os eventos, e a avaliação?                       |           |             |
| 11  | Os cenários são associados à alguma tarefa de uso diário do ator?                                      |           |             |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

Na Tabela 1, os campos de "Avaliação" e "Observações" serão preenchidos no desenvolvimento em que haverá uma discussão a respeito de alguns itens. Para tal será utilizado o ID da pergunta.

## Cronograma e Participantes

Os participantes são os integrantes do grupo [Felipe de Sousa](https://github.com/fsousac), que será responsável por realizar a verificação e a correção dos problemas encontrados. Além disso, o integrante do grupo [Millena Queiroz](https://github.com/millenaqueiroz) realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](planejamento-verificacao-etapa2.md).

<center>

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Participantes da Etapa</p></font>

|                     Participante                     |   Papel   |
| :--------------------------------------------------: | :-------: |
|    [Felipe de Sousa](https://github.com/fsousac)     | Avaliador |
| [Millena Queiroz](https://github.com/millenaqueiroz) |  Revisor  |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

## Desenvolvimento

O artefato foi verificado e gerou os resultados da Tabela 2, sendo possível identificar os tópicos faltantes e/ou concluídos.

<center>

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Checklist preechido. </p></font>

| ID  | Descrição                                                                                              | Avaliação |        Observações        |
| :-: | ------------------------------------------------------------------------------------------------------ | :-------: | :-----------------------: |
|  1  | O artefato possui Introdução?                                                                          |    Sim    |                           |
|  2  | O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                                  |    Sim    |                           |
|  3  | O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores? |    Sim    |                           |
|  4  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           |    Sim    |                           |
|  5  | Todos os textos estão na norma padrão?                                                                 |    Sim    |                           |
|  6  | Os cenários possuem detalhes contextuais de uso da aplicação envolvendo o usuário?                     |    Sim    |                           |
|  7  | Eles descrevem o comportamento e as experiência dos atores?                                            |    Sim    |                           |
|  8  | Cada ator possui objetivos que dirigem as tarefas que ele realiza?                                     |    Sim    |                           |
|  9  | Cada cenário tem um título que descreve brevemente a situação, os atores, referência a outro artefato? |    Sim    |                           |
| 10  | Nos cenários há o ambiente, o planejamento, as ações, os eventos, e a avaliação?                       |    Não    | Será justificado no texto |
| 11  | Os cenários são associados à alguma tarefa de uso diário do ator?                                      |    Sim    |                           |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

Com base na tabela preenchida, serão feitas considerações acerca de alguns itens da tabela.

### ID 10 - Nos cenários há o ambiente, o planejamento, as ações, os eventos, e a avaliação?

Os cenários não apresentam a avaliação do usuário,tendo apenas a aba de exceção para possíveis erros.

## Sugestões e melhorias

O artefato apresenta uma ótima descrição dos cenários de uso do software, e possui bastante qualidade e robustez, salvo alguns detalhes com relação aos pontos citados. Sugere-se, portanto, algumas melhorias a seguir:

- Incluir a avaliação do usuário em cada cenário, para que seja possível identificar o que o usuário pensa sobre o sistema e como ele se sente ao utilizá-lo;
- Incluir a metodologia utilizada para a criação dos cenários, visto que, atualmente possui somente o tópico de "Metodologia" porém sem nenhum corpo e texto.

## Bibliografia

> MACIEL, Geovana. Cenários. Repositório do grupo Bilheteria Digial da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/verificacao/grupo/etapa2/cenarios/>. Acesso em: 2 de dezembro 2023.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versões

| Versão | Data       | Descrição            | Autor(es)                                     | Revisor(es)                                          |
| ------ | ---------- | -------------------- | --------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 02/12/2023 | Criação do documento | [Felipe de Sousa](https://github.com/fsousac) | [Millena Queiroz](https://github.com/millenaqueiroz) |
