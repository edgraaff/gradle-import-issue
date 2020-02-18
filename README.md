# "Import project" issue

This project is a demonstration to point out a possible deadlock, which occurrs when for example importing this project in Eclipse (as an existing Gradle project).

Steps to reproduce:

1.  Clone this repository, or download the contents
2.  Open Eclipse
3.  File -> Import -> Existing Gradle project -> choose the `multi-web-app` module (which will include all others)
