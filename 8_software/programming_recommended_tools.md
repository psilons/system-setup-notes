# Programming Tools

Google has a tool to show comparisons and trending, e.g., here is the comparison between Java and 
Python:

https://trends.google.com/trends/explore?geo=US&q=%2Fm%2F07sbkfb,%2Fm%2F05z1_

It can compare libs too, but not versions, e.g., JDK 8 and JDK 11.

## IDEs
[IntelliJ](https://www.jetbrains.com/idea/), one tool fits all.
  - licenses:
    - Community and student licenses.
    - Annual subscription license with [Toolbox](https://www.jetbrains.com/toolbox-app/)
  - Plugins:
    - Python
    - Scala
    - Vue.js
    - TeXiFy IDEA
    - Batch Scripts Support
    - PDF Viewer
    - SequenceDiagram
  - Languages:
    - Java
    - Scala
    - Python
    - JavaScript
    - HTML/CSS
    - MarkDown
    - Latex
  - Other features:
    - project/module 2 level management: much needed feature with many down the road consequences.
      Standardized directory structures across languages, src/test/out
    - refactoring, cross references, and global search.
    
## Database GUI clients
[DataStrip](https://www.jetbrains.com/datagrip/) is included in the 
Jetbrains Toolbox.  

JDBC hides the database vendor difference, so these GUIs can deal with many 
database vendors. For vendor specific, such as stored procedures, we have to
use vendor tools, such as Oracle Toad and MS SQL Management studio. Bulk
import/export tools are almost always specific, such as BCP, COPY, etc.

## Version Control
Use GitHub:
- https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token

Git Clients
- [TortoiseGIT](https://tortoisegit.org/download/) is a GUI and shell extension for Windows.
It installs the git command line as well.

- [SourceTree](https://www.sourcetreeapp.com/) is another option for Mac and Windows.

[WinMerge](https://winmerge.org) is a free good diff tool to compare files and 
folders locally on Windows. Apple's Developer Tools has FileMerge.

## Java
- [Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Maven](https://maven.apache.org/) or [Gradle](https://gradle.org/). 
- [Spring Framework](https://docs.spring.io/spring-framework/docs/current/reference/html/overview.html)

## Python
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html), can create different environments
  for different versions. One nice feature in Conda is that it hides some of C++ lib dependencies 
  with precompiled binaries for different OS.
- Use [Python](https://www.python.org/downloads/) in conjunction with
  [python penv](https://github.com/pyenv/pyenv) for environment switching.

## Javascript
- [Node.js](https://nodejs.org/en/)
- [Vue.js](https://vuejs.org/)
- [DevExtreme](https://js.devexpress.com/)

## Latex
[MikTex](https://miktex.org/download) for Windows and Mac.

## HTTP Rest Service
- [Postman](https://www.postman.com/product/api-client/)
- [Insomnia](https://insomnia.rest/)

## Graphics
- Icon generator: https://favicon.io/favicon-generator/
- Button generator: https://cooltext.com
- Text generator: https://text.imageonline.co/
- Code Image generator: https://carbon.now.sh/
