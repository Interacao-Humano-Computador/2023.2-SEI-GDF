# Cenários

## Introdução

Cenário no contexto de IHC é uma narrativa imaginária e contextual de um usuário realizando uma atividade. Ela é uma ferramenta utilizada no Design baseado em Cenários, com o objetivo de descrever de forma clara o e compreensiva um contexto específico de uso de uma parte da interface. Um cenário é uma hipótese do qual é extraído o perfil do usuário e seus objetivos, entre outros detalhes. Ao ler e discutir sobre o cenário, a equipe de design analisa e aprende como a interface influencia a atividade do usuário, facilitando encontrar alternativas adequadas para o problema. Esse processo envolvendo cenários é iterativa, tentando aprimorar a solução a cada passo.

O design baseado em cenários se divide basicamente em três atividades sucessivas, sempre com espaço para iteração e transformações de cenários. As atividades são:

1. Análise do problema: para análise e estudo do problema, todos os interessados na solução (stakeholders) participam, a fim de conhecer a situação atual. Então a equipe cria cenários baseados no que foi analisado a respeito do usuário, suas atividades, o contexto de uso, e as ferramentas e artefatos envolvidos;

2. Projeto de uma solução de IHC: criados os cenários que consolidam o que foi compreendido pela equipe de design, parte-se para elaboração de uma solução para os problemas descritos. Cenários são divididos em: cenários de atividade, que relatam principalmente as funcionalidades do sistema; cenários de informação especificam as informações oferecidas ao usuário pelo sistema; cenários de interação são os mais detalhados que os anteriores, e abordam as ações do usuário e as respectivas respostas do sistema;

3. Prototipação e avaliação da solução proposta: nesse estágio a solução é consolidada em forma de um protótipo, também sujeito a avaliação. Até nesse estágio os cenários são úteis e relevantes, baseado neles, a equipe pode avaliar o desenvolvimento e o resultado de processo. 

## Metodologia

## Modelo de Cenário

Um estudo obre o uso de cenários no desenvolvimento de software identificou várias formas de descrevê-los, incluindo texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. Entre essas opções, o texto estruturado se destacou como uma abordagem comum e, portanto, foi escolhida e adaptada para melhor entendimento e/ou aprendizado.

A **Tabela 1**, logo abaixo, apresenta um modelo utilizado para cada cenário.

<center>

**Tabela 1** - Modelo de cenários

| Elemento            | Descrição                                                  |
| :-----------------: | ---------------------------------------------------------- |
| Objetivo            | A finalidade ou meta a ser alcançada no cenário.           |
| Ambiente/Contexto   | Os detalhes da situação que influenciam a ação dos atores. |
| Recursos            | Objetos e elementos que interagem com os atores.           |
| Atores              | Indivíduos ou entidades que participam do cenário.         |
| Episódios           | Sequência de ações realizadas pelos atores no cenário.     |
| Restrições          | Possíveis obstáculos ou limitações nas ações dos atores.   |
| Exceção             | Eventos não usuais ou casos fora do padrão no cenário.     |

