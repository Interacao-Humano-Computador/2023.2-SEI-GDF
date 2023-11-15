# Verificação dos Cenários

## Introdução

Este documento é de verificação do artefato de [Cenários](https://interacao-humano-computador.github.io/2023.2-NotaLegal/analise%20de%20requisitos/cenarios/) produzido pelo [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) que tem o projeto voltado ao site do programa governamental Nota Legal. Com base nisso, seus cenários serão verificados de acordo com as informações presentes no livro Interação-Humano-Computador de Barbosa e Silva.

## Metodologia

Para a verificação do artefato, a metodologia escolhida será baseada na inspeção de Fagan. Conforme proposta por ele, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos. Essa revisão é realizada através de uma checklist onde se tem uma lista com os defeitos mais comuns que deverão ser identificados, analisados e classificados.
A checklist, baseada no livro, será composta por 5 perguntas que serão o padrão exigido para a documentação e em seguida perguntas envolvendo o conteúdo do artefato.Na Tabela 1 estão expostos todas as perguntas abordadas para verficação do artefato, a versão utilizadas para a verificação será a: 1.10, feita no dia 13 de outubro de 2023.

<center>

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Checklist artefato cenários. </p></font>

| ID  |                                                   Descrição                                                    | Avaliação | Observações |
| :-: | :------------------------------------------------------------------------------------------------------------: | :-------: | :---------: |
|  1  |                                         O artefato possui Introdução?                                          |           |             |
|  2  |                     O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                      |           |             |
|  3  |     O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores?     |           |             |
|  4  |                  Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                  |           |             |
|  5  |                                     Todos os textos estão na norma padrão?                                     |           |             |
|  6  |                                   O artefato possui a metodologia utilizada?                                   |           |             |
|  7  |      Os cenários possuem Objetivo, Ambiente/Contexto, Recursos, Atores, Episódios, Restrições e Exceções?      |           |             |
|  8  |                      Lendo o texto, consigo imaginar a situação do cenário corretamente?                       |           |             |
|  9  | A modelagem de cenários englobam possíveis situações de erro e caminhos alternativos em pelo menos uma tarefa? |           |             |
| 10  |             A modelagem de cenários mostra tarefas de execução corriqueira do usuário no sistema?              |           |             |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

Na Tabela 1, os campos de "Avaliação" e "Observações" serão preenchidos no desenvolvimento em que haverá uma discussão a respeito de alguns itens. Para tal será utilizado o ID da pergunta.

## Desenvolvimento

O artefato foi verificado e gerou os resultados da Tabela 2, sendo possível identificar os tópicos faltantes e/ou concluídos.

<center>

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Checklist preechido. </p></font>

| ID  |                                                   Descrição                                                    | Avaliação  |        Observações         |
| :-: | :------------------------------------------------------------------------------------------------------------: | :--------: | :------------------------: |
|  1  |                                         O artefato possui Introdução?                                          |    Sim     |                            |
|  2  |                     O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                      |    Sim     |                            |
|  3  |     O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores?     |    Sim     |                            |
|  4  |                  Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                  |    Sim     |                            |
|  5  |                                     Todos os textos estão na norma padrão?                                     |    Sim     |                            |
|  6  |                                   O artefato possui a metodologia utilizada?                                   |    Sim     |                            |
|  7  |      Os cenários possuem Objetivo, Ambiente/Contexto, Recursos, Atores, Episódios, Restrições e Exceções?      | Incompleto | Será justificado no texto. |
|  8  |                      Lendo o texto, consigo imaginar a situação do cenário corretamente?                       |    Sim     | Será justificado no texto  |
|  9  | A modelagem de cenários englobam possíveis situações de erro e caminhos alternativos em pelo menos uma tarefa? |    Não     | Será justificado no texto. |
| 10  |             A modelagem de cenários mostra tarefas de execução corriqueira do usuário no sistema?              |    Sim     |                            |

<font size="3"><p style="text-align: center">Fonte: [Felipe de Sousa](https://github.com/fsousac).</p></font>

</center>

Com base na tabela preenchida, serão feitas considerações acerca de alguns itens da tabela.

### ID 7 - Os cenários possuem Objetivo, Ambiente/Contexto, Recursos, Atores, Episódios, Restrições e Exceções?

Analisando alguns cenários presentes no documento temos tópicos não deixam claros os fatores citados, mas outros sim. O cenário [Registrar nova reclamação](https://interacao-humano-computador.github.io/2023.2-NotaLegal/analise%20de%20requisitos/cenarios/#registrar-nova-reclamacao), por exemplo, não explicita diretamente esses fatores, já o cenário de [Consultar Estabelecimento](https://interacao-humano-computador.github.io/2023.2-NotaLegal/analise%20de%20requisitos/cenarios/#consultar-estabelecimento) deixa explícito o objetivo, ambiente/contexto, recursos, atores, episódios, restrições e exceções. Portanto, o artefato não está completo nesse quesito.

### ID 8 - Lendo o texto, consigo imaginar a situação do cenário corretamente?

Apesar de alguns cenários não deixarem claro os fatores citados no ID 7, é possível imaginar todas as situações corretamente, pois os cenários são bem descritos e de fácil entendimento.

### ID 9 - A modelagem de cenários englobam possíveis situações de erro e caminhos alternativos em pelo menos uma tarefa?

Os cenários citados englobam somente os "caminhos felizes" do sistema, desconsiderando usuários novos e erros de digitação, por exemplo.

## Sugestões e melhorias

O artefato apresenta uma ótima descrição dos cenários de uso do software, e possui bastante qualidade e robustez, salvo alguns detalhes com relação aos pontos citados. Sugere-se, portanto, algumas melhorias a seguir:

- Deixar explícito no inicio de cada cenário o objetivo, ambiente/contexto, recursos, atores, episódios, restrições e exceções a fim de facilitar a compreensão do leitor e agilizar seu entendimento acerca do assunto;
- Englobar nos cenários já criados alguns erros que o usuário pode vir a cometer, como por exemplo, digitar um CPF inválido ou um e-mail inválido e como o usuário se recuperaria desses erros;

## Bibliografia

> ROSA, Gabriel. Verificação do artefato Cenários. Repositório do grupo Nota Legal da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.2-NotaLegal/verificacao/Grupo%202/Entrega%202/cenarios/>. Acesso em: 15 de novembro 2023.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versões

| Versão | Data       | Descrição            | Autor(es)                                     | Revisor(es)                                          |
| ------ | ---------- | -------------------- | --------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 15/11/2023 | Criação do documento | [Felipe de Sousa](https://github.com/fsousac) | [Millena Queiroz](https://github.com/millenaqueiroz) |
