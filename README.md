# js-hubot

## require node

```sh
# ndenv
$ git clone https://github.com/riywo/ndenv ~/.ndenv
$ echo 'export PATH="$HOME/.ndenv/bin:$PATH"' >> ~/.bash_profile
$ echo 'eval "$(ndenv init -)"' >> ~/.bash_profile
$ source ~/.bash_profile

# node-build
$ git clone https://github.com/riywo/node-build.git ~/.ndenv/plugins/node-build
```

## install hubot

```
$ git clone git@github.com:kao-bee/js-hubot.git
$ cd straw-hubot
# install node using .node-version
$ ndenv install
$ ndenv rehash
# install node-modules using package.json
$ npm install
```

## execute in terminal

```sh
# at project top directory

$ ./bin/hubot
```
