[![Open Source Saturday Italy](https://img.shields.io/badge/Open%20Source%20Saturday-Italy-red)](https://oss-italy.github.io/)
[![Discord](https://img.shields.io/discord/688392679892975619.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/TpEa5Wn)


Repository del sito di Open Source Saturday Italy. https://oss-italy.github.io/

# Build locale
Per fare una build locale del sito:

* Installa ruby
* Installa bundler con il comando `$ gem install bundler`
* Crea un file chiamato `Gemfile` nella root del sito con il seguente contenuto:
  ```
  source 'https://rubygems.org'
  gem 'github-pages', group: :jekyll_plugins
  ```
* Installa Jekyll e altre dipendenze con il comando `$ bundle install`
* Esegui il server localmente con `$ bundle exec jekyll serve`
* Apri l'indirizzo `http://localhost:4000` nel tuo browser
