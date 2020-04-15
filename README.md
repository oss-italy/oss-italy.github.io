[![Open Source Saturday Italy](https://img.shields.io/badge/Open%20Source%20Saturday-Italy-red)](https://oss-italy.github.io/)
[![Discord](https://img.shields.io/discord/688392679892975619.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/TpEa5Wn)


Repository del sito di Open Source Saturday Italy. https://oss-italy.github.io/

# Build locale
* clona questa repository:
  ```
  git clone https://github.com/oss-italy/oss-italy.github.io
  ```

* entra nella directory:
  ```
  cd oss-italy.github.io
  ```

A questo punto puoi scegliere se usare docker o no:

## Docker
* esegui il container [github-pages](https://github.com/Starefossen/docker-github-pages) con questo comando:
  ```
  $ docker run -it --rm -v "$PWD":/usr/src/app -p "4000:4000" starefossen/github-pages
  ```
* Apri l'indirizzo `http://localhost:4000` nel tuo browser

## Manuale
* Installa ruby
* Installa bundler con il comando `$ gem install bundler`
* Installa Jekyll e altre dipendenze con il comando `$ bundle install`
* Esegui il server localmente con `$ bundle exec jekyll serve`
* Apri l'indirizzo `http://localhost:4000` nel tuo browser
