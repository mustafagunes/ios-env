# iOS Environment - Makefile

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A small makefile for the iOS development process that makes it easy.

### Features
  - git-flow
  - git
  - pod (pod tool install - init - install - repo update)
  - carthage (carthage tool install - init - install)
  - fastlane (fastlane tool install - init)


### Installation
Navigate to the main directory of your project.

*From commandline:*
```sh
$ curl -O https://raw.githubusercontent.com/mustafagunes/ios-env/master/Makefile
```

### Usage

![ScreenShot](https://github.com/mustafagunes/ios-env/blob/master/resource/ss.gif)

*For default all setup:*
```sh
$ make
```

*For pod setup:*
```sh
$ make pod
```

*For carthage setup:*
```sh
$ make carthage
```

*For all setup clean:*
```sh
$ make clean
```
