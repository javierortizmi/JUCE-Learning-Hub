# Tutorials

This folder contains small, focused example projects that illustrate core JUCE concepts and features.

Each tutorial is designed to be easy to understand and extend, ideal for learning specific aspects of JUCE step-by-step.

---

## Tutorials Included

| Tutorial Name  | Description                        | Difficulty |
| -------------- | -------------------------------- | ---------- |
| HelloWorld     | Basic JUCE application skeleton  | Beginner   |

---

## How to Build

Each tutorial contains a `.jucer` project file for use with the Projucer, and a `CMakeLists.txt` for building with CMake.

Make sure you have the JUCE submodule initialized:

```bash
git submodule update --init --recursive
```

Build using either:

- **Projucer**: Open the `.jucer` file, save the project, then build with your IDE.
- **CMake**: Run `cmake` and build from the command line or your IDE.

---

Enjoy learning JUCE! 🚀
