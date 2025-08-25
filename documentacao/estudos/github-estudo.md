# Interface do GitHub

## Repositórios
Onde ficam os seus projetos.

### O que é um Repositório?
Um repositório é uma **pasta** onde você guarda os arquivos de um projeto junto com todo o **histórico de alterações**.  
Ele é usado principalmente no **GitHub**, mas a ideia serve em geral.

#### O que tem em um repositório:
- Arquivos do projeto (códigos, imagens, textos, documentação)  
- Histórico de versões (quem mudou, o que mudou, quando mudou)  
- Ramificações (**branches**) para desenvolver coisas em paralelo  

#### Tipos de repositório:
- **Local**: fica no seu computador, criado com `git init`  
- **Remoto**: fica em um servidor (ex: GitHub, GitLab), usado para compartilhar e sincronizar  

📌 **Exemplo:**  
Imagine que você está criando um site.  
- Sem o Git → você teria várias pastas com nomes tipo: `site-final-V1`, `site-final-V2-ajustes`.  
- Com o Git → tudo fica no mesmo lugar e o Git guarda automaticamente o histórico, sem precisar duplicar as pastas.  

---

## Como Criar um Repositório
1. Clique em **New Repository**  
2. Preencha:
   - `repository name` (nome do projeto)  
   - `description` (descrição)  
   - `public` ou `private` (se quiser que outros vejam)  
   - marque **Initialize with a README**  

---

## README
O **README** é como se fosse a vitrine do seu projeto.  

### O que colocar:
- Nome do projeto  
- Descrição: o que o projeto faz  
- Como instalar/rodar: passo a passo para quem quiser usar  
- Como contribuir: se outros quiserem colaborar  
- Licença: se é livre, aberto, etc  
- Tecnologias usadas: linguagens, frameworks, etc  

---

## Commits
Um **commit** é quando você muda algo no código e coloca junto uma explicação do que você mudou.  
Os commits mostram todo o histórico de mudanças que ocorreram no projeto.  

---

## Issues
As **issues** são como um quadro de tarefas e problemas a serem corrigidos no projeto.  

### Funções das issues:
- Relatar bugs  
- Pedir melhorias  
- Organizar tarefas  

📌 **Exemplo:**  
- Issue 1: corrigir link da página inicial  
- Issue 2: adicionar referências  

---

## Pull Requests
São **pedidos de alteração** no projeto.  
Permitem que as mudanças feitas em uma branch sejam revisadas e mescladas ao código principal.  

---

## Branches
Uma **branch** é um desenvolvimento separado do projeto.  
Você pode mexer sem alterar o código principal.  

### Exemplo:
- A branch `main` é o código principal.  
- Você quer adicionar mais uma função → cria a branch `funcao-feature` e faz todas as mudanças ali.  
- Depois pode juntar essa branch com o código original por meio de um **pull request**.  

### Funções do branch:
- Trabalhar com outras funções sem modificar o projeto principal  
- Permitir várias pessoas trabalharem em áreas diferentes ao mesmo tempo  
- Se der algum problema, você pode apagar a branch e o código principal continua intacto  
