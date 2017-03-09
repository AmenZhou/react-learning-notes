#Use Eslint

* Install eslint

`npm install -g eslint`

* Install vim plugin -- https://github.com/vim-syntastic/syntastic

* Basic eslintrc.json file

```
{
  "extends": "airbnb",
  "parser": "babel-eslint",
  "plugins": ["react"]
}
```

* Install dependencies

```
npm install -g eslint-config-airbnb \
                 babel-eslint \
                 eslint-plugin-react
                 
```

* Install import resolver 

`npm i eslint-import-resolver-webpack -g`
