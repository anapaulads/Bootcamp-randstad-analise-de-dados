\# Módulo: Versionamento de Código com Git e GitHub



\## Resumos das aulas



\- Aula 1: Visão Geral do Curso e Ferramentas

Foi apresentada a proposta do curso e os conceitos fundamentais de versionamento de código, além de uma introdução às ferramentas Git e GitHub.



\- Aula 2: Instalação, Configuração e Autenticação

Realizamos a instalação do Git, a configuração inicial do usuário e exploramos os métodos de autenticação. Aprendemos a gerar tokens de acesso e a criar/ativar chaves SSH para conexão segura com o GitHub.



\- Aula 3: Primeiros Passos com Git e GitHub

Praticamos operações essenciais no fluxo de versionamento:



&nbsp;   - Criação e clonagem de repositórios

&nbsp;   - Registro de alterações no repositório local

&nbsp;   - Desfazer modificações

&nbsp;   - Envio (push) e sincronização (pull) com o repositório remoto

&nbsp;   - Trabalho com branches (criação, mesclagem, exclusão e resolução de conflitos)

&nbsp;   - Utilização de comandos úteis para o dia a dia de versionamento



\## Comandos Git 



| Comando | Ação |

| ------- | ---- |

| mkir "nome da pasta" | Cria uma pasta | 

| git init | Inicia o Git |

| git status | Verifica o status dos arquivos da pasta |

| touch "nome do arquivo" | Cria um arquivo |

| touch resumos/resumo-aula1.md | Cria arquivo sem precisar entrar na pasta |

| git add "nome do arquivo" | Adiciona o arquivo específico| 

| git add . | Adiciona todos os arquivos | 

| git commit -m "msg" | Commita o arquivo com a mensagem |

| git log | exibe o histórico de alterações (commits) de um repositório |

| echo "nome da pasta"/ > .gitignore | cria ou substitui o arquivo .gitignore e adiciona o diretório à lista de diretórios a serem ignorados pelo Git | 

| touch "nome da pasta"/.gitkeep | Rastreia a pasta vazia | 

| git restore --staged "nome do arquivo" | "desfaz" o git add do arquivo |

| git restore "nome do arquivo" | apaga as alterações feitas no arquivo |

| git reset --soft HEAD~1 | desfaz o último commit sem apagar as alterações feitas |

| git diff | Retorna a diferença entre o arquivo no GitHub e o arquivo na máquina |

| git branch | Verifica as branches do projeto |

| git checkout -b "nome da branch"| Cria uma nova branch |

| git checkout "nome da branch" | Altera a branch |

| git branch -D "nome da branch" | Força a deleção da branch |

| git branch -d "nome da branch" |Exclui de forma segura, somente quando as alterações forem mescladas |







