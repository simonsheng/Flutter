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


* Widget. 
  * PreferredSizeWidget. 
    * AppBar. 
    * CupertinoTabBar. 
    * ObstructingPreferredSizeWidget. 
    * PreferredSize. 
    * Tab. 
    * TabBar. 
  * ProxyWidget. 
    * NotificationListener.  
    * InheritedWidget. 
      * BottomNavigationBarTheme
      * ButtonBarTheme. 
      * CheckboxTheme. 
      * CupertinoUserInterfaceLevel. 
      * DataTableTheme. 
      * DefaultAssetBundle. 
      * Directionality. 
      * DropdownButtonHideUnderline. 
      * FlexibleSpaceBarSettings. 
      * FocusTraversalOrder. 
      * HeroControllerScope. 
      * InheritedModel. 
      * InheritedNotifier. 
      * InheritedTheme. 
      * MediaQuery. 
      * PrimaryScrollController. 
      * RadioTheme. 
      * ScrollbarTheme. 
      * ScrollConfiguration. 
      * SelectionRegistrarScope. 
      * SwitchTheme. 
      * UnmanagedRestorationScope. 
    * ParentDataWidget. 
      * Flexible. 
      * KeepAlive. 
      * LayoutId. 
      * Positioned. 
      * TableCell. 
  * RenderObjectWidget. 
    * ConstrainedLayoutBuilder. 
    * LeafRenderObjectWidget. 
    * ListWheelViewport. 
    * MultiChildRenderObjectWidget. 
    * RenderObjectToWidgetAdapter. 
    * SingleChildRenderObjectWidget. 
    * SliverWithKeepAliveWidget. 
    * Table. 
  * StatefulWidget. 
    * ActionListener  
    * Actions. 
    * AndroidView. 
    * AnimatedCrossFade. 
    * AnimatedList. 
    * AnimatedSize. 
    * AnimatedSwitcher. 
    * AnimatedWidget. 
    * AppBar. 
    * AutofillGroup. 
    * AutomaticKeepAlive. 
    * BackButtonListener. 
    * BottomAppBar. 
    * BottomNavigationBar. 
    * BottomSheet. 
    * ButtonStyleButton. 
    * CalendarDatePicker. 
    * Checkbox. 
    * CupertinoActivityIndicator. 
    * CupertinoApp. 
    * CupertinoButton. 
    * CupertinoContextMenu. 
    * CupertinoContextMenuAction. 
    * CupertinoDatePicker. 
    * CupertinoNavigationBar. 
    * CupertinoPageScaffold. 
    * CupertinoPicker. 
    * CupertinoSearchTextField  
    * CupertinoSegmentedControl. 
    * CupertinoSlider. 
    * CupertinoSlidingSegmentedControl. 
    * CupertinoSliverNavigationBar. 
    * CupertinoSliverRefreshControl. 
    * CupertinoSwitch. 
    * CupertinoTabScaffold. 
    * CupertinoTabView. 
    * CupertinoTextField. 
    * CupertinoTimerPicker. 
    * DatePickerDialog. 
    * DateRangePickerDialog. 
    * DefaultTabController. 
    * Dismissible. 
    * Draggable. 
    * DraggableScrollableSheet. 
    * DragTarget. 
    * DrawerContasdfroller. 
    * DropdownButton. 
    * DualTransitionBuilder. 
    * EditableText. 
    * ExpandIcon. 
    * ExpansionPanelList. 
    * ExpansionTile  
    * FadeInImage. 
    * FlexibleSpaceBar. 
    * Focus. 
    * FocusableActionDetector. 
    * FocusTraversalGroup. 
    * Form. 
    * FormField. 
    * FutureBuilder. 
    * GlowingOverscrollIndicator. 
    * Hero. 
    * ImageImplicitlyAnimatedWidget. 
    * Ink. 
    * InputDatePickerFormField. 
    * InputDecorator. 
    * InteractiveViewer. 
    * LicensePage. 
    * ListWheelScrollView. 
    * Localizations. 
    * Material. 
    * MaterialApp. 
    * MaterialBanner. 
    * MergeableMaterial. 
    * NavigationRail. 
    * Navigator. 
    * NestedScrollView. 
    * Overlay. 
    * PageView. 
    * PaginatedDataTable. 
    * PlatformMenuBar. 
    * PlatformViewLink. 
    * PopupMenuButton. 
    * PopupMenuEntry. 
    * ProgressIndicator. 
    * Radio. 
    * RangeSlider. 
    * RawAutocomplete. 
    * RawChip. 
    * RawGestureDetector. 
    * RawKeyboardListener. 
    * RawMaterialButton. 
    * RawScrollbar. 
    * RefreshIndicator. 
    * ReorderableList. 
    * ReorderableListView. 
    * RestorationScope. 
    * RootRestorationScope. 
    * Router. 
    * Scaffold. 
    * ScaffoldMessenger. 
    * Scrollable. 
    * ScrollNotificationObserver. 
    * SelectableRegion. 
    * SelectableText. 
    * SelectionArea. 
    * SelectionContainer. 
    * SemanticsDebugger. 
    * SharedAppData. 
    * ShortcutRegistrar. 
    * Shortcuts. 
    * Slider. 
    * SliverAnimatedList. 
    * SliverAppBar. 
    * SliverReorderableList. 
    * SnackBar. 
    * SnackBarAction. 
    * StatefulBuilder. 
    * StatusTransitionWidget. 
    * Stepper. 
    * StreamBuilderBase. 
    * StretchingOverscrollIndicator. 
    * TabBar. 
    * TabBarView. 
    * TextField. 
    * TextSelectionGestureDetector  
    * TickerMode. 
    * TimePickerDialog. 
    * Tooltip. 
    * UiKitView. 
    * UniqueWidget. 
    * UserAccountsDrawerHeader. 
    * ValueListenableBuilder. 
    * WidgetInspector. 
    * WidgetsApp. 
    * WillPopScope. 
    * YearPicker. 
  * StatelessWidget. 
    * AboutDialog. 
    * AboutListTile. 
    * ActionChip
    *  AlertDialog
    *  AnimatedIcon
    *  Autocomplete
    *  BackButton
    *  BackButtonIcon
    *  Banner
    *  Builder
    *  ButtonBar
    *  CallbackShortcuts
    *  Card
    *  CheckboxListTile
    *  CheckedModeBanner
    *  Chip
    *  ChoiceChip
    *  CircleAvatar
    *  CloseButton
    *  Container
    *  CupertinoActionSheet
    *  CupertinoActionSheetAction
    *  CupertinoAlertDialog
    *  CupertinoDialogAction
    *  CupertinoFormRow
    *  CupertinoFormSection
    *  CupertinoFullscreenDialogTransition
    *  CupertinoNavigationBarBackButton
    *  CupertinoPageTransition
    *  CupertinoPickerDefaultSelectionOverlay
    *  CupertinoPopupSurface
    *  CupertinoTabBar
    *  CupertinoTextSelectionToolbar
    *  CupertinoTextSelectionToolbarButton
    *  CupertinoTheme
    *  DataTable
    *  DefaultTextEditingShortcuts
    *  Dialog
    *  DisplayFeatureSubScreen
    *  Divider
    *  DraggableScrollableActuator
    *  Drawer
    *  DrawerHeader
    *  DropdownMenuItem
    *  ExcludeFocus
    *  ExcludeFocusTraversal
    *  FilterChip
    *  FloatingActionButton
    *  FlutterLogo
    *  GestureDetector
    *  GridPaper
    *  GridTile
    *  GridTileBar
    *  HeroMode
    *  HtmlElementView
    *  Icon
    *  IconButton
    *  ImageIcon
    *  InkResponse
    *  InputChip
    *  KeyboardListener
    *  KeyedSubtree
    *  ListTile
    *  MaterialButton
    *  ModalBarrier
    *  NavigationBar
    *  NavigationDestination
    *  NavigationIndicator
    *  NavigationToolbar
    *  OrientationBuilder
    *  PageStorage
    *  Placeholder
    *  PositionedDirectional
    *  PreferredSize
    *  RadioListTile
    *  ReorderableDragStartListener
    *  SafeArea
    *  Scrollbar
    *  ScrollView
    *  SimpleDialog
    *  SimpleDialogOption
    *  SingleChildScrollView
    *  SliverFillRemaining
    *  SliverFillViewport
    *  SliverPersistentHeader
    *  SliverSafeArea
    *  SliverVisibility
    *  Spacer
    *  Switch
    *  SwitchListTile
    *  Tab
    *  TabPageSelector
    *  TabPageSelectorIndicator
    *  Text
    *  TextSelectionToolbar
    *  TextSelectionToolbarTextButton
    *  Theme
    *  Title
    *  ToggleButtons
    *  TooltipVisibility
    *  UnconstrainedBox
    *  VerticalDivider
    *  Visibility

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
