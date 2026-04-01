# BMI Calculator App

## Description

This is a Flutter application that calculates Body Mass Index (BMI) using the user's height and weight.

## Features

- Welcome screen
- Input screen for height and weight
- BMI calculation
- Result screen with BMI category and advice

## Technologies Used

- Flutter
- Dart

## How to Run

1. Open the project in VS Code
2. Run this command in terminal:
   flutter run

## Project Structure

- lib/main.dart
- lib/screens/welcome_screen.dart
- lib/screens/input_screen.dart
- lib/screens/result_screen.dart

## Author

Mr ozy
Computer Engieering Student

## Project Description

### Research Problem

This application solves the problem of quickly calculating Body Mass Index (BMI) to help users understand their health status.

### Motivation

Maintaining a healthy BMI is important for overall health. This app provides a simple and fast way for users to check their BMI.

### Control Flow

1. User opens the app (Welcome Screen)
2. User enters height and weight (Input Screen)
3. App calculates BMI
4. Result is displayed with advice (Result Screen)

### Implementation Strategy

The app is built using Flutter and consists of multiple screens:

- main.dart → Entry point
- welcome_screen.dart → First screen
- input_screen.dart → User input
- result_screen.dart → Displays BMI result

BMI is calculated using the formula:
BMI = weight / (height × height)
