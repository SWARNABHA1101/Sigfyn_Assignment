# Sigfyn_Assignment
Solution and Code to all the assignment questions

Link to Google Colab notebook for both the codes, please click on the below hyperlink.
1) [Merge Sort](https://colab.research.google.com/drive/1OHe9mCsL9MlcsMgtIDj_j7I1HGMI6kFp?usp=sharing)  <br/>
2) [Depth First Search](https://colab.research.google.com/drive/17T9UfWzV-JnEvLP8zZxdU4y5SD_v4EzO?usp=sharing) <br/>

## My First React Native App
This is an example for `react-native`, which display the NBA informations, such as teams, players, and so on. Relative data is from `stat.nba.com`, you can reference the [wiki page](https://github.com/seemethere/nba_py/wiki/stats.nba.com-Endpoint-Documentation) of `nba_py` on github.

This example tells us how to use React Native, Redux, and more.<br/>
Github Repo Link for the React-Native App- https://github.com/SWARNABHA1101/React-Native-first-app

## Requirements

1. [React Native](http://facebook.github.io/react-native/docs/getting-started.html) (follow iOS and Android guides)
  - Xcode 7.3+
2. [CocoaPods](http://cocoapods.org) (only for iOS)
  - Version 1.0+ recommended (`gem install cocoapods --pre`)
  
  ## Setup

1. **Clone the repo**

  ```
  $ git clone https://github.com/SWARNABHA1101/React-Native-first-app.git
  $ cd react-native-first-app
  ```
  2. **Install dependencies** (npm v3+)

  ```
  $ npm install
  $ (cd ios; pod install)       # only for iOS version
  ```
3. **Running on Android**

  ```
  $ react-native run-android
  $ adb reverse tcp:8081 tcp:8081     # required to ensure the Android app can access the Packager server
  ```

4. **Running on iOS**

  ```
  $ react-native run-ios
  ```
