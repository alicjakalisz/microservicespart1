1. We are removing src file and configure parent pom xml to have depependecy management for individual modules and dependencies for all the modules
2. in the root folder we right click and create module customer
3. Inside parent pom, new section has appeared - modules with modules customer in
4. Customer module will have src and its own pom.xml that will be pointing to parent pomx.xml. 
5. in Customer pom we add spring-boot-web dependency (it has only lombok and test and these were added for all in general dependencies section of parent pom)
6. Create CustomerApplication class for start up
once we added boot-web to this module. It will take this dependency from parent spring-boot-dependencies that holds all boot dependencies undder
Dependency Management tag. Submodules can pick what dependency they need from this general dependency and some of them will have boot web some will have others.
6.in Customer module resources create application.yml and declare port and name of the module.
7. create banner.txt
8. Create class Customer.
9. 
