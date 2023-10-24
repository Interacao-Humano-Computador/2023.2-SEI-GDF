# Princípios Gerais do Projeto

## Introdução

Para que um modelo conceitual seja eficaz, ele deve seguir princípios e diretrizes gerais que facilitem a aprendizagem e o uso por parte dos usuários. Esses princípios e diretrizes incluem: Restrições: O design deve ajudar os usuários a entender quais ações são possíveis em um determinado momento. Isso pode ser feito usando restrições, como limites de tempo ou condições de entrada; Clareza visual: O design deve tornar os aspectos importantes do sistema visualmente claros. Isso pode ser feito usando cores, ícones e outros elementos visuais para representar conceitos e ações; Mapeamentos naturais: O design deve usar mapeamentos naturais entre as intenções dos usuários, as ações necessárias, os efeitos das ações e a interpretação do estado do sistema. Isso torna o sistema mais fácil de aprender e usar.<a id="anchor_1" href="#REF1">^1^</a>.

## Metodologia

Para cada princípio geral, foram identificados os procedimentos que mais violam esse princípio. A análise foi dividida em dois subtópicos: definição, violação e sujestão de melhoria. Para identificar as violações, cada participante analisou o site individualmente, visando entender onde elas poderiam estar presentes e fornecer uma sujestão de melhoria para o problema. Além disso, a análise foi feita apenas na versão desktop do site.

## Correspondência com as Expectativas dos Usuários

### Definição

Neste tópico, o ponto principal é a naturalidade com a qual o usuário controla o sistema projetado. Sendo assim, necessita-se analisar as variáveis psicológicas e físicas as quais envolvem o universo daquele sistema. Portanto, deve-se certificar de que o usuário consiga determinar as seguintes relações: intenções e ações possíveis; entre ações e seus efeitos no sistema; entre o estado real do sistema e o que é percebido pela visão, audição ou tato; entre o estado percebido do sistema e as necessidades, intenções e expectativas do usuário<a id="anchor_1" href="#REF1">^1^</a>.

### Violação

Na Figura 1, é possível perceber a violação da Correspondência com a Expectativa do Usuário, dado que o filtro de setor é uma seleção de lista encontrada na parte do _header_ da página no canto direito (onde está selecionado "GTE"), ao mudá-lo não fica claro para o usuário em qual setor está selecionado, visto que não há nenhuma mudança visual além do próprio filtro.

<font size="3"><p style="text-align: center"><b>Figura 1</b> - Violação da Correspondência com as Expectativas dos Usuários.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/59223b97-5a6e-47af-97b4-ece8360c08a9" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/59223b97-5a6e-47af-97b4-ece8360c08a9">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> SEI-GDF (Acesso em: 20 de outubro 2023).</p></font>

### Sugestão de melhoria

Colocar o setor em uma área maior e em maior destaque da tela em que o usuário se encontra, tornando-o mais visível e compreensível, como sugere a Figura 2, na área em destaque.

<font size="3"><p style="text-align: center"><b>Figura 2</b> - Sugestão de melhoria para a Correspondência com as Expectativas dos Usuários.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/8a2d352a-0644-406a-a359-181cc29ddf5a" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/8a2d352a-0644-406a-a359-181cc29ddf5a">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> SEI-GDF (Acesso em: 20 de outubro 2023).</p></font>

## Simplicidade nas Estruturas das Tarefas

### Definição

O planejamento e a resolução de problemas requisitados devem ser reduzidos a fim de reduzir a complexidade de uma determinada tarefa, dado que tal pode ser desnecessariamente complexa. Portanto, a simplificação segue quatro abordagens tecnológicas<a id="anchor_1" href="#REF1">^1^</a>:

- manutenção da essência da tarefa, mas com diversos aparatos que auxiliam na realização de tal;
- explicitar de maneira visual o que antes era obscuro ao usuário, o que melhora o controle do usuário sobre a tarefa e o feedback recebido por ele;
- automatizar completamente ou parcialmente a tarefa;
- alterar a natureza da tarefa.

### Violação

Uma violação da Simplicidade nas Estruturas das Tarefas é claramente visível ao tentermos criar uma conta no SEI-GDF como usuário externo, sendo necessário preencher um formulário muito extenso, como mostrado na Figura 3, além disso ainda é necessário fazer uma autênticação pessoal para a criação da conta, dando uma complexidade muito grande para a tarefa.

