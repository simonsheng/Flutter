# Flutter
- [ ] Generate UML of Flutter classes, failed since the file is 40,000+ lines, it's a way big to generating a png or svg file. Detials as below:
  * https://pub.dev/packages/dcdg
  > dart pub global activate dcdg
  > dart pub global run dcdg -h

  * find flutter packages in /opt/flutter/packages/flutter
  * run the command in folder which has pubspec.yaml
  > dart pub global run dcdg -o structure.wsd

  * but the structure.wsd file is a way big to plantuml can handle.
  * https://plantuml.com/
  * Install Graphviz which has access issue. Fix it later.
  * Install plantuml.jar. Generated empty png and svg. Fix it later
  * Installed Eclipse plugin which generated empty png and svg. Fix it later
  * Installed extensions of VSCode which geneaerted empty png and svg. Fix it later.


