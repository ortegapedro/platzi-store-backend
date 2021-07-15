# encriptar las keys
download RUBY: https://www.ruby-lang.org/es/documentation/installation/#rubyinstaller

execute:
    ruby -v
    gem install travis
    travis version
    travis encrypt api_key

Copiar y pegar el resultado en el archivo .travis.yml
