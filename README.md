#Curso Front-End
### EBAC
# Git
## conceitos versionamento
 -histórico
 -controle de versâo
 -Quem alterou
 -O quê alterou
 -Quando alterou
 -Todos os arquivos
 -Evoluçâo contínua


 Arquivo A | Versão 1 | Versão 2
 Arquivo b | Versão 1 | Versão 2
 
 ## Instalação do Git
 git-scm.com/
 Linux (apt-get): sudo apt-get install git
 mec (brew): brew install git 
 ## Criar conta no Github

 ## Clonar o projeto
 git clone https://github.com/EduardoNunesFarias/Curso-Front-End.git
 


 ## commits
 Informação de Alteração
<<<<<<< HEAD
 - Após testado todo seu código 
   git add *
   git commit -m "mensagem"
   git push (enviar auterações para o repositório Github)
   git pull (puxar/ trazer auterações do Github para sua maquina)


=======
 - Após testado todo seu código
 - git add *
 - git commit -m "mensagem"
>>>>>>> f0343ff3839d4f1c0cbf9cb058eae39bb3a956c3

 ## Gitflow
 fluxo do Git
 
 ### Branchs
 São ramificações /versões palarelas
 main / master(vai para produção ,Quando o projeto e publicado)
 develop
 DoD Definition of Done : Critério de aceite
 git checkout -b dev (criar uma brench)
 git checkout master ( mudar de brench)

 versionamento 1.0.0
 ### Merge
 Mescla de branchs
