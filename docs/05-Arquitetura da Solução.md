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


## Hospedagem

O site utiliza a plataforma do Firebase Hosting como ambiente de hospedagem do site do projeto. O site é mantido no ambiente da URL: 

                                		  https://link_exemplo.firebaseapp.com 
				  		   (Apenas exemplo - ainda será feito)

A publicação do site no Firebase Hosting é feita por meio de uma submissão do projeto (push) via git para o repositório remoto que se encontra no endereço: 

                                		 https://git.firebasecom/link_exemplo.git 
				   		   (Apenas exemplo - ainda será feito)


