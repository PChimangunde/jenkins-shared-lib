# jenkins-shared-lib
this repo hold shared library for jenkins code

**What is jenkins shared lib?**
it is a universal code which we can use for any project.
it has advantage like 
we can use the code multiple time
we can create the functions which we can use multiple way 

**How to do it?**
## step 1 : create a folder /vars/ ... (in this folder we can create a .groovyfile for which i want to create the function and by this name only we can call this function in jenkins file)
example create hello.groovy file inside /vars/ folder so you can call the function by name hello() while writing the groovy syntax

**Syntax for the function**

defCall ( pass the variable which you want to pass) {

write the code here   
  }

Clone.groovy example :
step 1 : create clone.groovy file in /vars/clone.groovy 
step 2 : write the function in created file
        syntax 
        
        def call(String url, String branch) {
                git url: url, branch: branch
        }



Clo
  
