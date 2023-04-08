# Curso de Django
Curso de Django da [Udemy](https://www.udemy.com/course/curso-de-django-web-framework-com-python-html-e-css/)

[GitHub Pages](https://pages.github.com/).

### Criando máquina virutal
`$python3 -m venv ~/virtualenvs/cursodjango`

### Instalando Django e outras coisas

`$pip install django`

`$pip install pytest`

`$pip install pip setuptools wheel --upgrade`

`$install autopep8`

### Configurando o Git/Github

* Acessar o [github.com](https://github.com) e criar conta

* Criar um repositório no Github

* Colocar um nome, pode deixar público e criar em __Criar Repositório__

* Configurando o git local
    `$ git conifg user.name "<<Seu Nome>>"`

    `$ git conifg user.email "<<Seu Email>>"` (deve ser o mesmo que usou para criar a conta do github)

    `$ git conifg init.defaultBranch main`

    `$git init`


* Uma vez iniciado o git localmente, é necessário criar um par de chaves. Caso já tenha as chaves de outro projeto pode pular esta etapa. 
    `$ssh-keygen`


* Copiar a chave pública criada para colar nas configurações de [chaves](https://github.com/settings/keys)

    `$cat ~/.ssh/id_rsa.pub`


* Ir até o github do projeto e copiar o endereço, em seguida adicioná-lo ao diretório local

    `$git remote add origin <<endereço_projeto>>`

    Ex.: `$git remote add origin git@github.com:jonassonjp/cursodjango.git`

