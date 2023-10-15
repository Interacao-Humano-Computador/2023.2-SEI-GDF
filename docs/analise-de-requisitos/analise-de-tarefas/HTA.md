# Análise Hierárquica de Tarefas (HTA – Hierarchical Task Analysis)

## Introdução

HTA, ou Análise Hierárquica de Tarefas, é uma abordagem essencial na área de Interação Humano-Computador (IHC) utilizada para compreender e otimizar a interação entre usuários e sistemas computacionais. Esta técnica visa descompor uma tarefa complexa em hierarquias de sub-tarefas mais gerenciáveis e compreensíveis. A HTA ajuda a identificar os objetivos do usuário, as operações necessárias para alcançá-los e as estratégias que os usuários adotam para executar essas operações. Ao decompor as tarefas em níveis, desde metas até ações específicas, a HTA proporciona uma visão detalhada da interação, permitindo o design eficaz de sistemas mais intuitivos e eficientes para os usuários.
A HTA pode ser representada de forma visual, seja por meio de uma tabela ou de um diagrama, utilizando a notação indicada na figura 1.

</br>

<font size="4"><p style="text-align: center"><b>Figura 1</b> - Notação diagrama HTA.</p></font>

<center>

![image](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/60625345/5cbaabb1-5363-43c7-ac3a-7c941fde2965)

</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> BARBOSA e SILVA, 2010.<a id=anchor_1 href="#REF1"><sup>1</sup></a></p></font>

## Motivo da escolha

A escolha da Análise Hierárquica de Tarefas (HTA) para o projeto se deve à necessidade de compreender profundamente a interação entre os usuários e o sistema. A HTA oferece uma estrutura sistemática e hierárquica para desmembrar as complexas atividades que os usuários realizam ao utilizar o SEI GDF, permitindo a identificação das metas dos usuários e das sub-tarefas envolvidas.

Obs: Durante o processo de análise subentende-se que o usuário já havia acessado o site, portanto as ações realizadas são relativas somente aos processos internos do site.

## Análise de Tarefas

Para a análise das tarefas, ao observar o site, foram identificados duas principais áreas, a de Cidadão e a de Servidor, como mostra a Figura 2.

<font size="4"><p style="text-align: center"><b>Figura 2</b> - Áreas de acesso SEI - GDF.</p></font>

