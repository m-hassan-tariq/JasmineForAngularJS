# JasmineForAngularJS
Jasmine Unit Test For AngularJS sample using Reshaprer and Chutzpa as test runner


For installing Chutzpaa:
 
- Install the Chutzpah Visual Studio Extension. 
https://visualstudiogallery.msdn.microsoft.com/f8741f04-bae4-4900-81c7-7c9bfb9ed1fe
- Install the Jasmine test framework nuget package. 
From the package manager console, run: install-package JasmineTest

For installing Resharper:
- Get Resharper
https://www.jetbrains.com/resharper/download/
- After installation, Please set the configuration as highlighted in below image

![pastedimage 2](https://cloud.githubusercontent.com/assets/10474169/10744818/a7ce84c4-7c0a-11e5-9325-6751d370a7c9.png)

Bookmark below URL, its a cheat sheet for jasmine syntax 
http://ricostacruz.com/cheatsheets/jasmine.html


Below images will highlight new changes in ngninja project
- Directory Structure
- Resharper test Runner
- Chutzpa test runner

![pastedimage](https://cloud.githubusercontent.com/assets/10474169/10744819/a7cef3c8-7c0a-11e5-8bf2-3d58eb36ebd9.png)

How to code Jasmine Test Case
- Mention test file name
- Mock all dependencies for module which you are testing
- mention angular module name for which you are writing test cases
- Inject dependencies and initialize all variables 
- Write unit test for each functionality 

P.S. I have written unit test cases for Candidate Module(Controller, Service, main Candidate file and Shared http service, total 18 Unit test cases)

![pastedimage 1](https://cloud.githubusercontent.com/assets/10474169/10744817/a7ba1cc8-7c0a-11e5-978a-d841bcf3d226.png)

