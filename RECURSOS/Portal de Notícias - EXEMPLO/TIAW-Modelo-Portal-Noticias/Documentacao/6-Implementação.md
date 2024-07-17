# Projeto da Solução

<span style="color:red">Pré-requisitos: <a href="4-Gestão-Configuração.md"> Ambiente e Ferramentas de Trabalho</a></span>

## Tecnologias Utilizadas

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.

A imagem a seguir ilustra a o fluxo do usuário em nossa solução. Assim
que o usuário entra na plataforma, ele é apresentado à tela inicial
(Tela 1) onde ele é confrontado com as opões de editar seu perfil ou
então visualizar sua galeria.

Caso ele opte por seguir pelo primeiro caminho (Editar Perfil), ele é
redirecionado para a tela de edição de perfil (Tela 2), onde pode
atualizar seus dados cadastrais. Nessa tela, o usuário também pode
escolher para editar sua foto de perfil. Ao selecionar essa opção, ele é
redirecionado para a Tela 3, onde ele a imagem expandida do perfil do
usuário é mostrado. Ao selecionar a opção para atualizar a imagem, uma
nova janela abre pedindo para o usuário fazer o upload da nova foto.
Assim que o processo termina um pop-up exibe o status para o usuário
(Tela 4) e o usuário é redirecionado para a Tela 2.

Caso o usuário opte seguir pelo segundo caminho (Visualizar Galeria) ele
é redirecionado para a Tela 5 com todas as fotos que o usuário possui. O
usuário pode clicar em um post qualquer para visualizar os detalhes do
post (Tela 6). Nessa tela, ele pode então escolher editar o post, sendo
redirecionado para a Tela 7. Ao editar as informações, o usuário pode
escolher salvar ou deletar o post. Em ambos os casos o status é
notificado para o usuário (Tela 8) e em seguida ele é redirecionado
para a Tela 2.

![Exemplo de UserFlow](images/userflow.jpg)
