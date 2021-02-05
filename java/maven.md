### Maven
<details>
  <summary>What is Maven?</summary>
  Maven is a build and dependency tool for managing Java applications. Maven implicitly uses javac for compilation and jar/war/ear for archiving. Maven project has its own folder structure
 
 ![Maven Structure](https://i2.wp.com/www.dineshonjava.com/wp-content/uploads/2016/10/Maven-dirctory-structure.png?w=530&ssl=1)
 
</details>
<details>
  <summary>Why Maven?</summary>
  Since this tool has its own folder strucuter it's easy for the tool to compile and build multiple packages and classes. Ant was used to solve the problem of compiling multiple class files with same packages. Maven is an advanced tool which uses Ant for playing around with directorires inside maven plugins.
</details>
<details>
  <summary>List of Maven Commands?</summary>
  There are 3 commands used,
  - mvn compile
  - mvn test
  - mvn install
</details>
<details>
  <summary>Maven Lifecycle phases</summary>
  - generate-sources
  - compile
  - test-compile
  - test
  - package
  - integration-test
  - install
  - deploy
  
  ![Maven Lifecylce](https://www.bogotobogo.com/Java/tutorials/images/MavenLifeCycle/DefaultLifeCycle.png)
  
</details>
<details>
  <summary>What is archetype?</summary>
  Archetype is one of the maven plugin used for scaffolding Java project.
  example: 
  ```
  maven-archetype-quickstart
  ```
  Is an archetype which generates a sample Maven project: project. 
</details>
<details>
  <summary>Build Tool PPT</summary>

  [Maven BuildTool](https://github.com/web-slate/backend-papers/blob/master/doc/buildtools-maven.ppt?raw=true)
    
</details>



