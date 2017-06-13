# Integração Contínua utilizando Git

Script desenvolvido para aplicações em PHP com Composer e PHPUnit.

Developed by Gleandroj

# Dependencies

* [Composer](https://getcomposer.org)
* [Apache](https://www.apache.org)
* [Git](https://git-scm.com)
* [Bash](https://www.gnu.org/software/bash) (Normalmente vem com o Git)
* [PHP](https://secure.php.net)
* [PHPUnit](https://phpunit.de)
* [Laravel Framework](https://laravel.com/docs/master)

# Get Started

```sh
 $ bash ambiente-config
 $ composer global require "laravel/installer"
 $ composer create-project --prefer-dist laravel/laravel integracao-app
```
Agora copie o arquivo "composer.json.sample" para a pasta integracao-app.
Isso é necessário por causa de um script de test adicionado no arquivo para executar os testes corretamente.

```sh
 $ cd integracao-app && git init && git add .
 $ git commit -m "Initial Commit"
 $ git remote add origin http://localhost/git/integracao.git
 $ git push --set-upstream origin master
```

# Note

* Não esqueça de remover o arquivo .env do gitignore do projeto integracao-app
* Não esqueça de alterar os diretórios de acordo com seu sistema nos arquivos *.sample

Enjoy!
