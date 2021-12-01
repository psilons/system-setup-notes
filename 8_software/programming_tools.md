# Programming Tools

## IDEs
I use [IntelliJ](https://www.jetbrains.com/idea/) and [Toolbox](https://www.jetbrains.com/toolbox-app/)
with annual license. Community and student licenses are available too. 
(I am not associated with JetBrains).

IntelliJ works with Java, Python, Web(HTML, CSS, Javascript), Markdown, and 
others. One tool rules all. 

It has project/module management, refactoring, test coverage, syntax searching
and many more. Though I don't know all other tools, I know it takes huge
effort to build similar tools, say in 10 years. Comparing IDEA 4 with IDEA 2020
should give you some ideas.



## Database GUI clients
[DataStrip](https://www.jetbrains.com/datagrip/) is included in the 
Jetbrains Toolbox.  

[DBeaver Community](https://dbeaver.io/) is a free and good tool.  

[This review](https://codingsight.com/10-best-mysql-gui-tools/)
has other tools (not restricted to MySQL), such as Aqua Data Studio and Navicat
 
JDBC paves the database vendor difference, so these GUIs can deal with many 
database vendors. For vendor specific, such as stored procedures, we have to
use vendor tools, such as Oracle Toad and MS SQL Management studio. Bulk
import/export tools are almost always specific, such as BCP, COPY, etc.

## Command Terminals
[Color Terminals](colors/color_wheel.md) setups terminals.  
Here are some [useful commands](windows_cmd.md).

## Version Control
[TortoiseGIT](https://tortoisegit.org/download/) is a GUI and shell extension.
It installs the git command line as well.

[SourceTree](https://www.sourcetreeapp.com/) is another option for Mac and Windows.
https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token


[WinMerge](https://winmerge.org) is a free good diff tool to compare files and 
folders locally.
 
## Linux Tools
There are several Linux tools:  
- [MobaXterm](https://mobaxterm.mobatek.net/) is a linux interactive GUI. 
  This is used mainly for remote access. The free version can create at most
  10 sessions. Here is the [setup](mobaxterm/mobaxterm.md).
- [unxutils](https://anaconda.org/binstar/unxutils/files) is a command line 
  package. These can be used in scripts. Wget is included, but curl is not.
  Windows 10 includes curl(run where curl on command). Otherwise, we can get 
  curl from [curl.se](https://curl.se/windows/).
- [cygwin](https://www.cygwin.com/) is more powerful, especially if we need to
  compile C++ code. Another option is [MinGW64](http://mingw-w64.org/doku.php).
  Or use [MS Visual Studio](vs_cmd.png).
- Windows new terminal package has a linux shell.  
- Oracle [VirtualBox](https://www.virtualbox.org/) or 
  [alternatives](https://beebom.com/best-virtualbox-alternatives/). 
  Here is the VirtualBox [setup](mobaxterm/mobaxterm.md).

## Java
- [Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
  or [OpenJDK 11](https://jdk.java.net/java-se-ri/11), [OpenJDK 14](https://jdk.java.net/java-se-ri/14)
  Currently, version 8 is still the main stream(JDK 8 update 202 is the last 
  free version). See these discussions for more info:
  [JRebel Java Report](https://www.jrebel.com/blog/2020-java-technology-report) (Very informative),
  [Which free version](https://stackoverflow.com/questions/58250782/which-free-version-of-java-can-i-use-for-production-environments-and-or-commerci),
  [Java Trend](https://www.infoq.com/articles/java-jvm-trends-2020/),
  [Java Trend](https://www.alibabacloud.com/blog/status-quo-and-technology-trend-report-of-java_596778),
  [Java versions and features](https://www.marcobehler.com/guides/a-guide-to-java-versions-and-features).
  
  [Spring Framework](https://docs.spring.io/spring-framework/docs/current/reference/html/overview.html)
  supports JKD8u60+ and JDK11.
  
  I would go with OpenJDK11 for now.
  
- [Maven](https://maven.apache.org/) or [Gradle](https://gradle.org/). 
- Google has a tool to show comparisons and trending, e.g., here is the 
  comparison between Java and Python:
  https://trends.google.com/trends/explore?geo=US&q=%2Fm%2F07sbkfb,%2Fm%2F05z1_
  It can compare libs too, but not versions, e.g., JDK 8 and JDK 11.

## Python
-  [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or 
   [Python](https://www.python.org/downloads/)

## Javascript
- [Node.js](https://nodejs.org/en/)
- [Vue.js](https://vuejs.org/)
- [DevExtreme](https://js.devexpress.com/)

## Graphics
- Icon generator: https://favicon.io/favicon-generator/
- Button generator: https://cooltext.com
- Text generator: https://text.imageonline.co/
- Code Image generator: https://carbon.now.sh/

## Documents
- Postscript: [Viewer](http://pages.cs.wisc.edu/~ghost/index.html)
- Tex: 
  IntelliJ has a plugin [TeXiFy-IDEA](https://github.com/Hannah-Sten/TeXiFy-IDEA).
  [LEd](https://www.latexeditor.org/) is simple.
  [Others](https://mirocupak.com/best-development-setup-for-latex/) may prefer 
  [TexStudio](https://www.texstudio.org/), [Lyx](https://www.lyx.org/) 
  or [TexMaker](https://www.xm1math.net/texmaker/).


## Other tools
- [JSONedit](http://tomeko.net/software/JSONedit/) is a small convenient JSON 
  editor, tree based.
- [Softerra LDAP browser](https://www.ldapadministrator.com/)
  