![image](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/4566468e-ff46-44f6-8126-b813adfa489e)

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Felipe de Sousa](https://github.com/fsousac) (Acesso em: 14 de outubro 2023)</p></font>

### Pesquisa Processual (Cidadão)

Nessa tarefa, o usuário possui o objetivo de realizar a pesquisa de um processo como cidadão. A figura 3 apresenta o diagrama HTA relativa a tarefa, já a tabela 4 representa o mesmo HTA em tabela.
<br/>
<font size="4"><p style="text-align: center"><b>Figura 3</b> - Diagrama de Pesquisa Processual (Cidadão)</p></font>

![image](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/60625345/eaa373cb-2d24-4c44-92bf-939904852ddb)

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Millena Queiroz](https://github.com/millenaqueiroz) </p></font>

</br>

<font size="4"><p style="text-align: center"><b>Figura 4</b> - Tabela de Pesquisa Processual (Cidadão)</p></font>


<center>

| Objetivos/Operações                     | Problemas e Recomendações                                             |
| -------------------------------------- | -------------------------------------------------------------------- |
| 0. Pesquisa processual<br> 1/2 | <b>Input:</b> formulário de busca de processo ou documento<br> <b>Feedback:</b> São retornados os processos relacionados a busca.<br> <b>Plano:</b> Informar dados de busca e depois ter retorno de processos.
| 1.Inserir número do processo ou documento 1+2 |  <b>Input:</b> número do processo ou documento.<br> <b>Recomendação:</b> Especificar a relação de dependência com o campo "Pesquisar em"                                                                                                                                                                 |
| 2. Realizar pesquisa livre 1+2 | <b>Input:</b> Texto relacionado ao processo. <br> <b>Recomendação 1:</b> Especificar a relação de dependência com o campo "Pesquisar em"<br> <b>Recomendação 2:</b> Não fica claro a situação de independência entre o campo pesquisa livre e o campo inserir número do processo.                                                                 |
| 2.1 Selecionar onde pesquisar 1/2 | <b>Input:</b> Seleção de opção documentos gerados, externos ou processos. <br>                                                                      |
| 2.2 Especificar interessado/remetente (opcional) |                                                                      |
| 2.3 Especificar unidade geradora (opcional) |                                                                      |
| 2.4 Especificar tipo do processo (opcional) |                                                                      |
| 2.5 Especificar tipo do documento (opcional) |                                                                      |
| 2.6 Especificar data do processo/documento (opcional) |                                                                      |
| 3. Completar Captcha 1>2 |                                                                      |
| 4. Visualizar o resultado da busca |  <b>Input:</b> formulário de busca de processo ou documento<br> <b>Feedback:</b> São retornados os processos relacionados a busca.<br>   <b>Plano:</b> mostrar processos.                                                                 |

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Millena Queiroz](https://github.com/millenaqueiroz) </p></font>

### Fazer a conferência da autenticação de documentos (Cidadão)

Nessa tarefa, o usuário possui o objetivo de fazer a conferência da autenticação de documentos como cidadão. A figura 5 apresenta o diagrama HTA relativa a tarefa, já a tabela 6 representa o mesmo HTA em tabela.

<font size="4"><p style="text-align: center"><b>Figura 5</b> - Diagrama de Conferência de Autenticação de documentos (Cidadão)</p></font>

<center>

![image](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/60625345/7b908d4e-2528-4832-8ce0-08ccd5be03f8)
</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Millena Queiroz](https://github.com/millenaqueiroz) </p></font>

<font size="4"><p style="text-align: center"><b>Figura 6</b> - Tabela de Conferência de Autenticação de documentos (Cidadão)</p></font>

<center>

| Objetivos/Operações                        | Problemas e Recomendações                                             |
| ----------------------------------------- | -------------------------------------------------------------------- |
| Autenticação de documentos                |  <b>Input:</b> formulário de verificação de documento <br> <b>Feedback:</b>É retornado se documento é válido ou não <br> <b>Plano:</b> Informar dados de busca e depois ter retorno da validade dos processos.                                                                      |
| 1. Especificar Código Verificador   1+2       | <b>Input:</b> código verificador contido no documento<br><b>Recomendação:</b> mostrar obrigatoriedade do campo                                                                       |
| 2. Especificar Código CRC 1+2                 | <b>Input:</b> código CRC<br><b>Recomendação:</b> mostrar obrigatoriedade do campo                                                                                     |
| 3. Completar Captcha 1>2                      |                                                                        |
| 4. Conferir autenticação | <b>Feedback:</b>É retornado se documento é válido ou não <br>|
</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Millena Queiroz](https://github.com/millenaqueiroz) </p></font>

### Iniciar um processo (Servidor)

Nessa tarefa, o usuário possui o objetivo de iniciar um processo como servidor de um orgão. A figura 7 apresenta o diagrama HTA relativa a tarefa, já a tabela 8 representa o mesmo HTA em tabela.

<font size="4"><p style="text-align: center"><b>Figura 7</b> - Diagrama de iniciar processo (Servidor)</p></font>

<center>

![image](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/60625345/1594bd1e-8437-414b-b70b-3b2264f7445f)
</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Millena Queiroz](https://github.com/millenaqueiroz) </p></font>
<br/>

<font size="4"><p style="text-align: center"><b>Figura 8</b> - Tabela de iniciar processo (Servidor)</p></font>
<center>

| Objetivos/Operações                       | Problemas e Recomendações                                             |
| ---------------------------------------- | -------------------------------------------------------------------- |
| 0. Iniciar processo                          |  <b>Input:</b> formulário de criação de processo <br> <b>Feedback:</b>É retornado se documento foi criado e o seu respectivo número. <br> <b>Plano:</b> Retornar número do processo.                                                                       |
| 1. Selecionar tipo do processo            |  <b>Input:</b> Campo de seleção <br> <b>Feedback:</b>O usuário é redirecionado para o próximo passo do formulário <br>                                                                      |
| 2.1.1 Especificar o processo                 |                                                                        |
| 2.1.2 Descrever os assuntos                  |                                                                        |
| 2.1.3 Selecionar os Interessados             |                                                                        |
| 2.1.4 (Opcional) Fazer observações desta unidade |                                                                     |
| 2.1.5 Definir nível de acesso                | <b>Input:</b> Campo de seleção <br> <b>Feedback:</b>Se caso o processo for restrito é mostrado um campo de hipótese legal. <br>                                                                      |
| 3. Enviar processo |<b>Input:</b> formulário de criação de processo <br> <b>Feedback:</b>É retornado se documento foi criado e o seu respectivo número. <br> <b>Plano:</b> Retornar número do processo.           |
</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Millena Queiroz](https://github.com/millenaqueiroz) </p></font>

### Pesquisar um processo (Servidor)


Nessa tarefa, o usuário possui o objetivo de encontrar um processo a partir de alguma informação que possui partindo da área principal, após o login.

<font size="4"><p style="text-align: center"><b>Figura 9</b> - Diagrama de iniciar processo (Servidor)</p></font>

<center>

![image](https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/60625345/eb5c3da6-9e44-4ea2-aeb5-1733c6a44406) 

</center>

<font size="4"><p style="text-align: center"><b>Figura 10</b> - Tabela de pesquisar processo (Servidor)</p></font>
<center>

| Objetivos/Operações                                        | Problemas e Recomendações                                              |
| --------------------------------------------------------- | --------------------------------------------------------------------- |
| Busca e Pesquisa                                           | <b>Input:</b> formulário de busca de processo ou documento<br> <b>Feedback:</b> São retornados os processos relacionados a busca.<br> <b>Plano:</b> Informar dados de busca e depois ter retorno de processos.                                                                         |
| 1. Fazer login                                              |                                                                         |
| 2. Selecionar pesquisa                                      |   <b>Input:</b> número do processo ou documento.<br> <b>Recomendação:</b> Especificar a relação de dependência com o campo "Pesquisar em"                                                                                                                          |
| 2.1 Selecionar onde pesquisar                                |                                                                         |
| 2.1.2 Especificar texto para a pesquisa, órgão gerador, unidade geradora, o assunto... | |
| 3. Pesquisar processo                                       | <b>Input:</b> formulário de busca de processo ou documento<br> <b>Feedback:</b> São retornados os processos relacionados a busca.<br> <b>Plano:</b> Informar dados de busca e depois ter retorno de processos.  |


</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Millena Queiroz](https://github.com/millenaqueiroz) </p></font>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. **Interação Humano-Computador.** Rio de Janeiro: Elsevier, 2010.

## Histórico de Versão

| Versão | Data     | Descrição            | Autor(es)                                     | Revisor(es)                                          |
| ------ | -------- | -------------------- | --------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 14/10/23 | Criação do documento | [Millena Queiroz](https://github.com/millenaqueiroz) |  |
| `1.1`  | 14/10/23 | Correção de enumeração de tarefas | [Millena Queiroz](https://github.com/millenaqueiroz) |  |