# Angular-directive-to-allow-the-use-of-scrollReveal.js-project

Installation

Download

master.zip

GitHub

git clone https://github.com/abdain/angular.js.git

Bower

bower install fox-angular-scrollReveal.js

Load script after scrollReveal's

  
         <script src="path/to/scrollReveal.js"></script>
         <script src="path/to/fox-angular-scrollReveal.js"></script>
  
  
Include module dependency

  angular.module('myApp', ['fox.scrollReveal']);
Basic Usage

Needs a custom attribute on the container of all elements so it can start the controller. With that you can also inject your custom defaults.

        <div data-sr-container="{ custom defaults }">
        <!-- Same as scrollReveal's basic usage. -->
       <div data-sr="enter left and move 50px over 1.33s"> Foo </div>
       <div data-sr="enter from the bottom after 1s"> Bar </div>
       <div data-sr="wait 2.5s and then ease-in-out 100px"> Baz </div>
       </div>

 
Other than that it works just like the normal scrollReveal.js would. There is a "scroll-reveal" attribute directive, but it does not mess with the original custom attribute from scrollReveal.js. It is only used to register the element with the controller.

Documentation

Refer to scrollReveal.js's docs to set your custom defaults or animation parameters


[Demo and code example] (http://plnkr.co/edit/HTYndu?p=preview)
