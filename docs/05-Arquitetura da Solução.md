# Arquitetura da Solução

A seguir, apresentamos os detalhes técnicos da solução elaborada relativos à hospedagem e aos componentes que fazem parte da solução.

## Diagrama de componentes
![image](https://user-images.githubusercontent.com/106809153/193957455-96a156f0-a080-45cd-a9aa-c24b9643dcad.png)
                            
			    Arquitetura da Solução

A solução implementada conta com os seguintes módulos:

Navegador - Interface básica do sistema 

    Página Web - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
    
    Local Storage - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
    
    Categorias – opções de dados/informações a ser visualizadas;
	
    Anotações importantes – inserção de dados pelos usuários sobre as consultas/exames marcados.
	
    Hospedagem - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 


Inclua um diagrama da solução e descreva os módulos e as tecnologias que fazem parte da solução. Discorra sobre o diagrama.

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

![Exemplo de UserFlow](img/userflow.jpg)


## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.


## Hospedagem

O site utiliza a plataforma do Firebase Hosting como ambiente de hospedagem do site do projeto. O site é mantido no ambiente da URL: 

                                		  https://link_exemplo.firebaseapp.com 
				  		   (Apenas exemplo - ainda será feito)

A publicação do site no Firebase Hosting é feita por meio de uma submissão do projeto (push) via git para o repositório remoto que se encontra no endereço: 

                                		 https://git.firebasecom/link_exemplo.git 
				   		   (Apenas exemplo - ainda será feito)


