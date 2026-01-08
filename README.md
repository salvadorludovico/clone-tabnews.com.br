# clone-tabnews.com.br
Projeto de clone da plataforma tabnews para o curso.dev

# Aprendizados
- `node_modules` é a pasta onde ficam todas as dependências do projeto Node.js (bibliotecas, sub-bibliotecas, versões específicas, etc.).
    - `package.json` define quais dependências o projeto precisa
    - `package-lock.json` é o arquivo que define exatamente as versões de cada dependência que foi instalada.
- `git commit --amend` usando a flag `--amend` eu posso acoplar uma modificação ao commit anterior, sem fazer um novo commit
  - Por baixo dos panos o git apaga o commit anterior e cria um novo commit
  - Caso tenha feito o `git push` para o repositório remoto, deve ser necessário fazer `git push --force` ou `git push -f` para subir a alteração feita com `--amend`