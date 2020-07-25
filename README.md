# angular-add-bootstrap
![img](Screenshot_2.png)
~~~
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-light">Light</button>
<button type="button" class="btn btn-dark">Dark</button>
<button type="button" class="btn btn-link">Link</button>
~~~



~~~

## Create a new application
ng new AngularDemo


## add bootstrap to classpath inside angular.json
------------------
 "styles": [
              "src/styles.css",
              "node_modules/bootstrap/dist/css/bootstrap.min.css"
            ]



## If bootstrap not available inside node_modules you can add bootstrap using command
yarn add bootstrap@3.3.7 --save



## Start the application
>ng s -o 


~~~
