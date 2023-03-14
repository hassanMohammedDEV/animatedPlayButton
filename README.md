<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

animated button package.

## Features

can use some methods in this package.

## Getting started

package is animated button.

## Usage

animated_play_button/lib/src/animated_button.dart

```dart
import 'package:animated_play_button/animated_play_button.dart';
import 'package:flutter/material.dart';

import 'home_screen.dart';

class SettingsScreen extends StatelessWidget {
  const SettingsScreen({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: AnimatedPlayButton(onPressed: () {  },pauseIconColor: Colors.black,),
      ),
    );
  }
}
```

## Additional information

The package idea from https://www.youtube.com/watch?v=L01UGrbtHY0
