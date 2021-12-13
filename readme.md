<h1>Baixando o projeto e executando</h1>

Para clonar um repositório já existente você deve usar o comando: 

```
git clone https://github.com/anaclaudia-cb/Controle-de-Series.git
```

depois irá para a pasta do projeto utilizando o comando:

```
cd controle-de-series
```

depois instalará o composer na pasta

```
composer install
```

caso haja algum erro utilze o comando
```
composer update
```

rodará o comando

```
php artisan serve
```

irá para a paǵina do google e colocará localhost:8000/series

<h1>Sobre o Projeto</h1>

O projeto consiste em um sistema para controlar séries, podendo assim adicionar séries que estão sendo acompanhadas pelo usuário, ou excluir aquelas que já foram finalizadas. Foi desenvolvido junto do curso "Laravel parte 1: Produtividade no desenvolvimento web" disponível na plataforma Alura Cursos.

![home](https://imgur.com/cyqxzli.png)

A página inicial do sistema consistem em listar as séries adicionadas. Os botões ao lado de cada nome de série inserido são: editar, visualizar as temporadas e episódios da série e excluir.

![adicionar](https://imgur.com/wrC6LQO.png)

Ao apertar no botão de "adicionar" o usuário será redirecionado para um formulário onde aparecerá um formulário para ser preenchido e assim ir para o banco de dados.

O projeto consiste também em elementos do bootstrap.
