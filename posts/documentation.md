# Bem-Vindo `a nossa Wiki!

## Estrutura do Projeto


```plaintext
- **/wiki-posts**
  - **/templates**
    - index_template.html
    - page_template.html
  - **/static**
    - **/css**
      - style.css
    - **/images**
      - github-logo.jpeg
      - python-logo.png
  - **/posts**
    - posts.json
    - documentation.md
    - post_documentation.md
  - **/scripts**
    - create_pages.py
  - **/docs**
- .gitignore
- README.md

* **/templates:** Contém os modelos HTML utilizados para gerar as páginas.
* **/static:** Armazena arquivos estáticos como folhas de estilo CSS e imagens.
* **/posts:** Mantém o arquivo posts.json e markdown com as informações sobre as postagens.
* **/scripts:** Inclui o script Python create_pages.py para criar páginas HTML a partir dos dados em posts.json, documentation.md e post_documentation.md.
* **/docs:** Destinado a armazenar as páginas HTML geradas pelo script.
```

## Passos Realizados

### Configuração do Repositório:

- Criada a branch main.
- Criado o arquivo .gitignore.
- Inicializado o arquivo README.md.


### Integração do Gitflow:

- Configurado o Gitflow com as branches develop, main, feature, release, e hotfix.


### Estrutura Básica do Projeto:

1. Criada a estrutura básica do projeto com as pastas templates, static, posts, scripts, e docs.

2. Adicionados arquivos como index.html, post_template.html, style.css, github-logo.jpeg, python-logo.png, posts.json, e create_pages.py.

### Geração de Páginas com Python:

1. Desenvolvido o script Python create_pages.py.
2. Utilizado o Jinja2 para a geração dinâmica de páginas HTML.
3. Adicionadas informações sobre postagens ao arquivo posts.json.
4. Adicionado arquivo documentation.md explicando o fluxo de branches e o script Python.

### Executando o Projeto:

Para executar o projeto:

- Clone o repositório localmente.

- Execute o script Python generate_pages.py para gerar as páginas HTML na pasta docs.

- Abra o arquivo index.html no navegador para visualizar o site.

- Para adicionar novas postagens, edite o arquivo posts.json e execute o script novamente.



´´´bash

python3 scripts/create_pages.py

´´´

As páginas geradas estarão disponíveis na pasta docs.
