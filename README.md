# composer-bin-template
A composer library demo project, mainly shows how to build your own composer library with a executable script.
# install
#### Add the following line to your composer.json
```json
  "repositories": [
    {
      "type": "vcs",
      "url": "git@github.com:bitmyth/composer-bin-template.git"
    }
  ],
```
Run `composer global require bitmyth/bin-demo`,you will see a executable script installed in $HOME/.composer/bin directory if default location setting of composer bin directory has not been changed

# Play
then just run `hi` command in console ,you will see output  `Hello World`
