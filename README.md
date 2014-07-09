SBT template project
============

A SBT template project for quick start

Following the below steps to setup a sbt project quickly:

1. Install Scala 2.10.2 (Download and add bin folder to path)
 If you already have Scala installed, just modify `build.sbt` file with your Scala version.

 ``` sbt
  scalaVersion := "<Scala_verion_on_your_machine>"
 ```
2. Install SBT (`brew install sbt`)
3. Clone this project to some place in your machine.  
 `git clone https://github.com/fedcuit/sbt-template.git`
4. Run `sbt gen-idea` in root folder
  ![generate intelliJ project](https://raw.githubusercontent.com/fedcuit/transfer-station/master/gen-idea.png "sbt gen-idea")
5. Open root folder in IntelliJ

 ![open sbt project](https://raw.githubusercontent.com/fedcuit/transfer-station/master/open.png "import sbt project")
 ![choose sbt project](https://raw.githubusercontent.com/fedcuit/transfer-station/master/choose.png "choose sbt project")

All set, let's rock!
