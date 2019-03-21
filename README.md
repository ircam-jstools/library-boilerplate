# library-boilerplate

> project starter for libraries

## Create a new project

```
git clone depth=1 https://github.com/ircam-jstools/library-boilerplate my-library
cd my-library
rm -Rf .git
```

## Available commands

```
npm run transpile
```

> transpile all files from `src` to `dist`

```
npm run watch
```

> watch files in `src` and transpile on save

```
npm run test
```

> run all the tests in `tests`

```
npm run doc
```

> Create the documentation using `jsdoc`. The documentation is built in the 
> `docs` directory. make sure to configure the github repository accordingly.

```
npm run deploy
```

> Deploy a new version of the library on `github` and `npm`. see [https://github.com/sindresorhus/np](https://github.com/sindresorhus/np) for more information

