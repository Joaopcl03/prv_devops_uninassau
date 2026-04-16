## Perguntas (Git e GitHub - básico)
1. Qual a diferença entre `git init` e `git clone`?
#git init cria um repositorio do zero e o git clone, cona um repositorio ja existente
2. O que faz o comando `git status`?
#mostra o estado atual do projeto
3. Para que serve o `git add` antes do `git commit`?
#git add seleciona o que voce quer salvar e git commit salva permanentemente as alterações
4. Qual a diferença entre `git pull` e `git fetch`?
o git pull faz o fetch e une as mudanças automaticamente no seu codigo, ja o git fetch baixa o que tiver de novo no servidor mas nao mexe no codigo atual.
5. O que é um branch e por que ele é usado?
#é uma copia paralela do projeto. é usado para fazer alterações no projeto, ou ajustes, sem mecher no codigo principal.
6. O que é um Pull Request no GitHub?
#é um pedido para que suas alterações seram adicionadas no projeto.
7. Explique a diferença entre branch de origem e branch de destino em um PR.
#de origem é onde voce faz suas auterações e de destino é onde voce quer q seu codigo seja aplicado.
8. O que acontece se duas pessoas alterarem a mesma linha de um arquivo em branches diferentes?
#pode dar conflito e o git nao consegue decidir qual é o correto.
9. Para que serve o arquivo `.gitignore`?
#serve para listar os arquivos que o git deve ignorar.
10. Qual é a função do `README.md` em um projeto?
#é o documento do projeto. um manual de instrução do projeto.