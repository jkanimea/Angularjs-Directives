# Directives with Angular JS

This angularJs directive example was initially done by David Mosher. I have borrow his code because he got a excellent explanation on some advanced features in Angular, mapping from  HTML and explanation how this relates to angular directives, It also got some good  debugging techniques, tips and tricks. 
I had to modify initially to get working on web server using nodejs http and add my own documentation for me to understand his code better.

Scenario :- You have html written in angular directive for a data grid and this need to translated in angular code.  

   <grid-screen resource="/api/data.json">
     <grid-columns>
       <grid-column title="Product"     field="product"></grid-column>
       <grid-column title="Description" field="description"></grid-column>
       <grid-column title="Cost"        field="cost"></grid-column>
     </grid-columns>
   <grid with-inline-editor></grid>
  </grid-screen>

His [screencast](https://www.youtube.com/watch?v=Ty8XcASK9js)

It covers:

* html as a dsl
* abstractions in html
* [$compile](https://docs.angularjs.org/api/ng/service/$compile)
* [$templateRequest](https://docs.angularjs.org/api/ng/service/$templateRequest)
* [$templateCache](https://docs.angularjs.org/api/ng/service/$templateCache)
* [directive definition object](https://docs.angularjs.org/api/ng/service/$compile#directive-definition-object)
* [requiring other directives](https://docs.angularjs.org/api/ng/service/$compile#-require-)
* [directive communication ($scope.$broadcast, $scope.$on)](https://docs.angularjs.org/guide/scope#scope-events-propagation)





