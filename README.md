
# Guia do Git

Este é um guia simples para aqueles que querem lembrar dos principais comandos git e acessá-los de forma rápida e objetiva.

O Git é um sistema de controle de versão distribuído amplamente utilizado no desenvolvimento de software. Seus principais usos incluem:

1. **Controle de Versão:** Mantém um histórico completo de todas as alterações feitas em um projeto.
2. **Colaboração:** Permite que várias pessoas trabalhem simultaneamente no mesmo projeto.
3. **Rastreamento de Alterações:** Oferece a capacidade de ver quem fez quais alterações e quando.
4. **Branching e Merging:** Facilita a criação de branches para trabalhar em novas funcionalidades e mesclar as alterações de volta à versão principal.
5. **Backup e Restauração:** Simplifica o processo de backup e restauração de projetos.


## Tabelas de comandos

Abaixo encontra-se algumas tabelas de comandos básicos para o dia a dia.

#### Comandos básicos

| Comando      | Descrição                           | 
| :----------- | :---------------------------------- | 
| `git init`   | Inicializa um repositório           | 
| `git add`    | Adiciona arquivos ao staging area   | 
| `git commit` | Salva as alterações no repositório  | 
| `git status` | Exibe o estado atual do repositório | 
| `git log`    | Exibe o histórico de commits        |


#### Colaboração

| Comando               | Descrição                                          | 
| :-------------------- | :------------------------------------------------- | 
| `git clone`           | Clona um repositório remoto para o repositório local | 
| `git pull`    | Puxa alterações do repositório remoto e mescla com o repositório local  | 
| `git fetch`   | Busca alterações do repositório remoto, mas não as mescla automaticamente  | 
| `git push`            | Envia commits locais para um repositório remoto  | 
| `git pull-request`    | Solicita a integração de mudanças no repositório remoto através de uma pull request |

#### Ramificação (branch)

| Comando                           | Descrição                                                 | 
| :-------------------------------- | :-------------------------------------------------------- | 
| `git branch`                      | Lista todas as branches no repositório                    | 
| `git branch [nome]`               | Cria uma nova branch com o nome especificado              | 
| `git checkout [branch]`           | Muda para a branch especificada                           | 
| `git checkout -b [nome]`          | Cria uma nova branch com o nome especificado e muda para ela |
| `git branch -d [nome]`            | Apaga a branch especificada                               |
| `git branch -D [nome]`            | Força a remoção da branch especificada, mesmo que haja commits não mesclados  |
| `git merge [branch]`              | Mescla uma branch com a branch atual                      | 
| `git remote`                      | Lista os repositórios remotos configurados                | 

#### Mesclagem (merge)

| Comando           | Descrição                                        | 
| :---------------- | :----------------------------------------------- | 
| `git merge`      | Mescla uma branch com a branch atual            | 
| `git rebase`     | Reaplica as alterações de uma branch sobre outra| 
| `git mergetool`  | Abre uma ferramenta para resolver conflitos     | 


#### Configurações

| Comando                       | Descrição                                             | 
| :---------------------------- | :---------------------------------------------------- | 
| `git config --global user.name "[seu nome]"` | Configura o nome de usuário globalmente |
| `git config --global user.email "[seu email]"` | Configura o email do usuário globalmente |
| `git config --global core.editor "[editor]"` | Configura o editor de texto padrão para mensagens de commit |
| `git config --global color.ui true` | Ativa a colorização da saída do Git para melhorar a legibilidade |
| `git config --list` | Exibe todas as configurações do Git (pressione "q" para voltar) |

## Autores

- [@devklebinho](https://www.github.com/devklebinho)


## Referência

- [Documentação oficial](https://git-scm.com/doc)