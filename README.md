## Passo a passo atividade 
- Em primeiro lugar foi acionado o Git Bash para acionar os comandos,Sendo criada uma pasta chamada repositorio (para confirmar o caminho é adequado usar o comando pwd, pórem não foi usado.)
Dentro desse repositorio foi navegado


<img width="512" height="203" alt="1" src="https://github.com/user-attachments/assets/bd324b97-bd1b-4d89-8c14-3ea6b25564e2" />


- usando o comando git clone https://github.com/anajmartins19/create/git-local.git 

serviu para copiar um repositório do GitHub para o meu computador.




<img width="726" height="332" alt="2" src="https://github.com/user-attachments/assets/4d76bdcd-8aef-48bb-b465-e5e964f3ec9e" />

Logo depois que eu executei o comando para clonar o repositório, o Git Bash mostrou uma sequência de mensagens indicando que o processo estava acontecendo corretamente. Primeiro apareceu a frase “Cloning into 'git-local'...”, que significa que o Git estava criando uma nova pasta local com esse nome para armazenar o conteúdo do repositório.
Em seguida, surgiram mensagens como Enumerating objects, “Counting objects” e “Compressing objects”, mostrando que o Git estava contando, compactando e transferindo os arquivos e o histórico do repositório remoto. Depois, as linhas “Receiving objects” e “Resolving deltas” indicaram que o download dos arquivos foi concluído e que o Git estava organizando tudo corretamente na minha máquina. Por fim, a palavra “done.” confirmou que o clone foi feito com sucesso e que o repositório estava pronto para ser acessado.






Depois do clone, entrei na pasta do repositório com:

<img width="628" height="53" alt="3" src="https://github.com/user-attachments/assets/66c43b6e-2f4f-4b87-b642-80389b689465" />



Esse comando me levou para dentro do projeto, e ele funcionou corretamente.

- Criei uma nova branch e já mudei para ela usando:


<img width="525" height="41" alt="4" src="https://github.com/user-attachments/assets/48a0032e-ba8b-4cfe-b43f-87f28457dfb1" />


O comando funcionou direitinho e cumpriu o que eu queria: criar uma branch específica para trabalhar na documentação e na colaboração.

- Ouve tentativas de commit 

O que eu executei:
git commit-m "feat: Adiciona documentacao sobre integracao e colaboracao"

O terminal retornou erro e o commit não foi realizado.Pois eu  escrevi commit-m sem espaço entre commit e -m, então o Git não reconheceu o comando.

Comando correto:

<img width="502" height="33" alt="6" src="https://github.com/user-attachments/assets/62dd8a35-207b-4731-9f44-30df7238273a" />

-  Tentativa de push da branch

foi executado:

<img width="558" height="109" alt="7" src="https://github.com/user-attachments/assets/a128811c-75dd-41e3-bb5f-57c132553448" />

O que aconteceu:
O Git retornou mensagens como “does not appear to be a git repository” e “Could not read from remote repository”.

Poruqe eu  não informei o repositório remoto, então o Git não sabia para onde enviar a branch.

mas logo foi corrigido com
git push -u origin documentacao-colaboracao.

## colaboração 
em seguida adicionei um colaborador 
Para adicionar um colaborador em um repositório no GitHub, eu abri o repositório e fui até a aba Settings. Dentro das configurações, entrei na opção Collaborators e cliquei em Add collaborator. Depois disso, digitei o nome de usuário ou o e-mail da pessoa que eu queria adicionar e confirmei o convite. O colaborador recebeu uma notificação por e-mail e, ao aceitar, passou a ter acesso ao repositório, podendo clonar o projeto, criar branches, fazer commits e abrir pull requests normalmente. Esse processo é importante para permitir o trabalho em equipe de forma controlada e segura.

<img width="858" height="243" alt="colaboração " src="https://github.com/user-attachments/assets/d395c8e9-a654-48e0-8fa3-92f4ed87cccb" />



