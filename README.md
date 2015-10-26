# JasmineForAngularJS
Jasmine Unit Test For AngularJS sample using Reshaprer and Chutzpa as test runner


For installing Chutzpaa:
 
1: Install the Chutzpah Visual Studio Extension. 
https://visualstudiogallery.msdn.microsoft.com/f8741f04-bae4-4900-81c7-7c9bfb9ed1fe
2: Install the Jasmine test framework nuget package. 
From the package manager console, run: install-package JasmineTest

For installing Resharper:
1. Get Resharper
https://www.jetbrains.com/resharper/download/
2. After installation, Please set the configuration as highlighted in below image

![pastedimage 2](https://cloud.githubusercontent.com/assets/10474169/10744818/a7ce84c4-7c0a-11e5-9325-6751d370a7c9.png)

Bookmark below URL, its a cheat sheet for jasmine syntax 
http://ricostacruz.com/cheatsheets/jasmine.html


Below images will highlight new changes in ngninja project
1. Directory Structure
2. Resharper test Runner
3. Chutzpa test runner

![pastedimage](https://cloud.githubusercontent.com/assets/10474169/10744819/a7cef3c8-7c0a-11e5-8bf2-3d58eb36ebd9.png)

How to code Jasmine Test Case
1. Mention test file name
2. Mock all dependencies for module which you are testing
3. mention angular module name for which you are writing test cases
4. Inject dependencies and initialize all variables 
5. Write unit test for each functionality 

P.S. I have written unit test cases for Candidate Module(Controller, Service, main Candidate file and Shared http service, total 18 Unit test cases)

![pastedimage 1](https://cloud.githubusercontent.com/assets/10474169/10744817/a7ba1cc8-7c0a-11e5-978a-d841bcf3d226.png)