<font size="3"><p style="text-align: center"><b>Figura 3</b> - Violação da Simplicidade nas Estruturas das Tarefas.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/c2fa1aaf-b258-42c7-843d-bfe7c1644ee4" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/c2fa1aaf-b258-42c7-843d-bfe7c1644ee4">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela de cadastro de usuário externo no SEI-GDF (Acesso em: 20 de outubro 2023).</p></font>

### Sugestão de melhoria

Simplificar o processo, se não for possível, explicitar ao usuário os passos para a criação da conta antes da tela do formulário.

## Equilíbrio entre Controle e Liberdade do Usuário

### Definição

A partir da ideia de que o usuário é o proprietário do computador, da interface e do ambiente de trabalho, quando o sistema é responsivo a ponto do usuário se sentir no comando de tal, o usuário aprende rapidamente e ganha um sentimento de maestria. No entanto, deve-se ressaltar a necessidade da busca por um equilíbrio, pois as restrições servem para guiar o usuário e evitar o acúmulo de informações, o que resulta em uma confusão mental para o sujeito. Portanto, o sistema deve, de maneira discreta, induzir o usuário a sentir que há somente uma única opção<a id="anchor_2" href="#REF2">^2^</a>.

### Violação

Neste tópico, o principal entrave é a liberdade do usuário, o site não permite ao usuário aprimorar sua busca para uma melhor organização, a busca não pode ser reorganizada pelo usuário. Por exemplo, ele não pode ordenar por data ou por região de origem. O padrão não muda e é sempre: por número do documento, como demonstrado na Figura 4.

<font size="3"><p style="text-align: center"><b>Figura 4</b> - Violação do Equilíbrio entre Controle e Liberdade do Usuário.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/584220f3-e970-42f6-a9b7-f8cb2c4f75a6" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/584220f3-e970-42f6-a9b7-f8cb2c4f75a6">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela de pesquisa como servidor em um exemplo de busca por tipo de documento (Acesso em: 22 de outubro 2023).</p></font>

### Sugestão de melhoria

Inserir no site mecanismos de organização das pesquisas para melhor gerenciamento pelo usuário, sugere-se como mostra a Figura 5.

<font size="3"><p style="text-align: center"><b>Figura 5</b> - Sugestão de melhoria para o Equilíbrio entre Controle e Liberdade do Usuário.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/8f6d682a-3f6f-4753-a471-ebd196ded8fd" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/8f6d682a-3f6f-4753-a471-ebd196ded8fd">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela de pesquisa como servidor em um exemplo de busca por tipo de documento (Acesso em: 22 de outubro 2023).</p></font>

## Consistência e Padronização

### Definição

Com o intuito de facilitar o aprendizado e o uso de um sistema, recomenda-se um padrão consistente, que perdura dentro do modelo conceitual, na interface<a id="anchor_1" href="#REF1">^1^</a>. No entanto, quando tal consistência for impossibilitada pela natureza do sistema, deve-se definir mapeamentos arbitários, ou seja, padronizar<a id="anchor_2" href="#REF2">^2^</a>.

### Violação

Ao entrar no site, vemos as opções do menu de cidadão e servidor, e abaixo vemos as notícias do SEI, as quais estão em um padrão de escala diferentes do resto do site. Violando o princípio, como mostra a Figura 6.

<font size="3"><p style="text-align: center"><b>Figura 6</b> - Violação da Consistência e Padronização.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/ea791716-fea0-42be-9d3f-356fd2124def" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/ea791716-fea0-42be-9d3f-356fd2124def">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela inicial do SEI-GDF mostrando a falta de padronização nas escalas do site (Acesso em: 22 de outubro 2023).</p></font>

### Sugestão de melhoria

Reorganizar e redimensionar as notícias para manter as imagens em um padrão de tamanho.

## Promoção da Eficiência do Usuário

### Definição

O espectro predominante neste tópico é o econômico. Sendo assim, a eficiência do usuário está relacionada ao custo, dado que as pessoas custam mais do que máquinas. Além disso, ao economizar tempo e esforço do usuário, realiza-se um investimento melhor do que economizar em processamento ou armazenamento. Portanto, é necessário suprimir a ociosidade do usuário, de forma que o trabalho do usuário não seja impedido pelo sistema: os processos acontecem em um plano de fundo enquanto o usuário trabalha em outras partes<a id="anchor_2" href="#REF2">^2^</a>.

