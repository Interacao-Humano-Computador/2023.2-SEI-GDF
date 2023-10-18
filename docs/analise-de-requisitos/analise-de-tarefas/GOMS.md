# GOMS (Goals, Operators, Methods and Selection Rules)

## Introdução

O método GOMS (Goals, Operators, Methods, Selection Rules) é uma abordagem de análise de tarefas que descreve as etapas que os usuários seguem para realizar uma tarefa em um sistema. O GOMS é baseado em um conjunto de regras que descrevem como os objetivos dos usuários são alcançados por meio da seleção de operadores, métodos e regras de seleção. O método é útil para avaliar a eficiência e usabilidade de interfaces de usuário e sistemas, além de ajudar na identificação de possíveis problemas e áreas de melhoria.

As tarefas são descritas da seguinte forma:

- Objetivos: Representam as metas que os usuários desejam alcançar por meio do uso do sistema. Por exemplo, um objetivo de um usuário pode ser "enviar um e-mail" ou "abrir um documento".
- Operadores: São as ações cognitivas ou físicas que os usuários podem realizar para atingir um objetivo. Por exemplo, um operador pode ser "digitar um endereço de e-mail" ou "clicar em um botão".
- Métodos: São sequências de operadores que os usuários podem seguir para atingir um objetivo. Por exemplo, um método para enviar um e-mail pode ser "abrir o cliente de e-mail", "digitar o endereço do destinatário", "digitar o assunto do e-mail" e "digitar o corpo do e-mail".
- Regras de seleção: São regras que os usuários usam para decidir qual método usar para atingir um objetivo. Por exemplo, uma regra de seleção pode ser "se o usuário já tiver um e-mail aberto, use o método de responder ao e-mail".

## Motivo da escolha

Dos modelos de análise de tarefas apresentados na disciplina, escolhemos o CNM-GOMS porque ele é frequentemente usado para prever o desempenho dos usuários em várias tarefas. Isso significa que podemos identificar pontos específicos em que os usuários podem se confundir ou cometer erros. Ao corrigir esses problemas, podemos melhorar a experiência do usuário.

Além disso, o CNM-GOMS é baseado em uma compreensão sólida da cognição humana. Isso significa que ele é mais preciso e confiável do que outros modelos de análise de tarefas. Ele também é detalhado, o que permite a identificação de problemas específicos. Por fim, o CNM-GOMS é uma técnica comprovada e estabelecida na área de design de interação.

Obs: Durante o processo de análise subentende-se que o usuário já havia acessado o site, portanto as ações realizadas são relativas somente aos processos internos do site.

## Análise de Tarefas

Para a análise das tarefas, ao observar o site, foram identificados duas principais áreas, a de _Cidadão_ e a de _Servidor_, como mostra a Figura 1.

<font size="3"><p style="text-align: center"><b>Figura 1</b> - Áreas de acesso SEI - GDF.</p></font>

<center>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/4566468e-ff46-44f6-8126-b813adfa489e" data-origin="https://github.com/Interacao-Humano-Computador/2023.2-SEI-GDF/assets/95441810/4566468e-ff46-44f6-8126-b813adfa489e" alt="image">

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> https://portalsei.df.gov.br (Acesso em: 14 de outubro 2023).</p></font>

### Pesquisa Processual (Cidadão)

Nessa tarefa, o usuário possui o objetivo de realizar a pesquisa de um processo como cidadão.

```
GOAL 0: Fazer a pesquisa de um processo/documento.
    GOAL 1: Acessar aba de pesquisa processual
        OP 1.1: Guiar o mouse para a aba meu Pesquisa processual, no menu Cidadão
        0P 1.2: Pressionar o botão
    GOAL 2: Descrever o processo desejado
        OP 2.1: Guiar o mouse para a caixa de texto dentre as disponíveis (Nº do Processo ou Documento, Pesquisa Livre, Interessado / Remetente, Unidade Geradora, Tipo do Processo, Tipo do Documento)
        OP 2.2: Clicar na opção desejada e digitar os dados para a pesquisa
        OP 2.3: Selecionar uma ou mais opções de "Pesquisar em:" dentre as disponíveis (Processos, Documentos Gerados e Documentos Externos)
        OP 2.4: Selecionar uma das opões em "Data do Processo/Documento" dentre (Período explícito, 30 dias e 60 dias)
        OP 2.4.1: Caso a opção selecionada seja "Período explícito", especificar as datas de início e fim do período desejado
        OP 2.5: Responder a caixa de Captcha presente na página
        OP 2.6: Clicar no botão "Pesquisar"

```

### Fazer a conferência da autenticação de documentos (Cidadão)

Nessa tarefa, o usuário possui o objetivo de fazer a conferência da autenticação de documentos como cidadão.

```
GOAL 0: Fazer a conferência da autenticação de documentos
    GOAL 1: Acessar aba de autenticação de documentos
        OP 1.1: Guiar o mouse para opção de autenticação de documentos, no menu Cidadão
        0P 1.2: Clicar no botão
    GOAL 2: Inserir os dados para a conferência
        OP 2.1: Guiar o mouse para a caixa de texto "Código Verificador" e clicar
        OP 2.2: Digitar o código verificador
        OP 2.3: Guiar o mouse para a caixa de texto "Código CRC" e clicar
        OP 2.4: Digitar o código CRC
        OP 2.5: Responder a caixa de Captcha presente na página
        OP 2.6: Clicar no botão "Pesquisar"

```

### Iniciar um processo (Servidor)

Nessa tarefa, o usuário possui o objetivo de iniciar um processo como servidor de um orgão.

