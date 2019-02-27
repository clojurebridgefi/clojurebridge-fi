# ClojureBridge.fi

Home page for Finnish ClojureBridge organization.

The pages are at https://clojurebridge.fi/


# Development

This is a GitHub pages project, the contents under `/docs` is the public content. 

The main html file is at `/docs/index.html`. Styles are in SASS at `/src/styles.scss`.

Start SASS compilation:

```bash
./node_modules/.bin/sass --watch src/styles.scss docs/styles.css
```

Start auto reloading server:

```bash
./node_modules/.bin/autoreload-server docs
```

There's a handy `Justfile` if you have [just](https://github.com/casey/just) installed. The above
commands can be done by just:

```bash
just sass
```

...and...
 
```bash
just reload
``` 


# Publish

Once your changes are done just commit and push to master. 


## License

[This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