### Violação

Neste tópico, o principal entrave é a liberdade do usuário, o site não permite ao usuário a volta à página inicial, uma vez que foi iniciado um processo como servidor. Ferindo o princípio e forçando o usuário a terminar a tarefa imediatamente como mostrado na Figura 7.

<font size="3"><p style="text-align: center"><b>Figura 7</b> - Violação da Promoção da Eficiência do Usuário.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/887e70ec-bcce-496e-af34-74fe89b04550" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/887e70ec-bcce-496e-af34-74fe89b04550">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela de Iniciar processo como Servidor (Acesso em: 22 de outubro 2023).</p></font>

### Sugestão de melhoria

Implementação de uma possibilidade de saída do usuário para a tela inicial, utilizando-se de avisos para confirmar o cancelamento do início do processo, como ilustra a Figura 8.

<font size="3"><p style="text-align: center"><b>Figura 8</b> - Sugestão de melhoria para a Promoção da Eficiência do Usuário.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/9a1ca529-9739-44de-a736-f889477ce743" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/9a1ca529-9739-44de-a736-f889477ce743">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela de Iniciar processo como Servidor (Acesso em: 22 de outubro 2023).</p></font>

## Antecipação

### Definição

Todo o tipo de informação essencial ao usuário naquele determinado momento deve ser fornecida ao usuário sem que ele precise requisitar tal ao sistema. Além disso, o software deve antecipar também situações com altas propabilidades de acontecimento, o que aumenta a responsividade do sistema<a id="anchor_3" href="#REF3">^3^</a>.

### Violação

Ao interagir com um processo, naturalmente é esperado que o servidor irá abri-lo mais vezes com o tempo. Entretanto, o site não disponibiliza nenhuma aba relacionada com "processos recentes" que demonstraria quais processos o usuário acessou recentemete, sendo mandatória uma busca do usuário sempre que deseja conferir um processo. Ferindo, portanto, o princípio da Antecipação como mostra a Figura 9.

<font size="3"><p style="text-align: center" id="FIG9"><b>Figura 9</b> - Violação da Antecipação.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/06dfc959-4e81-4580-af07-95d846330fa9" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/06dfc959-4e81-4580-af07-95d846330fa9">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela inicial do acesso como Servidor no SEI (Acesso em: 22 de outubro 2023).</p></font>

### Sugestão de melhoria

Inserir uma aba na página inicial chamada "Processos recentes" em que ficarão salvos os últimos processos que o usuário acessou, como demonstra a Figura 10.

<font size="3"><p style="text-align: center"><b>Figura 10</b> - Sugestão de melhoria para a Antecipação.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/e27b77b6-68e6-40be-be6a-8eac67e2d3db" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/e27b77b6-68e6-40be-be6a-8eac67e2d3db">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela inicial do acesso como Servidor no SEI (Acesso em: 22 de outubro 2023).</p></font>

## Visibilidade e Reconhecimento

### Definição

Antes que uma ação seja executada, o usuário precisa ter uma visão prévia das maneiras de como podem ser realizadas e das instruções para a sua execução. Ademais, a interface deve apresentar informações lógicas e disponíveis ao usuário naquele momento<a id="anchor_1" href="#REF1">^1^</a>.

### Violação

Também na página inicial do sevidor, temos o menu lateral e uma série de ícones para realizar ações dentro do site. No entanto, a parte de ícones é bem desconexa da função que o botão exerce e a área do menu lateral não possui nenhum ícone que facilite a pre-visualização do que cada opção realiza, cabendo ao usuário aprender sobre cada coisa, o que fere o princípio como mostra também a <a id="anchor_fig9" href="#FIG9">Figura 9</a>.

### Sugestão de melhoria

Alteração dos ícones para ícones mais claros e que ilustrassem melhor para qual finalidade é o botão no site.

## Conteúdo Relavante e Expressão Adequada

### Definição

Para o tópico de Conteúdo Relavante e Expressão Adequada, destacam-se quatro máximas<a id="anchor_4" href="#REF4">^4^</a>:

