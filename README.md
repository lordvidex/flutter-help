# Flutter Help
I compiled this to help flutter programmers with one or two packages to import in case of confusion that i came across while 
starting flutter
## Displaying SplashScreen while initializing app
This comes in handy when you have to initialize plugins like `notifications`, `shared_preferences` and so many
other packages while displaying splash screen to keep the user entertained 🙃.
```dart
main() async {
  //`runApp()` can be called more than once in the app
  runApp(new SplashScreen());
  var foo = await init();
  runApp(new FullApp(foo: foo));
}
```
## Media Players
- [Audio Player and Video Player](https://www.codementor.io/@ponnamkarthik3/flutter-media-playback-audio-video-yvgzj7516) :
```
video_player
audioplayers
file_picker
```
## Loading Spinner
- [ModalProgressHUD](https://pub.dev/packages/modal_progress_hud)
## PDF Reader
- [flutterpdfview](https://pub.dev/packages/flutter_pdfview)
## Fancy Bottom Navigation Bar
- [bottom_navy_bar](https://pub.dev/packages/bottom_navy_bar)
## Fancy Scrolling effects
- [Flutter Slivers Overview: SliverList, SliverGrid, SliverToBoxAdapter, SliverFillRemaining [Video]](https://www.youtube.com/watch?v=k2v3gxtMlDE)
- [Flutter Slivers Overview: SliverAppBar, SliverPersistentHeader [Video]](https://www.youtube.com/watch?v=E3-WdYBrEDc)  
## Shimmer Effects for ListLoaders
- [shimmer](https://pub.dev/packages/shimmer)
## Fancy Text typer and text animations
- [Flutter animated-text-kit](https://pub.dev/packages/animated_text_kit)
## Notifications
- [Flutter Local Notifications [Video]](https://www.youtube.com/watch?v=950jZeaqbdU)
- [Watch out for awesome_notifications](https://pub.dev/packages/awesome_notifications)
## APIs and assets catalogues
- [Free sounds](https://freesound.org/)
- [Font Awesome Flutter Icon Pack](https://pub.dev/packages/font_awesome_flutter)
## Dart Algorithm Practices 
- [Exercism](https://exercism.io/tracks/dart)
- [CodeWars](https://www.codewars.com/dashboard)
- [C++ codeforces](codeforces.com)
- [c++ and Dart - SPOJ](https://www.spoj.com/problems/classical/)
## Notifications
- [Local Notifications](https://pub.dev/packages/flutter_local_notifications)
## Time line widget
- [https://pub.dev/packages/timeline_tile](https://pub.dev/packages/timeline_tile)  

*Feel free to **star** this page if you found this useful and make a **pull request** if you want to make an addition to the list to help others*
