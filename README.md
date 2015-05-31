# m2p
Maven .classpath generator for multi-maven project

### How to use

* Checkout and compile by 'mvn clean install'
* Copy target/m2p folder to the user's application folder
* Add ./m2p/bin to the $PATH
* Open shell console and locate multi-module maven project
* Run 'mvn eclipse:eclipse' and './m2p' in the parent folder of the multi-module maven project
* .classpath will be generated by using '.classpath' files from sub-modules
* Enjoy
