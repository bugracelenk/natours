# Natours

Natours is a website for tour companies. It has 5 sections:

- About Natours
- Your Benefits
- Popular Tours
- Your Benefits
- Book Now

### Tech

Natours uses some open source projects to work properly:

- [node-sass](https://github.com/sass/node-sass/) - Sass and Scss compiler
- [Node.js](https://nodejs.org/) Javascript runtime enviroment.

And of course Dillinger itself is open source with a [public repository][natours]
on GitHub.

### Installation

Natours doesnt require anything to run, but to purpose of develop scss you need to be installed [NodeJS][node.js] on your computer
Install the dependencies and devDependencies and start the server.

```sh
$ cd natours
$ npm install -d
$ live-server
$ npm run compile:sass
```

The command below watches all the changes on your scss files and compiles at the same time.

```sh
$ npm run compile:sass
```

### Todos

- Finish navigation
- Add Night Mode

## License

MIT

**Free Software, Hell Yeah!**

[//]: # "These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax"
[natours]: https://github.com/bugracelenk/natours
[pldb]: https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md
[plgh]: https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md
[plgd]: https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md
[plod]: https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md
[plme]: https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md
[plga]: https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md
