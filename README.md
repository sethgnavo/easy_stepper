![Easy Stepper](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/logo.png)

## About

[![Pub Version](https://img.shields.io/pub/v/easy_stepper.svg?label=pub&color=blue)](https://pub.dev/packages/easy_stepper/versions)
[![GitHub Stars](https://img.shields.io/github/stars/ma7moud3osman/easy_stepper?color=yellow&label=Stars)](https://github.com/ma7moud3osman/easy_stepper/stargazers)
[![GitHub opened issues](https://img.shields.io/github/issues/ma7moud3osman/easy_stepper?color=red)](https://github.com/ma7moud3osman/easy_stepper/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/ma7moud3osman/easy_stepper)](https://github.com/ma7moud3osman/easy_stepper/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub last commit](https://img.shields.io/github/last-commit/ma7moud3osman/easy_stepper)](https://github.com/ma7moud3osman/easy_stepper/commits/main)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ma7moud3osman/easy_stepper?label=size)
[![GitHub forks](https://img.shields.io/github/forks/ma7moud3osman/easy_stepper)](https://github.com/ma7moud3osman/easy_stepper/network/members)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](https://github.com/ma7moud3osman/easy_stepper/blob/main/LICENSE)


A fully customizable, beautiful and easy to use stepper widgets with different variations.

## Description

The stepper widgets help you to show or collect information from users using organized steps.

## Install

In the `pubspec.yaml` of your flutter project, add the following dependency:

```yaml
dependencies:
  easy_stepper: <latest_version>
```

In your library add the following import:

```dart
import 'package:easy_stepper/easy_stepper.dart';
```

## Getting started

* Simply import `package:easy_stepper/easy_stepper.dart`.

* __Important:__ The `direction` argument controls whether the stepper is displayed horizontally or vertically. A horizontal Stepper can be wrapped within a Column with no issues. However, if wrapped within a row, it _must also be_ wrapped within the built-in _Expanded_ widget. The same applies to the vertical Stepper.

* __Validation:__ To enable validation before the next step is reached, set the `steppingEnabled` property to an appropriate value in a `StatefulWidget`.

* __Controlling Steppers:__ All steppers are controlled using the `activeStep` property. You can control a stepper by tapping individual steps.

    * See examples __[here](https://pub.dev/packages/easy_stepper/example)__.

* To customize the color, border, etc., wrap a stepper widget inside a `Container` and specify it's `decoration` argument.

Example:

```dart
     EasyStepper(
       activeStep: activeStep,
       lineLength: 70,
       stepShape: StepShape.rRectangle,
       stepBorderRadius: 15,
       borderThickness: 2,
       padding: 20,
       stepRadius: 28,
       finishedStepBorderColor: Colors.deepOrange,
       finishedStepTextColor: Colors.deepOrange,
       finishedStepBackgroundColor: Colors.deepOrange,
       activeStepIconColor: Colors.deepOrange,
       loadingAnimation: 'assets/loading_circle.json',
       steps: const [
         EasyStep(
           icon: Icon(Icons.add_task_rounded),
           title: 'Order Placed',
         ),
         EasyStep(
           icon: Icon(Icons.category_rounded),
           title: 'Preparing',
         ),
         EasyStep(
           icon: Icon(Icons.local_shipping_rounded),
           title: 'Shipping',
         ),
         EasyStep(
           icon: Icon(Icons.door_back_door_outlined),
           title: 'On The Way',
         ),
         EasyStep(
           icon: Icon(Icons.check_circle_outline_outlined),
           title: 'Delivered',
         ),
         EasyStep(
           icon: Icon(Icons.reviews_outlined),
           activeIcon: Icon(Icons.reviews_rounded),
           title: 'Add Review',
         ),
       ],
       onStepReached: (index) => setState(() => activeStep = index),
     ),
```


## Features

Simple to use icon stepper widget, wherein each icon defines a step. Hence, the total number of icons represents the total number of available steps. [See Example](https://pub.dev/packages/easy_stepper/example).

## Horizontal-Stepper

* __With Title:__  

![Horizontal-Stepper](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/stepper-horizontal.gif)

![horizontal_dotted](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/horizontal_dotted.gif)


* __Without Title:__  

![Horizontal-Stepper-2](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/stepper_horizontal_2.gif)


* __With Line Text:__  

![horizontal_with_text](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/Horizontal_with_text.gif)

![Horizontal-Stepper-4](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/horizontal_text_line.gif)


* __Round Rectangle Border:__  

![RRect_Horizontal_Stepper](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/RRect_Horizontal_Stepper.gif)
 


## Vertical-Stepper

![Vertical-Stepper](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/stepper_vertical.gif)        ![Vertical-Stepper-3](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/vertical_3.gif)    ![Vertical-Stepper-2](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/stepper_vertical_2.gif)   ![Vertical-Stepper-4](https://github.com/ma7moud3osman/showcase/blob/main/easy_stepper/vertical_line.gif)     



## Contributions

Feel free to contribute to this project.

If you find a bug or want a feature, but don't know how to fix/implement it, please fill an [issue](https://github.com/ma7moud3osman/easy_stepper/issues).  
If you fixed a bug or implemented a feature, please send a [pull request](https://github.com/ma7moud3osman/easy_stepper/pulls).

## Connect with me

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ma7moud3osman)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ma7moud3osman/)  [![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/MaHmOuD_A_OsMaN) 


## Support

* Please __Like__ to __support__!

* [![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/ma7moud3osman)

## Built with

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

![Love](https://ForTheBadge.com/images/badges/built-with-love.svg)