# Porject Name
> sub title

Overview
---
project description simply

Fetures
---
+ [x] Feture 1
  * [x] Feture Sub Item 1
  * [x] Feture Sub Item 2
+ [x] Feture2 

Install
---
``` sh
```

Usage
---
+ Dev 
```
npm run dev
```

+ Production
```
npm run build
```

Command Line Options
---
This generator can also be further configured with the following command line flags.
```
        --version        output the version number
    -e, --ejs            add ejs engine support
        --pug            add pug engine support
        --hbs            add handlebars engine support
    -H, --hogan          add hogan.js engine support
    -v, --view <engine>  add view <engine> support (dust|ejs|hbs|hjs|jade|pug|twig|vash) (defaults to jade)
        --no-view        use static html instead of view engine
    -c, --css <engine>   add stylesheet <engine> support (less|stylus|compass|sass) (defaults to plain css)
        --git            add .gitignore
    -f, --force          force on non-empty directory
    -h, --help           output usage information
```
    
Structure
---
```
.
│── app.js
│── bin
│── package.json
│── public
│   │── images
│   │── javascripts
│   └── stylesheets
│── routes
│   │── index.js
│   └── users.js
└── views
    │── error.ejs
    └── index.ejs

```

Preview
---
+ Index
![Index](./screenshot/index.png)

+ Login
![Login](./screenshot/login.png)

+ Table
![Table](./screenshot/table.png)

+ Form
![Form](./screenshot/form.png)


License
---
[MIT](LICENSE)