- máxima da qualidade: não se deve realizar especulações ou proferir mentiras;
- máxima da quantidade: a quantidade de informação deve respeitar um limite imposto pelos objetivos da conversa;
- máxima da relação ou relevância: tudo o que for comunicado deve ter relação explícita e relevante ao tópico em questão;
- máxima de modo ou clareza: as conversas devem ser precisas e sem excesso.

### Violação

Algumas áreas do menu lateral não tem um nome de fácil entendimento para cada área. Por exemplo, Base de conhecimento, Pontos de controle, etc. Demonstrando, portanto, a violação das expressões adequadas, ferindo o princípio como mostra a Figura 11.

<font size="3"><p style="text-align: center"><b>Figura 11</b> - Violação da Conteúdo Relavante e Expressão Adequada.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/8eeedde8-ce8e-4a31-94d6-98a65b1d8fa4" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/8eeedde8-ce8e-4a31-94d6-98a65b1d8fa4">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da aba lateral da página inicial do SEI-GDF (Acesso em: 22 de outubro 2023).</p></font>

### Sugestão de melhoria

Mudança de nome dos tópicos para nomes mais intuitivos ao usuário.

## Projeto para Erros

### Definição

Dado que tanto o usuário quanto o sistema são passíveis de erro, o sistema deve se preparar para os potenciais erros que podem ocorrer. Sendo assim, tal preparação deve informar a ocorrência do erro ao usuário e instruir como reverter a possível perda ou ação indesejada. Além disso, ações irreversíveis devem requisitar uma confirmação persistente do usuário<a id="anchor_1" href="#REF1">^1^</a>.

### Violação

Como mostrado na Figura 12, o sistema não indica nenhum aviso ao pesquisar sem especificar algum filtro e retorna o mesmo site sem respostas, fato que pode causar ao usuário uma confusão sobre o status do sistema, e ferindo, portanto, o princípio do Projeto para Erros.

<font size="3"><p style="text-align: center"><b>Figura 12</b> - Violação do Projeto para Erros.</p></font>

<center>
<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/26de2298-6993-487a-b42c-88ac1b379ec4" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/26de2298-6993-487a-b42c-88ac1b379ec4">
</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> ScreenShot da tela de pesquisa como servidor após realizar uma pesquisa sem filtros (Acesso em: 22 de outubro 2023).</p></font>

### Sugestão de melhoria

Demonstrar a necessidade da aplicação de filtros para a pesquisa, retornando uma resposta para o usuário que inserir a busca vazia.

## Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> MELO, Arthur; CAMPELO, Gabriel. Princípios Gerais. Repositório do grupo Bilheteria Digial da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/principios/>. Acesso em: 22 de outubro 2023.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> NORMAN, Don. The Psychology Of Everyday Things. Basic Books, New York, illustrated edition, 1988.

> <a id="REF2" href="#anchor_2">2.</a> TOGNAZZINI, Bruce. First Principles of Interaction Design (Revised & Expanded), 2014.

> <a id="REF3" href="#anchor_3">3.</a> COOPER, Alan. The Inmates Are Running the Asylum: Why High Tech Products Drive Us Crazy and How to Restore the Sanity (2nd Edition). Sams Publishing, 1999.

> <a id="REF4" href="#anchor_4">4.</a> REEVES, Byron e NASS, Clifford. The Media Equation: How People Treat Computers, Television, and New Media Like Real People and Places. Cambridge University Press/CSLI, Stanford, Calif, new edition, 1996.

## Histórico de Versão

| Versão | Data       | Descrição                                              | Autor(es)                                     | Revisor(es)                                     |
| ------ | ---------- | ------------------------------------------------------ | --------------------------------------------- | ----------------------------------------------- |
| `1.0`  | 20/10/2023 | Documentação dos Princípios Gerais.                    | [Felipe de Sousa](https://github.com/fsousac) | [Caio Mesquita](https://github.com/caiomesvie)  |
| `1.1`  | 22/10/2023 | Finalização da Documentação dos princípios             | [Felipe de Sousa](https://github.com/fsousac) | [João Pedro](https://github.com/JoosPerro.png)  |
| `1.2`  | 24/10/2023 | Inserção de propostas de melhoria (pós apresentação 3) | [Felipe de Sousa](https://github.com/fsousac) | [Lucas Caldas](https://github.com/lucascaldasb) |
