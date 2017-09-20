# What technologies have been used for preparing the Slides?
[asciidoctor-revealjs](https://github.com/asciidoctor/asciidoctor-reveal.js) has been used to build the slides.

# How to Build this Repository?
1. Install Ruby
2. Open command prompt in slides directory.
3. Install bundler and configure it with below commands
```$ gem install bundler
$ bundle config --local github.https true
$ bundle --path=.bundle/gems --binstubs=.bundle/.bin
```
# How to Convert adoc to html?
Use the below command, <br/>
``` $ bundle exec asciidoctor-revealjs -a revealjsdir=https://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.5.0 <adoc_file_path>```



