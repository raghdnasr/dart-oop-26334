# Dart OOP Assignment - Raghda Nasr (ID: 26334)

## Overview
This repository contains the Dart Object-Oriented Programming (OOP) assignment covering classes, inheritance, encapsulation, getters/setters, and bug fixing.

## Files Included
- `main.dart`: Implements `BusCard` and `StudentCard` along with the `main` execution flow.
- `bug_hunt.dart`: Implements `Phone` and `SmartPhone` classes with encapsulation (`_brand`, `_battery`, `_system`), battery range validation (`0` to `100`), and constructor chaining via `super`.

## Bug Fixes in `bug_hunt.dart`
- Added proper private fields (`_brand`, `_battery`, `_system`) and initialized them safely.
- Implemented `battery` getter and setter with validation (`0` to `100`).
- Fixed `SmartPhone` constructor call to `super(brand, battery)`.
-