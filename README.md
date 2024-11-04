## Some Advantages of Angular-JS
1. With the help of Angular you can write Declarative code. ( Define the Target-UI states and how they change, and let Angular do the REST).
 == With the help of Vanila-Js I need to write Imperative code where I need to write code for each and every instructions that needs to be executed by the browser. == (Just for the sake of knowledge purpose)
2. Angular allows you to seperate concerns with the help of components. ( Components are custom HTML-Elements).
3. The Root component is placed inside the bootstrap application. 
## 4. Decorators are used to add meta-data to the things they are attached to. Example : Component Decorator.
   The Component Decorator is used to add meta-data to the classes.
   Some important attributes of Component Decorator
   	Selector == This Tells Angular which Elements of the Screen are controlled by this Component.
   	templateUrl == It contains the markup for that component ( value is generally the path of the file ).
5. So we export a class/component using export keyword so that we can use that class in other classes.
6. Components are created as classes. You instantiate the custom-html elements. But its Angular that instantiates
   the classes in the end. 
7. You Try Building a Component Tree in this way.
 				
 					            App Component
 					                 |
 					                 |
 	----------------------------------------------------------------------------
   |                                |                                           |
   Header Component           User Component                                 Tasks Component
   																				|
   																			 Task Component 