# AAI-NOITE-44035-THAIS
AAI NOITE UNIFECAF 44035 THAIS GABRIELE

Exercício 1:

// Comandos React Native

	// Passo 1: Instalação do Expo  → Prompt de comando
npm install -g expo-cli                       

 // aguarde até que a instalação seja concluída


// Passo 2: Criação do novo projeto  →  ainda no Prompt de comando

// comando para criar a nova pasta
mkdir nome_da_pasta 

// comando para acessar a pasta criada
cd nome_da_pasta

// comando para criar um novo projeto Expo
	expo init nomedoprojeto

//Configuração do projeto 
//Selecione o template “Blank” (aplicação vazia)e aperte o “Enter” 
	// aguarde até que a instalação seja concluída
	// comando para acessar a pasta do projeto
		cd nomedoprojeto
	
	//comando para abrir o vscode já com o projeto carregado nele
		code .
	//Pronto! agora você tem o ambiente criado

// Passo 3: Subindo projeto no GitHub
	
	// No CMD digite as seguintes linhas de codigos:

		//para navegar até a pasta do seu projeto
			cd caminho/do/projeto

		//para inicializar um repositório Git
			git init
	
		//para adicionar todos os arquivos do projeto no repositório
			git add .

		//Faça um Commit
			git commit -m "Primeiro commit"

		//Agora acesse seu git hub e crie um repositório, após a criação você irá receber uma URL, copie ela.

		// Adicionando a URL como repositório remoto
			git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git

		// Por fim, envie seu projeto para o GitHub:
			git push -u origin master


			
			
Exercício 2:

//Acessando o projeto da aula

	//Comando para clonar o repositório
		git clone <URL do repositório>

	//Navegue até o diretório do projeto
		cd nome-do-repositorio

	//Comando para obter as alterações mais recentes do repositório
		git pull

	//Para mudar para outra branch
		git checkout nome-da-branch

	//Comando para adicionar todos os arquivos 
		git add .
	
	//Comando para acessar o projeto atualizado e completo direto no vscode
		code .
