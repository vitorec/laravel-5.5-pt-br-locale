# Arquivos de linguagem do Laravel 5.5 - Português do Brasil

## Tradução das mensagens de erro padrão do Laravel 5.5 para PT-BR

Instalação:

1. Clonar este projeto para uma pasta dentro de `resources/lang/`
  ```
  $ cd resources/lang/
  $ git clone https://github.com/vitorec/laravel-5.5-pt-br-locale.git ./pt-br
  ```
  
Você pode remover o `README.md` e o diretório oculto `.git` para poder incluir
e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -rf pt-br/.git/ pt-br/README.md
  ```
  
2. Configurar o Laravel para utilizar o português por padrão:

  ```
  // Linha 81 do arquivo config/app.php
  'locale' => 'pt-br',
  ```

**OBS:** adaptado de [MavinsTecnologia](https://github.com/MavinsTecnologia/laravel-5.4-pt-br-locale) para o Laravel 5.5.
