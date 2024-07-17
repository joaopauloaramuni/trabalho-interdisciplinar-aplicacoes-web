# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em
se desenvolver profissionalmente através de um mestrado fora do país,
pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está
buscando uma agência que o ajude a encontrar universidades na Europa
que aceitem alunos estrangeiros.


> Enumere e detalhe as personas da sua solução. Para
> tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
> Lembre-se que você deve ser enumerar e descrever precisamente e
> personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários.

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Amanda Alves  | visualizar as notícias mais relevantes do momento           | tomar ciência dos fatos das áreas que me interessam               |
|Amanda Alves       | visualizar notícias mais alinhadas com minha área de atuação                 | gastar menos tempo lendo notícias e dar foco naquelas que estão relacionadas com o meu trabalho |
|Amanda Alves  | manter um registro de notícias específicas sobre as quais possuo interesse particular | visualizar depois e manter um histórico de notícias que possam ser compartilhadas posteriormente |
|Carlos Gomes  | fazer comentários em notícias e reportar minha opinião | discutir com grupos de interesse comum |
|Carlos Gomes  | compartilhar notícias nas redes sociais em que faço parte | poder discutir com os amigos e colegas de trabalhos sobre temas de interesse |
|Amanda Alves  | poder realizar uma pesquisa sobre notícias acerca de um tema específico | localizar tópicos específicos e conseguir maior objetividade em algumas leituras |
|Carlos Gomes  | ler notícias tanto no desktop quanto no celular | ocupar o tempo quando estou esperando algo (ex: filas de supermercado) |
|Amanda Alves  | quero saber a data e a fonte das notícias lidas | confiar no conteúdo passado e na atualidade das notícias que recebo |


## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
| RF-01 | O site deve apresentar na página principal notícias dinâmicas obtidas por meio de canais de notícias da Internet (API) | Alta |
| RF-02 | O site deve apresentar, para cada notícia, uma imagem correspondente ao assunto apresentado (thumbnail) | Média |
| RF-03 | O site deve permitir ao usuário visualizar o texto completo da notícia com todos os detalhes da publicação | Média |
| RF-04 | O site deve oferecer um menu adicional que permita ao usuário visualizar notícias de fontes distintas (sources). | Média |
| RF-05 | O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um texto específico que será informado na caixa de pesquisa. | Alta |
| RF-06 | O site deve permitir visualizar as informações de contatos do mantenedor do site | Média |
| RF-07 | O site deve permitir o compartilhamento de notícias visualizadas em plataformas de redes sociais | Baixa |
| RF-08 | O site deve permitir salvar notícias preferidas | Baixa |
| RF-09 | O site deve permitir verificar as notícias salvas como preferidas | Baixa |
| RF-10 | O site deve permitir que usuários possam comentar notícias | Baixa |
| RF-11 | O site deve exibir os comentários registrados juntamente com a notícia exibida | Baixa |



### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
| RNF-01 | O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku);  | Alta |
| RNF-02 | O site deverá ser responsivo permitindo a visualização em um celular de forma adequada | Alta |
| RNF-03 | O site deve ter bom nível de contraste entre os elementos da tela em conformidade  | Média |
| RNF-04 | O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) | Alta |


## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
| RE-01 | O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 07/07/2020. | 
| RE-02 | O aplicativo deve se restringir às tecnologias básicas da Web no Frontend | 
| RE-03 | A equipe não pode subcontratar o desenvolvimento do trabalho. | 