_Fonte: [Artur Ricardo](https://github.com/algorithmorphic)._

</center>

## Cenários Identificados

Os cenários identificados, tendo como base os usuários entrevistados e documentados no [Perfil de Usuário](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/blob/main/docs/analise-de-requisitos/perfil-de-usuario.md), e, também, as tarefas analisadas sob o método [GOMS](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/blob/main/docs/analise-de-requisitos/analise-de-tarefas/GOMS.md), estão apresentados nas tabelas 2, 3, 4 e 5:

### Cenário 01: Pesquisa Processual (Cidadão)

<center>

**Tabela 2** - Cenário 01

| Elemento            | Descrição |
| :-----------------: | --------- |
| Objetivo            | Realizar a pesquisa de um processo como cidadão. |
| Ambiente/Contexto   | Local: Em casa;<br>Tempo: Durante a noite;<br>Pré-condições: Acesso à Internet.|
| Recursos            | Internet, computador e site/plataforma do SEI - GDF. |
| Atores              | Um advogado. |
| Episódios           | - Guia o mouse para a aba meu Pesquisa processual, no menu Cidadão;<br>- Pressiona o botão;<br>- Guia o mouse para a caixa de texto dentre as disponíveis;<br>- Clica na opção desejada e digita os dados para a pesquisa;<br>- Seleciona uma ou mais opções de "Pesquisar em:" dentre as disponíveis;<br>- Seleciona uma das opões em "Data do Processo/Documento" dentre as disponíveis;<br>- Caso a opção selecionada seja "Período explícito", especifica as datas de início e fim do período desejado;<br>- Responde a caixa de Captcha presente na página; e<br>- Clica no botão "Pesquisar".|
| Restrições          | Fluxo de navegação intuitivo. |
| Exceção             | Falta de energia ou internet. |

_Fonte: [Artur Ricardo](https://github.com/algorithmorphic)._

</center>

### Cenário 02: Fazer a conferência da autenticação de documentos (Cidadão)

<center>

**Tabela 3** - Cenário 02

| Elemento            | Descrição |
| :-----------------: | --------- |
| Objetivo            | Fazer a conferência da autenticação de documentos como cidadão. |
| Ambiente/Contexto   | Local: No trabalho;<br>Tempo: Durante o dia;<br>Pré-condições: Acesso à Internet. |
| Recursos            | Internet, computador e site/plataforma do SEI - GDF. |
| Atores              | Um advogado. |
| Episódios           | - Guia o mouse para opção de autenticação de documentos, no menu Cidadão;<br>- Clica no botão;<br>- Guia o mouse para a caixa de texto "Código Verificador" e clica;<br>- Digita o código verificador;<br>- Guia o mouse para a caixa de texto "Código CRC" e clica;<br>- Digita o código CRC;<br>- Responde a caixa de Captcha presente na página; e<br>- Clica no botão "Pesquisar". |
| Restrições          | Fluxo de navegação intuitivo. |
| Exceção             | Falta de energia ou internet. |

_Fonte: [Artur Ricardo](https://github.com/algorithmorphic)._

</center>

### Cenário 03: Iniciar um processo (Servidor)

<center>

**Tabela 4** - Cenário 03

| Elemento            | Descrição |
| :-----------------: | --------- |
| Objetivo            | Iniciar um processo como servidor de um orgão. |
| Ambiente/Contexto   | Local: No trabalho;<br>Tempo: Durante o dia;<br>Pré-condições: Acesso à Internet. |
| Recursos            | Internet, computador e site/plataforma do SEI - GDF. |
| Atores              | Um servidor público. |
| Episódios           | - Guia o mouse para a caixa de texto de "Usuário" e clica;<br>- Digita o login do usuário;<br>- Guia o mouse para a caixa de texto de "Senha" e clica;<br>- Digita a senha do usuário;<br>- Guia o mouse para a caixa de seleção de "Órgão" e clica;<br>- Seleciona o órgão do usuário;<br>- (Opcional) Seleciona a opção de "Lembrar" para mantê-lo conectado para as próximas vezes que acessar o sistema;<br>- Clica no botão "Acessar";<br>- Guia o mouse para a opção 'Iniciar Processo' na barra lateral da página inicial;<br>- Clica no botão;<br>- Seleciona o Tipo do processo;<br>- Especifica o processo;<br>- Descreve os assuntos;<br>- Seleciona os Interessados;<br>- Faz observações desta unidade;<br>- Define nível de acesso; e<br>- Clica em "Salvar" para criar o Processo. |
| Restrições          | Fluxo de navegação intuitivo. |
| Exceção             | Falta de energia ou internet. |

_Fonte: [Artur Ricardo](https://github.com/algorithmorphic)._

</center>

### Cenário 04: Pesquisar um processo (Servidor)

<center>

**Tabela 5** - Cenário 04

| Elemento            | Descrição |
| :-----------------: | --------- |
| Objetivo            | Encontrar um processo a partir de alguma informação que possui partindo da área principal, após o login. |
| Ambiente/Contexto   | Local: Em casa;<br>Tempo: Durante a noite;<br>Pré-condições: Acesso à Internet. |
| Recursos            | Internet, computador e site/plataforma do SEI - GDF. |
| Atores              | Um servidor público. |
| Episódios           | - Guia o mouse para a caixa de texto de "Usuário" e clica;<br>- Digita o login do usuário;<br>- Guia o mouse para a caixa de texto de "Senha" e clica;<br>- Digita a senha do usuário;<br>- Guia o mouse para a caixa de seleção de "Órgão" e clica;<br>- Seleciona o órgão do usuário;<br>- (Opcional) Seleciona a opção de "Lembrar" para mantê-lo conectado para as próximas vezes que acessar o sistema;<br>- Clica no botão "Acessar";<br>- Guia o mouse para a opção 'Pesquisa' na barra lateral da página inicial;<br>- Clica no botão;<br>- Escolhe uma ou mais áreas para filtrar;<br>- Guia o mouse para a caixa de texto ou caixa de seleção e a preenche; e<br>- Clica no botão "Pesquisar".|
| Restrições          | Fluxo de navegação intuitivo. |
| Exceção             | Falta de energia ou internet. |

_Fonte: [Artur Ricardo](https://github.com/algorithmorphic)._

</center>

## Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.
>
> <a id="REF1" href="#anchor_1">2.</a> CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf. Acesso em 16 de outubro de 2023.
>
> <a id="REF1" href="#anchor_1">3.</a> Cenários Identificados, Banco Central do Brasil. Disponível em: <<https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/cenarios?id=cen%c3%a1rios-identificados>>. Acesso em 16 de outubro de 2023.

## Histórico de Versões

| Versão | Data       | Descrição                             | Autor(es)                                           | Revisor(es) |
| ------ | ---------- | ------------------------------------- | --------------------------------------------------- | ----------- |
| `1.0`  | 15/10/2023 | Criação dos cenários.                 | [Artur Ricardo](https://github.com/algorithmorphic) | [Felipe de Sousa](https://github.com/fsousac)|
| `2.0`  | 15/10/2023 | Atualização da estrutura do artefato. | [Artur Ricardo](https://github.com/algorithmorphic) | [Millena Queiroz](https://github.com/millenaqueiroz)|
| `2.1`  | 16/10/2023 | Atualização dos dados do artefato.    | [Artur Ricardo](https://github.com/algorithmorphic) |[João Pedro](https://github.com/JoosPerro)|