```
GOAL 0: Iniciar um processo
    GOAL 1: Acessar o SEI
        OP 1.1: Guiar o mouse para a caixa de texto de "Usuário" e clicar
        OP 1.2: Digitar o login do usuário
        OP 1.3: Guiar o mouse para a caixa de texto de "Senha" e clicar
        OP 1.4: Digitar a senha do usuário
        OP 1.5: Guiar o mouse para a caixa de seleção de "Órgão" e clicar
        OP 1.6: Selecionar o órgão do usuário
        OP 1.7: (Opcional) Selecionar a opção de "Lembrar" para mantê-lo conectado para as próximas vezes que acessar o sistema.
        OP 1.8: Clicar no botão "Acessar"
    GOAL 2: Iniciar a criação de um processo
        OP 2.1: Guiar o mouse para a opção 'Iniciar Processo' na barra lateral da página inicial
        OP 2.2: Clicar no botão
        OP 2.3: Selecionar o Tipo do processo
        OP 2.4: Especificar o processo
        OP 2.5: Descrever os assuntos
        OP 2.6: Selecionar os Interessados
        OP 2.7: Fazer observações desta unidade
        OP 2.8: Definir nível de acesso
        OP 2.9: Clicar em "Salvar" para criar o Processo
```

### Pesquisar um processo (Servidor)

Nessa tarefa, o usuário possui o objetivo de encontrar um processo a partir de alguma informação que possui partindo da área principal, após o login.

```
GOAL 0: Encontrar Processo
    GOAL 1: Acessar o SEI
        OP 1.1: Guiar o mouse para a caixa de texto de "Usuário" e clicar
        OP 1.2: Digitar o login do usuário
        OP 1.3: Guiar o mouse para a caixa de texto de "Senha" e clicar
        OP 1.4: Digitar a senha do usuário
        OP 1.5: Guiar o mouse para a caixa de seleção de "Órgão" e clicar
        OP 1.6: Selecionar o órgão do usuário
        OP 1.7: (Opcional) Selecionar a opção de "Lembrar" para mantê-lo conectado para as próximas vezes que acessar o sistema.
        OP 1.8: Clicar no botão "Acessar"
    GOAL 2: Pesquisar por um processo
        OP 2.1: Guiar o mouse para a opção 'Pesquisa' na barra lateral da página inicial
        OP 2.2: Clicar no botão
        (Sel. Rule: O usuário vai pesquisar com ao menos um dos filtros disponíveis)
            OP 2.3: Escolher uma ou mais áreas para filtrar, sendo elas Texto para Pesquisa Órgão Gerador, Unidade Geradora, Assunto,
                    Assinatura /Autenticação, Contato e informar se é Interessado, Remetente ou Destinatário, Descrição, Observação desta Unidade,
                    Número (Processo ou Documento) do SEI, Tipo do Processo, Tipo do Documento, Número / Nome na Árvore SEI,
                    Data do Documento (Período específico, 30 dias ou 60 dias), Usuário Gerador
            OP 2.4: Guiar o mouse para a caixa de texto ou caixa de seleção e preenche-la
            OP 2.5: Clicar no botão "Pesquisar"

```

### Gerar Documento (Servidor)

Nessa tarefa, o usuário possui o objetivo de gerar um documento num processo, considerando que ele possui acesso e buscou (ou iniciou) o processo no qual o documento será gerado.

```
GOAL 0: Gerar um documento
    GOAL 1: Incluir documento
        OP 1.1: Selecionar com o mouse ícone de novo documento, representado por uma folha em branco e um sol
        OP 1.2: Selecionar o ícone verde com o sinal '+' para expandir as opções de tipo do documento
    GOAL 2: Especificar o documento
        OP 2.1: Guiar o mouse para a caixa de texto de "Escolha o Tipo de Documento"
        OP 2.2: Digitar o tipo de documento desejado
        OP 2.3: Selecionar a sugestão oferecida pelo sistema logo abaixo da caixa de texto
    GOAL 3: Detalhar o documento
        OP 3.1: Selecionar uma opção em "Texto Inicial"
        OP 3.2: (Opcional) Preencher campo "Descrição"
        OP 3.3: Selecionar uma ou mais opções em "Interessados"
        OP 3.4: Selecionar uma ou mais opções em "Destinatários"
        OP 3.5: (Opcional) Selecionar opção em "Classificação por assuntos"
        OP 3.6: (Opcional) Preencher campo "Observações desta Unidade"
        OP 3.7: Selecionar opção em "Nível de Acesso"
        (Sel. Rule: Se o usuário selecionar um nível com restrições, ele deve especificar a hipótese legal)
            OP 3.8: Selecionar opção em "Hipóteste Legal"
        OP 3.9: Clicar em "Confirmar Dados"
        (Sel. Rule: Se os pop-ups estiverem bloqueados, o usuário deve abrir o documento manualmente)
            OP 3.10: Selecionar ícone "Editar Conteúdo", representado visualmente por um pergaminho e uma caneta
        OP 3.11: Editar conteúdo do documento
        
```

## Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> ALVES, Douglas; MACIEL, Geovanna. **GOMS (Goals, Operators, Methods and Selection Rules).** Repositório do grupo Bilheteria Digial da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <<https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/goms/>>. Acesso em: 14 de outubro 2023.

## Histórico de Versão

| Versão | Data     | Descrição            | Autor(es)                                     | Revisor(es)                                          |
| ------ | -------- | -------------------- | --------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 14/10/23 | Criação do documento | [Felipe de Sousa](https://github.com/fsousac) | [Millena Queiroz](https://github.com/millenaqueiroz) |
