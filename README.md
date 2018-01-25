# weather_icons_flutter

[Weather icons](https://github.com/erikflowers/weather-icons) wrapper for [Flutter.io](https://flutter.io/)

## Dependency

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
  weather_icons_flutter: ^1.0.0
```

## Usage

```dart
import 'package:weather_icons_flutter/weather_icons_flutter.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return new IconButton(
      // Use the WeatherIcons class for the IconData
      icon: new Icon(WeatherIcons.stars),
      onPressed: () { print("Pressed"); }
     );
  }
}
```
