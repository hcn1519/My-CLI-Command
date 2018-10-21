# My CLI Command

# Git

## Add specific lines from files

```
$ git add -p
y = add, n = not add, p = separate hunks(become smaller)
```


# Xcode

## List All available simulators

```
$ xcrun simctl list
```

## Take screenshot of simulator

```
$ xcrun simctl io booted screenshot screen.png
```

## Record video of simulator

```
$ xcrun simctl io booted recordVideo demo3.mov
```

## Build Xcode Project using Command Line

```
$ xcodebuild -project myProject.xcodeproj

// Using workspace
$ xcodebuild -workspace myProject.xcworkspace

// Specify scheme
$ xcodebuild -project myProject.xcodeproj -scheme myScheme

// Specify build-configuration
$ xcodebuild -project myProject.xcodeproj -configuration Debug

// Specify destination
$ xcodebuild -project myProject.xcodeproj -destination "OS=12.0,name=iPhone X"
```
