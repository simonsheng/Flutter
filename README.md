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
## [Flutter基础视频教程—427个组件全解析](https://www.liujunmin.com/tags/%E7%BB%84%E4%BB%B6%E5%88%86%E6%9E%90/)  
[Flutter继承关系图 03:01](https://www.bilibili.com/video/BV1BM4y1L71Z?p=1)
* Dart Source Code in flutter: /opt/flutter/bin/cache/dart-sdk
* Flutter Source Code in flutter: /opt/flutter/packages
(9/20/2022)
* Flutter/foundation/diagnostics.dart -- [mixin Diagnosticable](https://api.flutter.dev/flutter/foundation/Diagnosticable-mixin.html). 
* [DiagnosticableTree](https://api.flutter.dev/flutter/foundation/DiagnosticableTree-class.html). 

Flutter深入浅出---MaterialApp
45:47
P3
Flutter深入浅出---Scaffold
28:51
P4
Flutter深入浅出---AppBar
13:56
P5
Flutter深入浅出---TabBar
11:36
P6
Flutter深入浅出---Padding、AnimatedPadding
05:32
P7
Flutter深入浅出---Align、AnimatedAlign
04:33
P8
Flutter深入浅出---ConstrainedBox、BoxConstraints、UnconstrainedBox
08:45
P9
Flutter深入浅出---SizeBox、FittedBox
07:16
P10
Flutter深入浅出---OverflowBox、SizedOverflowBox
03:20
P11
Flutter深入浅出---AspectRatio、FractionallySizedBox
03:18
P12
Flutter深入浅出---Container、AnimatedContainer
09:44
P13
Flutter深入浅出---ClipRect、ClipRRect
04:49
P14
Flutter深入浅出---ClipOval、ClipPath
03:54
P15
Flutter深入浅出---Center、完结
03:17
