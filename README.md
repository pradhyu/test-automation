test-automation
===============

Test automation related projects

fitnesse: 
Fitnesse


http://fitnesse-launcher-maven-plugin.googlecode.com/svn/maven/site/fitnesse-launcher-maven-plugin/faq.html


Describe your new note here.

[INFO] ------------------------------------------------------------------------
adminuser@adminuser-VirtualBox:~/java/test/fitnesse/fitnesse-launcher-maven-plugin-read-only$ svn checkout http://fitnesse-launcher-maven-plug\
in.googlecode.com/svn/trunk/ fitnesse-launcher-maven-plugin-read-only

;; maven3 required
mvn clean install

---------------------------------------------------------
[INFO] Reactor Summary:
[INFO]
[INFO] FitNesse Launcher Parent .......................... SUCCESS [5.989s]
[INFO] FitNesse Launcher Maven Plugin .................... SUCCESS [45.097s]
[INFO] Example Java Project .............................. SUCCESS [11.956s]
[INFO] Example Spring Framework Project .................. SUCCESS [3.585s]
[INFO] Example SQL Project ............................... SUCCESS [10.576s]
[INFO] Example Webapp Project ............................ SUCCESS [3.617s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 1:21.338s
[INFO] Finished at: Thu Oct 16 02:03:09 BST 2014
[INFO] Final Memory: 29M/193M
[INFO] ------------------------------------------------------------------------
adminuser@adminuser-VirtualBox:~/java/test/fitnesse/fitnesse-launcher-maven-plugin-read-only$ 

Import sample project in eclipse: 

		<!-- 
                This profile is for use when writing tests using the FitNesse wiki.
				Simply run 'mvn verify -P wiki' and use a browser to visit http://localhost:9123/SpringExample
			 -->
	
