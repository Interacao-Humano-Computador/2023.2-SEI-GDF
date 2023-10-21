# Características Gerais do SEI - GDF

## Introdução

A avaliação das capacidades e limitações da plataforma constitui uma das atividades recomendadas no <b>ciclo de vida de Mayhew</b>. Nesse processo, serão analisadas as oportunidades e restrições relacionadas a hardware, sistemas operacionais, ambientes gráficos, recursos de rede e outras características. No artefato, estão registradas as principais características do SEI GDF, suas restrições e potenciais oportunidades.
O objetivo desse artefato é reconhecer e esmiuçar as características do SEI GDF. Uma vez que essas características estejam compreendidas, será viável criar um design personalizado que leve em consideração as particularidades individuais da plataforma.

## Características da Plataforma

O SEI GDF é um sistema web de produção e gestão de documentos e processos eletrônicos desenvolvido pelo Tribunal Regional Federal da 4ª Região (TRF4) e cedido gratuitamente à administração pública. Ele é acessível através de qualquer dispositivo com conexão à internet e um navegador web. Dentre suas principais funcionalidades pode-se mencionar:
- Produção de documentos dentro do ambiente do próprio sistema e assinatura eletrônica;
- Controle do nível de acesso, gerenciamento e o trâmite de processos e documentos restritos e sigilosos, conferindo o acesso somente às unidades envolvidas ou a usuários específicos; 
- Criação de modelos de documentos;
- Fluxo de trâmite do processo;
- Controle de prazos; estatísticas da unidade e tempo do trâmite do processo;
- Pesquisa em todo teor, nos casos de processos públicos;
- Acesso externo ao processo; 

### Tecnologias utilizadas

No que diz respeito às tecnologias empregadas no SEI - GDF, de acordo com o manual de instalação da plataforma, são usadas: 
- PHP 
- MySQL server
- Memcache
- Java

### Características Negativas e Limitações

A seguir serão listadas as limitações e características negativas do site:

- A versão da plataforma na versão mobile é de difícil visualização visto que, pela quantidade de elementos, todos ficam bem menores em telas de tamanho reduzido. 
- Na opção "Pesquisa Pública" não está claramente indicado que para abrir o processo é necessário clicar no ícone de árvore.
- Os ícones usados na [plataforma logada do SEI - GDF](https://github-production-user-asset-6210df.s3.amazonaws.com/95441810/277069483-59223b97-5a6e-47af-97b4-ece8360c08a9.png) não são intuitivos;
- O site apresenta algumas funcionalidades que direcionam para guias externas, o que pode causar desorientação ao usuário.
- Não existe nenhum salvamento local na opção "Gerar Documento", então se houver alguma instabilidade do sistema/conexão, o documento em criação é perdido.


## Bibliografia

> - BARBOSA, S. D. J.; SILVA, B. S. **Interação Humano-Computador.** Rio de Janeiro: Elsevier, 2010.
> - **Componentes de Software - SEI** - Sistema Eletrônico de Informações. Disponível em: <https://softwarepublico.gov.br/social/sei/manuais/manual-de-instalacao/4.-componentes-de-software>. Acesso em: 21 de outubro de 2023.
> - **O que é o SEI?** – Portal SEI-GDF. Disponível em: <https://portalsei.df.gov.br/category/sobre-o-sei/o-que-e-o-sei/>. Acesso em: 21 de outubro de 2023.

## Histórico de Versão

| Versão | Data     | Descrição            | Autor(es)                                     | Revisor(es)                                          |
| ------ | -------- | -------------------- | --------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 21/10/23 | Criação do documento | [Millena Queiroz](https://github.com/millenaqueiroz) |  |
| `1.1`  | 21/10/23 | Reorganização da disposição das informações | [Millena Queiroz](https://github.com/millenaqueiroz) |  |
