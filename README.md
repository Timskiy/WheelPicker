![Banner](https://github.com/AigeStudio/WheelPicker/blob/main/Previews/main/Banner.jpg)

> ⚠️ This is a maintained fork of [AigeStudio/WheelPicker](https://github.com/AigeStudio/WheelPicker), published to JitPack under:
>
> `implementation 'com.github.timskiy:WheelPicker:v1.1.3'`

---

# WheelPicker

[![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg)](https://github.com/timskiy/WheelPicker)
[![License](https://img.shields.io/badge/License-Apache%202-blue.svg)](LICENSE)

A customizable and smooth Android wheel selector. Includes `WheelDatePicker`, `WheelYearPicker`, `WheelMonthPicker`, `WheelDayPicker`.

---

## Preview

![Preview](https://github.com/AigeStudio/WheelPicker/blob/main/Previews/main/Preview.gif)

## Demo

[📱 Download Demo APK](https://github.com/AigeStudio/WheelPicker/blob/main/APK/Demo.apk)

---

## 🔧 Setup

### Add JitPack to your project `build.gradle`:
```gradle
allprojects {
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```

### Add dependency:
```gradle
implementation 'com.github.timskiy:WheelPicker:v1.1.3'
```

---

## 📦 Alternative: Import as module

1. Clone or download this repository
2. Copy the `wheelpicker` module into your project
3. In your `settings.gradle`:
```gradle
include ':wheelpicker'
project(':wheelpicker').projectDir = new File('libs/wheelpicker')
```
4. In `app/build.gradle`:
```gradle
implementation project(':wheelpicker')
```

---

## 📚 Usage

See the [Wiki](https://github.com/AigeStudio/WheelPicker/wiki/WIKI) for detailed usage and examples.

---

## Widgets

### WheelDatePicker
![WheelDatePicker](https://github.com/AigeStudio/WheelPicker/blob/main/Previews/main/WheelDatePicker.gif)

### WheelYearPicker
![WheelYearPicker](https://github.com/AigeStudio/WheelPicker/blob/main/Previews/main/WheelYearPicker.gif)

### WheelMonthPicker
![WheelMonthPicker](https://github.com/AigeStudio/WheelPicker/blob/main/Previews/main/WheelMonthPicker.gif)

### WheelDayPicker
![WheelDayPicker](https://github.com/AigeStudio/WheelPicker/blob/main/Previews/main/WheelDayPicker.gif)

---

## Features

- Cyclic scrolling of items
- Custom visible item count
- Custom text color, size, spacing
- Selection listener
- Indicator & curtain support
- Atmospheric and perspective effects
- Curved wheel display

---

## License

```
Copyright 2015-2024

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at:

    http://www.apache.org/licenses/LICENSE-2.0
```
