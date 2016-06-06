AngularJS training
==================

fetch all dependencies:

    npm install
    npm install -g http-server karma-cli

continuous unit tests:

    npm test

serve the application:

    npm start

download and run REST API:

    git clone https://github.com/ducin-public/itcorpo-api
    cd itcorpo-api
    npm install
    npm start -- -t false # tenant headers are not required
    # or
    npm start # tenant headers are required

additional resources
--------------------

 * [AngularJS unit testing guide](https://docs.angularjs.org/guide/unit-testing)

additional software used
------------------------

app:

 * [`twitter bootstrap`](https://getbootstrap.com/docs/3.3/), [`starter-template`](https://getbootstrap.com/docs/3.3/examples/starter-template/)
 * [`angular-ui-bootstrap`](https://angular-ui.github.io/bootstrap/)
 * [`angular-busy`](https://github.com/cgross/angular-busy)

cli:

 * [`json-server`](https://github.com/typicode/json-server) / [`mock-rest-api`](https://github.com/ducin-public/mock-rest-api)
 * [`http-server`](https://github.com/indexzero/http-server)
