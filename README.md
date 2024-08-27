## Requisitos

* PHP 8.1 ou superior
* Composer
* Git

## Como rodar o projeto
Instalar as dependências
```

composer install
```

```
Duplicar o arquivo ".env.example" e renomear para ".env"
```

Gerar a chave
```
php artisan key:generate
```

## Sequencia para criar o projeto

Criar o projeto com laravel
```
composer create-project laravel/laravel manager
```

Acessar o diretório onde está o projeto
```
cd manager
```

Iniciar o projeto criado com laravel
```
php artisan serve

```

Acessar o conteúdo padrão do laravel
```
http://127.0.0.1:8000/

```

## Enviar para o GitHub
Iniciar o versionamento com GIT na máquina
```
git init
```
Definir suas configurações de usuário
```
git config --local user.name "seu nome"
```

```
git config --local user.email "seu email cadastrado no GitHub"
```
Baixar os arquivos do Git
```
git clone --branch <nome da branch> <nome do repositório>
```

Verificar se você está na branch correta
```
git branch
```
Para baixar as atualizações do GitHub para sua máquina com o projeto já clonado
```
git pull
```


