# ember-materialize-mu-authorization

## installation

+ npm install ember-cli-materialize --save-dev
+ ember g ember-cli-materialize
+ add the following lines to your ember-cli-build.js file:
    sassOptions: {
      includePaths: [
        'bower_components',
        'bower_components/materialize/sass',
        'node_modules/ember-cli-materialize'
      ]
    }

## usage

add the following handlebars to your template:
```
{{authorization-manager}}
```

to select a different button color you can set it using the buttonClass variable:
```
{{authorization-manager buttonClass="light-green accent-1"}}
```

you can also select a different table style with:
```
{{authorization-manager tableClass="hoverable"}}
```