## Webpack useful settings

i added some interesting settings in order to make the webpack-server work. I set also the css and image loaders. 

This configuration corresponds to the following folder structure:

```

├── dist
│   ├── index.html
│   ├── js
│   │   ├── index.html
│   │   ├── main.js
│   │   └── main.js.map
│   ├── main.js
│   └── styles
│       ├── style.css
│       └── style.css.map
├── package.json
├── package-lock.json
├── src
│   ├── js
│   │   └── main.js
│   └── scss
│       └── styles.scss
└── webpack.config.js
└── node_modules

```

to use the LiveReloadPlugin, you need to add ```<script src="http://localhost:35729/livereload.js"></script>``` at the head tag
in your ```index.html``` file. More infos [here](https://www.npmjs.com/package/webpack-livereload-plugin)
