Technical Requirements
----------------------------------------------------------------------------------------------------
* Must have:
  1. Operating system: Mac or Windows
  2. Software platform: Java
      - JDK
  3. Java IDE: IntelliJ IDEA
  4. Version control: Git
  5. Git repository hosting service: GitHub
  6. Build tool: Maven
  7. Software-testing framework: Selenium
  8. Testing framework: TestNG

Setup
----------------------------------------------------------------------------------------------------
* Fork the repository
  - To fork the Spoon-Knife repository, click the Fork button in the header of the repository. 
  - Sit back and watch the forking magic. When it’s finished, you’ll be taken to your copy of the Spoon-Knife repository.

* Clone your fork
  - On your GitHub account, navigate to the main page of the repository.
  - Under the repository name, click Clone or download. alt text
  - In the Clone with HTTPs section, copy the clone URL for the repository.
  - Open Terminal and navigate to your workspace.
  - Type git clone, and then paste the URL you copied. `git clone https://github.com/YOUR-USERNAME/Team2WebAutomation.git`
  - Press Enter. Your local clone will be created.

* Switch to your branch
  - Switch over to the branch "yourfirstname" when you want to add new commits to it.
  - You can see all branches created by using: git branch. The asterisk indicates the current active branch.
  - Use the checkout command to switch branch. git checkout [name_of_your_branch]

* After you have done a lot of work on your branch
  - Stage the file(s) for commit to your local repository. git add .
  - Commit the file(s) that you've staged in your local repository. git commit -m "Add message here"
  - Push the changes in your local repository to GitHub: git push origin [name_of_your_branch]

* Making a Pull Request
  - At last, you’re ready to propose changes into the main project!
  - On your GitHub account, navigate to the main page of the repository.
  - In the "Branch" menu, choose the branch that contains your commits. alt text
  - To the right of the Branch menu, click New pull request. Use the base branch dropdown menu to select the 
  branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made 
  your changes in.
  - Type a title and description for your pull request.
  - Click Create pull request.

Explanations
----------------------------------------------------------------------------------------------------------------------------------
* `/AliBaba`
  - Test cases: includes page object model, page factory.
  - Data driven: reads testdata from xls files, google sheets.
* `/AliBabaExtent-Report`
  - Generates extent report in html format
* `/Cigna`
  - Test cases: includes page object model, page factory.
* `/CignaExtent-Report`
  - Generates extent report in html format
* `/Generic`
  - Generic module is created to manage all the common setttings for all the modules.
* `/HomeDepot`
  - Test cases: includes page object model, page factory.
  - Data driven: reads testdata from xls files, google sheets.
* `/HomeDepotExtent-Report`
  - Generates extent report in html format
* `/Cigna`
  - Test cases: includes page object model, page factory.
* `.gitignore`
  - Git uses this file to determine which files and directories to ignore, before you make a commit.
* `pom.xml`
  - A Project Object Model or POM is the fundamental unit of work in Maven.
  - It is an XML file that contains information about the project and configuration details used by Maven to build the project.

References
-----------------------------------------------------------------------------------------------------------------------------------
* Java API
  - [Oracle API Documents](https://docs.oracle.com/javase/8/docs/api/)
* Git and GitHub learning resources
  - [Git hub](https://help.github.com/articles/good-resources-for-learning-git-and-github/)
* POM Reference
  - [Maven POM Documents](https://maven.apache.org/pom.html)
  - [Maven Repository](https://docs.oracle.com/javase/8/docs/api/)
* Selenium Java API
  - [Selenium Documents](https://seleniumhq.github.io/selenium/docs/api/java/)
  - [Selenium jar files and Drivers](http://www.seleniumhq.org/download/)
* TestNG API
  - [TestNG Documents](https://jitpack.io/com/github/cbeust/testng/master/javadoc/)
* Working with GoogleSheet
  - [GoogleSheet API Document](https://developers.google.com/sheets/api/quickstart/java)
* Apache Maven Project
  - [Maven CLI Options Reference](http://maven.apache.org/ref/3.1.0/maven-embedder/cli.html)
* JMeter
  - [Apache JMeter](http://jmeter.apache.org/)
* Mobile Testing resources
  - [Node/npm](https://www.npmjs.com/package/npm)
  - [Appium](http://appium.io/downloads.html)
  - [Android SDK](https://developer.android.com/studio/index.html)
