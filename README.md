# mqtt_video_player

A Video Player App based on Flutter. When a MQTT message is received, the video starts playing.

##  Dependency on Libraries

- video_player: https://pub.dev/packages/video_player
- mqtt_client: https://pub.dev/packages/mqtt_client

## Installation

### Install Flutter

Follow the instructions on https://docs.flutter.dev/get-started/install/macos .

### Add Video

Save the video you want to play in ```assets/video/``` in this working directory and call it ```video.mp4```. Or change the path in line 58 of main.dart.

### Change the MQTT settings

Change the MQTT server ip-adress, username, password and the topic in line 33 of main.dart. The topic message should contain ```play``` or change it in line 228 of main.dart.

### Load on your Device

Load the app on the Device of your choice.

