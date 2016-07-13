# Directives with Angular JS

This examines some of the more advanced features in Angular, specifically Directives and how we can leverage the power of custom elements and attributes to map Domain Specific concepts through HTML, translate those into Value Objects in our Domain, and gain rendered simple HTML output. Also discussed: complexity, creating a DSL with directives, debugging techniques, tips and tricks.

this screencast covers:

* html as a dsl
* abstractions in html
* [$compile](https://docs.angularjs.org/api/ng/service/$compile)
* [$templateRequest](https://docs.angularjs.org/api/ng/service/$templateRequest)
* [$templateCache](https://docs.angularjs.org/api/ng/service/$templateCache)
* [directive definition object](https://docs.angularjs.org/api/ng/service/$compile#directive-definition-object)
* [requiring other directives](https://docs.angularjs.org/api/ng/service/$compile#-require-)
* [directive communication ($scope.$broadcast, $scope.$on)](https://docs.angularjs.org/guide/scope#scope-events-propagation)

# Running the Code Locally

I like to use the npm module [serve]() for running a simple static webserver for projects like this:

```shell
npm i -g serve
git clone git@github.com:davemo/advanced-directives-with-angular-js.git
cd advanced-directives-with-angular-js
serve
```



