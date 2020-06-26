# Name TBD

Still finalizing the project mission and details

# Contributing

We welcome contributions from anyone. Feel free to pick up an issue (if there are any) and make a PR. If you want to be more involved, we coordinate a lot of the bigger picture of this project on a Slack group, and you can send [Bryan](https://github.com/potterbm) a message or an email for an invite.

## Development Environment

This app is written in [Flutter](https://flutter.dev), a cross-platform UI framework in the [Dart](https://dart.dev) language.

#### Prerequisites

Make sure you have `git` installed, along with `ruby` (it comes installed by default on MacOS). You’ll also want a package manager set up with basic command line tools installed.

#### Setup

1. Make sure your XCode is at the latest version, then install command line tools for it and accept any licenses
```sh
sudo xcode-select --install
sudo xcodebuild -license accept
```

2. Download and install Flutter by following [the instructions on their site](https://flutter.dev/docs/get-started/install)

3. Clone this repository
```sh
git clone git@github.com:Voting-Guide-App/app.git
```

4. Set up your IDE. Install the [Flutter extension for VSCode](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter) or use [one of their other suggested IDEs](https://flutter.dev/docs/get-started/editor)

5. Run `flutter doctor` and validate that it has no errors (warnings can be fine). You may have to install cocoapods:
```sh
sudo gem install cocoapods

# On a Mac
sudo gem install -n /usr/local/bin cocoapods
```

## Resources

* [Dart language tour](https://dart.dev/guides/language/language-tour)
* [Flutter sample app](https://flutter.dev/docs/get-started/codelab)
* [Useful Flutter samples](https://flutter.dev/docs/cookbook)
* [Dart packages](https://pub.dev)
* [Android Studio]()
